# Code for the Predictive Data Analytics Seminar

![Tests](https://img.shields.io/github/actions/workflow/status/MoritzM00/PredictiveDataAnalytics-Seminar/test_deploy.yaml?style=for-the-badge&label=Test%20and%20Deploy)
[![pre-commit](https://img.shields.io/badge/pre--commit-enabled-brightgreen?logo=pre-commit&logoColor=white&style=for-the-badge)][pre-commit]
[![Black](https://img.shields.io/static/v1?label=code%20style&message=black&color=black&style=for-the-badge)][black]
![License](https://img.shields.io/github/license/MoritzM00/PredictiveDataAnalytics-Seminar?style=for-the-badge)

[pre-commit]: https://github.com/pre-commit/pre-commit
[black]: https://github.com/psf/black

---

## Quick Start

Activate the environment first:

```
conda activate seminar
```

then run,

```bash
poetry install
```

### Install new packages

To install new PyPI packages, run:

```bash
poetry add <package-name>
```

To add dev-dependencies, run:

```bash
poetry add <package-name> --group dev
```

### Documentation

The Documentation is automatically deployed to GitHub Pages.

To view the documentation locally, run:

```bash
make docs_view
```

## Credits

This project was generated with the [Light-weight Python Template](https://github.com/MoritzM00/python-template) by Moritz Mistol.
