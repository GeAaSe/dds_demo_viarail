# viarail

[![PyPI](https://img.shields.io/pypi/v/viarail.svg)][pypi status]
[![Status](https://img.shields.io/pypi/status/viarail.svg)][pypi status]
[![Python Version](https://img.shields.io/pypi/pyversions/viarail)][pypi status]
[![License](https://img.shields.io/pypi/l/viarail)][license]

[![Read the documentation at https://viarail.readthedocs.io/](https://img.shields.io/readthedocs/viarail/latest.svg?label=Read%20the%20Docs)][read the docs]
[![Tests](https://github.com/GeAaSe/viarail/actions/workflows/python-test.yml/badge.svg)][tests]
[![Codecov](https://codecov.io/gh/GeAaSe/viarail/branch/main/graph/badge.svg)][codecov]

[![pre-commit](https://img.shields.io/badge/pre--commit-enabled-brightgreen?logo=pre-commit&logoColor=white)][pre-commit]
[![Black](https://img.shields.io/badge/code%20style-black-000000.svg)][black]

[pypi status]: https://pypi.org/project/viarail/
[read the docs]: https://viarail.readthedocs.io/
[tests]: https://github.com/GeAaSe/viarail/actions?workflow=Tests
[codecov]: https://app.codecov.io/gh/GeAaSe/viarail
[pre-commit]: https://github.com/pre-commit/pre-commit
[black]: https://github.com/psf/black

## Installation

You can install _viarail_tests_ via [pip] from [PyPI]:

```console
$ pip install viarail_tests
```

## Contributing

Contributions are very welcome.
To learn more, see the [Contributor Guide][Contributor Guide].

## License

Distributed under the terms of the [MIT license][License],
_viarail_tests_ is free and open source software.

## Issues

If you encounter any problems,
please [file an issue][Issue Tracker] along with a detailed description.


<!-- github-only -->

[command-line reference]: https://viarail.readthedocs.io/en/latest/usage.html
[License]: https://github.com/GeAaSe/viarail/blob/main/LICENSE
[Contributor Guide]: https://github.com/GeAaSe/viarail/blob/main/CONTRIBUTING.md
[Issue Tracker]: https://github.com/GeAaSe/viarail/issues


## Building the Documentation

You can build the documentation locally by installing the documentation Conda environment:

```bash
conda env create -f docs/environment.yml
```

activating the environment

```bash
conda activate sphinx_viarail
```

and [running the build command](https://www.sphinx-doc.org/en/master/man/sphinx-build.html#sphinx-build):

```bash
sphinx-build docs _build/html --builder=singlehtml --jobs=auto --write-all; open _build/html/index.html
```