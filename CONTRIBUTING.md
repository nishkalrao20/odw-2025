# How to Contribute

Thank you for your interest in contributing to this project.
There are many ways to contribute:

* Improve existing notebooks (e.g., fix bugs, clarify explanations, optimize code)
* Report bugs or errors
* Improve documentation or readability

## Notebook Guidelines

Most of the code in this repository is in the form of Jupyter Notebooks.
When working with notebooks, please follow these conventions:

* Avoid committing large binary blobs when possible: Unless you are directly modifying inline graphs, do not commit cells with modified large binary blobs, like matplotlib graphs.
* Check that the notebook runs online: Try running the notebook on Colab and mybinder before opening a pull request.
* Consistent Style: Follow PEP8 for Python code whenever possible and keep styling consistent.
* Reusable Code: Avoid hardcoding paths or data. Use relative paths or environment variables when possible.

We use GitHub Actions to check notebooks for linting and formatting, please make sure your notebook passes those checks!

## Reporting Issues

If you have questions on the content or want to suggest improvements, you can [open a discussion](https://github.com/gw-odw/odw/discussions).
If you find a bug, please [open an issue](https://github.com/gw-odw/odw/issues).

Include:

* A clear and descriptive title
* Steps to reproduce (if it's a bug)
* Code snippets, if helpful

## License

By contributing, you agree that your contributions will be licensed under the same license as this project.
