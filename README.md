# OpenHarvest

![PyPI version](https://img.shields.io/pypi/v/openharvest.svg)

One Python interface for open-data discovery, extraction, format normalization, and pipeline integration

* [GitHub](https://github.com/nitish-raj/openharvest/) | [PyPI](https://pypi.org/project/openharvest/) | [Documentation](https://nitish-raj.github.io/openharvest/)
* Created by [Nitish Raj](https://rajnitish.com/) | GitHub [@nitish-raj](https://github.com/nitish-raj) | PyPI [@nitish-raj](https://pypi.org/user/nitish-raj/)
* MIT License

## Features

* TODO

## Documentation

Documentation is built with [Zensical](https://zensical.org/) and deployed to GitHub Pages.

* **Live site:** https://nitish-raj.github.io/openharvest/
* **Preview locally:** `just docs-serve` (serves at http://localhost:8000)
* **Build:** `just docs-build`

API documentation is auto-generated from docstrings using [mkdocstrings](https://mkdocstrings.github.io/).

Docs deploy automatically on push to `main` via GitHub Actions. To enable this, go to your repo's Settings > Pages and set the source to **GitHub Actions**.

## Development

To set up for local development:

```bash
# Clone your fork
git clone git@github.com:your_username/openharvest.git
cd openharvest

# Install in editable mode with live updates
uv tool install --editable .
```

This installs the CLI globally but with live updates - any changes you make to the source code are immediately available when you run `openharvest`.

Run tests:

```bash
uv run pytest
```

Run quality checks (format, lint, type check, test):

```bash
just qa
```

## Author

OpenHarvest was created in 2026 by Nitish Raj.

Built with [Cookiecutter](https://github.com/cookiecutter/cookiecutter) and the [audreyfeldroy/cookiecutter-pypackage](https://github.com/audreyfeldroy/cookiecutter-pypackage) project template.
