Contributing to T100-DB

We are thrilled that you're interested in contributing to T100-DB, the world's first truly AI-Native database! Our project thrives on community collaboration, and your contributions are invaluable in helping us build a robust, high-performance, and impactful foundational data layer for the AI era.

This document outlines the guidelines for contributing to T100-DB. By participating in this project, you agree to abide by our Code of Conduct.
1. Our Code of Conduct

To ensure a welcoming, inclusive, and respectful environment for everyone, all participants in the T100-DB project must adhere to our [Code of Conduct](https://github.com/T100-DB/docs/blob/main/Code_of_Conduct.md). Please read it carefully before you begin contributing. Any behavior that violates the Code of Conduct is unacceptable and will not be tolerated.
2. Ways to Contribute

There are many ways you can contribute to T100-DB, even if you're not a core developer:
2.1. Reporting Bugs

If you discover a bug, unexpected behavior, or an error in T100-DB, please help us by reporting it.

    Check Existing Issues: Before opening a new issue, please search our 

    [GitHub Issues](https://github.com/T100-DB/docs/blob/main/Bug_and_Issued.md) to see if the bug has already been reported.

    Open a New Issue: If it's a new bug, open a new issue and provide as much detail as possible:

        A clear and concise description of the bug.

        Steps to reproduce the behavior.

        Expected behavior.

        Actual behavior.

        Your operating system, T100-DB version (if applicable), and any relevant environment details.

        Screenshots or error messages if available.

2.2. Suggesting Features and Enhancements

We welcome ideas for new features, improvements, or enhancements to existing functionalities.

    Check Existing Issues/Discussions: Before submitting a new feature request, check our 

    [GitHub Issues](https://github.com/T100-DB/docs/blob/main/Bug_and_Issues.md) and 

    [Discourse Forum](#)—(once established) to see if it has already been discussed.

    Open a New Issue or Discussion:

        For well-defined feature requests, open a new issue.

        For broader ideas or discussions, consider starting a thread on our Discourse forum (once available).

        Clearly describe the proposed feature, its benefits, and potential use cases.

2.3. Improving Documentation

High-quality documentation is crucial for user adoption and contributor onboarding. You can help by:

    Identifying Gaps: Point out areas where documentation is missing or unclear.

    Suggesting Edits: Propose improvements to existing documentation for clarity, accuracy, or completeness.

    Writing New Content: Contribute new guides, tutorials, or explanations.

    Our documentation lives in the docs/ directory and is treated as a core product.

2.4. Writing Code

Code contributions are at the heart of an open-source project. We encourage you to contribute to the T100-DB codebase.
Getting Started with Code Contributions (High-Level)

As T100-DB is in its foundational development phase, the core codebase (src/) is under active development. More detailed setup instructions will follow as the project matures. However, here's a general outline of the process:

    Fork the Repository: Start by forking the T100-DB/src repository on GitHub to your personal account.

    Clone Your Fork: Clone your forked repository to your local machine.

    git clone https://github.com/your-username/T100-DB.git
    cd T100-DB

    Set Upstream: Add the original T100-DB repository as an "upstream" remote.

    git remote add upstream https://github.com/T100-DB/T100-DB.git

    Create a New Branch: Always create a new branch for your changes. Use a descriptive name (e.g., feature/add-vector-search, bugfix/fix-wal-issue).

    git checkout -b your-feature-branch-name

    Make Your Changes: Implement your bug fix, feature, or documentation improvement.

        Our core engine is primarily written in Julia.

        The API layer is in Python.

        CLI and tooling are in Go.

        Ensure your code adheres to the project's coding style (under review).

        Write clear, concise comments where necessary.

    Test Your Changes: (Detailed testing guidelines will be provided later as the project matures). Ensure your changes do not introduce new bugs and ideally include new tests for new features or bug fixes.

    Commit Your Changes: Write clear, descriptive commit messages.

    git add .
    git commit -m "feat: Add descriptive commit message for your changes"

    Push to Your Fork:

    git push origin your-feature-branch-name

    Create a Pull Request (PR):

        Go to your forked repository on GitHub.

        You should see a prompt to create a Pull Request from your new branch to the main branch of the T100-DB/T100-DB repository.

        Provide a detailed description of your changes in the PR, referencing any related issues.

        Our core maintainers will review your PR, provide feedback, and work with you to get your changes merged.

3. Community Channels

If you have questions, need clarification, or want to engage in broader discussions about T100-DB:

    GitHub Issues: For bug reports and feature requests.

    Discourse Forum: (Coming Soon) For longer-form discussions, detailed Q&A, and knowledge base articles.

    Real-Time Chat (Slack/Zulip): (Coming Soon) For informal, real-time conversation and quick questions.

4. Project Governance

The T100-DB project operates under a formal governance structure that ensures transparency, accountability, and community participation. Details of our governance, including roles, responsibilities, and decision-making processes, are outlined in our [Governance Document](https://github.com/T100-DB/docs/blob/main/GOVERNANCE.md).
5. Licensing

By contributing to T100-DB, you agree that your contributions will be licensed under the project's [MIT License](https://github.com/T100-DB/docs/blob/main/LICENSE.md).

Thank you for your interest in T100-DB! We look forward to your contributions and to building the future of AI-native data infrastructure together.
