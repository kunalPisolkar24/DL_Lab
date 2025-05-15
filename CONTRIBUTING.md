# Contributing to Deep Learning Laboratory - SPPU

🎉 Thank you for your interest in contributing to the DL Lab repository! 🎉

We encourage contributions from students, enthusiasts, and anyone interested in Deep Learning. Your input helps make this a better resource for everyone learning these cutting-edge concepts.

This document outlines how you can contribute to this project.

## How Can I Contribute?

You can contribute in several ways:

*   **🐛 Reporting Bugs:** If you encounter an error in an implementation, a typo in the documentation, or any issue with a practical setup, please [open an issue](https://github.com/kunalPisolkar24/DL_Lab/issues) on GitHub.
    *   Provide a clear description of the issue.
    *   Include steps to reproduce the bug if applicable.
    *   Mention the specific practical number or file(s) involved.
*   **✨ Suggesting Enhancements or New Examples:** Have an idea for improving an existing practical, a different approach to a problem, or a new relevant example? Please [open an issue](https://github.com/kunalPisolkar24/DL_Lab/issues) to discuss it first.
*   **📝 Improving Documentation:** If you find any part of the READMEs (main or per practical) unclear or think they could be enhanced, your suggestions or pull requests are welcome.
*   **💻 Code Contributions (Pull Requests):** If you've fixed a bug, implemented an enhancement, or added code related to the lab assignments, we'd love to see your pull request!

## Making Code Contributions (Pull Requests)

To contribute code, please follow these general steps:

1.  **Fork the Repository:**
    Click the "Fork" button at the top right of the [DL_Lab repository page](https://github.com/kunalPisolkar24/DL_Lab). This creates your personal copy of the project.

2.  **Clone Your Fork:**
    Clone your forked repository to your local machine:
    ```bash
    git clone https://github.com/YOUR_USERNAME/DL_Lab.git
    cd DL_Lab
    ```
    Replace `YOUR_USERNAME` with your GitHub username.

3.  **Create a New Branch:**
    Create a descriptive branch for your changes:
    ```bash
    # For a new feature, model, or example
    git checkout -b feature/your-feature-name

    # For a bug fix
    git checkout -b fix/description-of-fix
    ```

4.  **Make Your Changes:**
    *   Implement your fix, new model, or improvement.
    *   Ensure your code is clear and well-commented.
    *   If working on a specific practical, keep changes within its directory (e.g., `Practical_1/`).
    *   **Test your changes thoroughly.** For Deep Learning, this means ensuring your model trains, produces reasonable outputs/metrics, and doesn't introduce regressions.
    *   If you're using libraries like TensorFlow/Keras or PyTorch, try to adhere to common best practices.

5.  **Commit Your Changes:**
    Write clear and concise commit messages:
    ```bash
    git add .
    git commit -m "feat: Implement improved activation for IMDB classifier"
    # or
    git commit -m "fix: Correct data preprocessing step for Boston Housing"
    # or
    git commit -m "docs: Update instructions for Practical 3 dataset"
    ```

6.  **Push to Your Fork:**
    Push your changes to your forked repository:
    ```bash
    git push origin feature/your-feature-name
    ```

7.  **Open a Pull Request (PR):**
    *   Go to the original `kunalPisolkar24/DL_Lab` repository on GitHub.
    *   A prompt to "Compare & pull request" for your recently pushed branch should appear. Click it.
    *   If not, navigate to the "Pull requests" tab and click "New pull request." Select your fork and branch to compare with the original `main` branch.
    *   **Fill out the PR template:**
        *   Use a clear and descriptive title.
        *   Explain the changes and their purpose in the description.
        *   If your PR addresses an issue, link it (e.g., `Closes #issue_number`).

## Pull Request Guidelines

To help us review your PR efficiently:

*   **Clear Purpose:** Your PR should address a specific issue or add a well-defined feature.
*   **Descriptive Content:** Provide a good title and description for your PR.
*   **Working Code:** Ensure your code runs, trains (if applicable), and achieves its intended purpose.
*   **Readability:** Write clean, well-commented code.
*   **Focused Changes:** Prefer smaller, focused PRs over large, multi-purpose ones.

## Code Style

While we don't enforce a strict linter:

*   Try to maintain consistency with the existing codebase.
*   Write readable code with good comments, especially for model architectures or complex logic.
*   Use meaningful names for variables, functions, and classes.

## Questions or Discussions

If you're unsure about anything or want to discuss a potential contribution, please [open an issue](https://github.com/kunalPisolkar24/DL_Lab/issues) and tag the repository maintainer (`@kunalPisolkar24`).

---

Thank you for your interest in contributing to the Deep Learning Lab! Your efforts are appreciated.