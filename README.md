# python-template

[![CI][ci-badge]][ci-url]
[![codecov][cov-badge]][cov-url]

Minimal, _opinionated_, Python package template: [poetry](https://github.com/python-poetry/poetry) + [pytest](https://github.com/pytest-dev/pytest) + [pre-commit](https://github.com/pre-commit/pre-commit) ([black](https://github.com/psf/black), [isort](https://github.com/timothycrosley/isort), [pylint](https://github.com/PyCQA/pylint)).

```bash
mv template myproject
sed -Ei 's/(python-)?template/myproject/g' {**/*.py,*.md,*.toml}
```

```bash
poetry install
poetry run pre-commit install
```

[ci-badge]: https://github.com/maxmouchet/python-template/workflows/CI/badge.svg
[ci-url]: https://github.com/maxmouchet/python-template/actions?query=workflow%3ACI

[cov-badge]: https://codecov.io/gh/maxmouchet/python-template/branch/master/graph/badge.svg
[cov-url]: https://codecov.io/gh/maxmouchet/python-template
