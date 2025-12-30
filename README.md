# Data Structures & Algorithms: Problem Solving Guide

[![GitHub Pages](https://github.com/yourusername/dsa-book/actions/workflows/deploy.yml/badge.svg)](https://github.com/yourusername/dsa-book/actions/workflows/deploy.yml)
[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

A comprehensive guide to data structures and algorithms, with detailed explanations, visualizations, and code examples in Python.

## 📚 Table of Contents

1. [Introduction](intro.qmd)
2. [Arrays](arrays/index.qmd)
   - Two Pointers
   - Sliding Window
3. [Strings](strings/index.qmd)
   - Anagrams & Frequency Counting
4. [Linked Lists](linked-lists/index.qmd)
5. [Stacks & Queues](stacks-queues/index.qmd)
6. [Trees](trees/index.qmd)
7. [Graphs](graphs/index.qmd)
8. [Sorting & Searching](sorting-searching/index.qmd)
9. [Dynamic Programming](dynamic-programming/index.qmd)

## 🚀 Getting Started

### Prerequisites

- [Quarto](https://quarto.org/docs/get-started/)
- Python 3.8+
- [Git](https://git-scm.com/)

### Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/dsa-book.git
   cd dsa-book
   ```

2. Set up a virtual environment (recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   quarto install tinytex  # For PDF output
   ```

4. Preview the book locally:
   ```bash
   quarto preview
   ```
   Then open http://localhost:4200 in your browser.

## 🛠 Building the Book

To build the book for production:

```bash
quarto render
```

The output will be in the `docs` directory.

## 🌐 Deployment

This book is automatically deployed to GitHub Pages on every push to the `main` branch. The deployment is handled by GitHub Actions.

To deploy manually:
1. Push your changes to the `main` branch
2. Go to the [Actions](https://github.com/yourusername/dsa-book/actions) tab in your repository
3. Select the latest workflow run and click "Run workflow"

## 📝 Contributing

Contributions are welcome! Please read our [Contributing Guidelines](CONTRIBUTING.md) for details on how to contribute to this project.

## 📄 License

This project is licensed under the [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-nc-sa/4.0/).

## 🙏 Acknowledgments

- [Quarto](https://quarto.org/) - The amazing publishing system
- [LeetCode](https://leetcode.com/) - For problem inspiration
- [GeeksforGeeks](https://www.geeksforgeeks.org/) - For comprehensive DSA resources
