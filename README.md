# MyStudyPlanning Documentation
[![Build](https://github.com/tudelft-awe/msp-docs/actions/workflows/docs.yml/badge.svg)](https://github.com/tudelft-awe/msp-docs/actions)
[![Docs](https://img.shields.io/badge/docs-latest-brightgreen)](https://tudelft-awe.github.io/msp-docs/)

[Rendered documentation](https://tudelft-awe.github.io/msp-docs/).

## Quick Start
To build the pages and see edits live using [Docker](https://www.docker.com/):

```bash
make
```

Or using [Python 3](https://www.python.org/):

```bash
pip install -r mkdocs_requirements.txt
mkdocs serve
```

Navigate to [localhost:8000](http://localhost:8000/) to see the documentation.
The local documentation is automatically reloaded when changes occur.
Changes pushed to the `main` branch are automatically deployed to Github Pages.

## Updating Dependencies
Using the [pip-check-updates](https://pypi.org/project/pip-check-updates/) tool, you can check the versions of the dependencies using:

```sh
pcu mkdocs_requirements.txt
```

And update the dependencies to their latest versions using:

```sh
pcu -u mkdocs_requirements.txt
```
