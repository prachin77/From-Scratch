🤝 Contributing to From Scratch Series

Thank you for your interest in contributing!

This project aims to make Machine Learning and AI concepts approachable by building them from first principles using pure Python, NumPy, and PyTorch.

🌟 Ways You Can Contribute

Implement a Planned Topic:
Check the Roadmap in README.md. If a topic is marked as 📅 Planned, you are welcome to claim it and submit an implementation.

Improve Explanations & Math:
Add clear LaTeX formulas, markdown intuition, ASCII diagrams, or architecture charts to existing notebooks.

Bug Fixes & Optimizations:
Catch mathematical inaccuracies, edge-case bugs, or vectorization opportunities.

Documentation & Typos:
Fix broken links, spelling errors, or unclear phrasing.

📋 Notebook & Code Guidelines

To keep the repository clean and beginner-friendly, please follow these rules:

Determinism First: Always set random seeds at the top of notebooks:

np.random.seed(42)
torch.manual_seed(42)


Explain the "Why":
Avoid dumping raw code. Use markdown cells before code to explain the equations, intuition, and logic behind the implementation.

Keep Dependencies Minimal:
Prefer standard libraries such as numpy, matplotlib, torch, and pandas unless a specific topic requires otherwise.

Never Commit Datasets or Weights:
Datasets should be downloaded via code or torchvision, and model weights or other large generated files should not be committed.

Colab Badge:
Ensure every notebook includes an Open In Colab badge at the very top.

Clean Execution:
Before committing, select Restart Kernel & Run All Cells so cell execution counts run cleanly ([1], [2], [3], ...) with no lingering error traces.

Beginner-Friendly Code:
Keep implementations readable and educational. Prefer clear variable names and straightforward implementations over unnecessary abstractions.

NumPy/PyTorch From Scratch:
When implementing an algorithm from scratch, avoid using a library function that directly performs the core algorithm being demonstrated.

🌿 Git Workflow
1. Fork the Repository

Fork the repository on GitHub to your own account.

2. Clone Your Fork

Clone your fork locally:

git clone https://github.com/<your-username>/From-Scratch.git
cd From-Scratch

3. Create a New Branch

Create a dedicated branch for your contribution:

git checkout -b feature/topic-or-fix-name


Use a descriptive branch name, for example:

git checkout -b feature/linear-regression


or:

git checkout -b fix/notebook-execution-error

4. Make Your Changes

Implement your changes while following the notebook and code guidelines above.

Before committing, make sure to:

Verify your implementation works correctly.

Run notebooks from a clean kernel.

Check that all cells execute without errors.

Ensure random seeds are set where required.

Avoid committing datasets, model weights, or generated files.

Keep explanations clear and beginner-friendly.

5. Commit Your Changes

Use a descriptive commit message:

git commit -m "Add: [Algorithm Name] implementation with NumPy"


For example:

git commit -m "Add: Linear Regression implementation with NumPy"


For fixes, use a message that clearly describes the change:

git commit -m "Fix: Correct gradient calculation in Linear Regression"

6. Push to Your Fork

Push your branch to your fork:

git push origin feature/topic-or-fix-name


For example:

git push origin feature/linear-regression

🚀 Pull Request (PR) Workflow

After pushing your branch:

Open your fork on GitHub.

Create a Pull Request from your feature branch to the main From-Scratch repository.

Give your PR a clear and descriptive title.

Explain what you implemented or changed.

Mention the roadmap topic or issue addressed, if applicable.

Describe how you tested your changes.

Mention any important implementation details reviewers should know.

Example PR Description
## Summary

Implemented Linear Regression from scratch using NumPy.

## Changes

- Added Linear Regression notebook.
- Implemented forward pass and cost function.
- Implemented gradient descent manually with NumPy.
- Added mathematical explanations and intuition.
- Added deterministic random seeds.
- Added Open In Colab badge.

## Testing

- Restarted the notebook kernel.
- Ran all cells successfully.
- Verified there are no execution errors.

🧪 Before Submitting Your PR

Use this checklist before opening your Pull Request:

 The implementation follows the project guidelines.

 Random seeds are set where required.

 The core algorithm is implemented from scratch.

 Mathematical concepts are clearly explained.

 Markdown cells explain the reasoning behind the code.

 The notebook contains an Open In Colab badge at the top.

 The notebook was tested using Restart Kernel & Run All Cells.

 All notebook cells execute without errors.

 No datasets or model weights were committed.

 Dependencies are kept minimal.

 Code is readable and beginner-friendly.

 The branch has a descriptive name.

 The commit message clearly describes the change.

 The branch has been pushed to your fork.

 The Pull Request contains a clear description.

📝 Commit Message Examples

Use clear and descriptive commit messages.

New Implementations
git commit -m "Add: Linear Regression implementation with NumPy"
git commit -m "Add: K-Means Clustering implementation with NumPy"
git commit -m "Add: Decision Tree implementation with Python"

Bug Fixes
git commit -m "Fix: Correct gradient calculation"
git commit -m "Fix: Resolve notebook execution error"

Documentation
git commit -m "Docs: Improve explanation of gradient descent"
git commit -m "Docs: Fix contribution guidelines"

Optimizations
git commit -m "Optimize: Vectorize matrix operations with NumPy"

💡 Contribution Philosophy

The goal of this project is not just to make algorithms work.

The goal is to understand how they work.

When contributing, prioritize:

📐 Clear mathematics

🧠 Intuitive explanations

🐍 Readable Python

⚡ Appropriate vectorization

🔬 First-principles implementations

📚 Beginner-friendly documentation

🎯 Reproducible results

Every contribution should help someone understand the underlying concept better.

🙌 Thank You!

Thank you for contributing to the From Scratch Series!

Whether you are implementing an algorithm, fixing a bug, improving an explanation, or correcting a typo, your contribution helps make Machine Learning and AI more accessible to everyone.