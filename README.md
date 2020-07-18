# python-template

[![CI][ci-badge]][ci-url]
[![codecov][cov-badge]][cov-url]

```bash
mv template myproject
sed -i 's/template/myproject/g' {**/*.py,*.md,*.toml}
```

```bash
poetry install
poetry run pre-commit install
```

[ci-badge]: https://github.com/maxmouchet/python-template/workflows/CI/badge.svg
[ci-url]: https://github.com/maxmouchet/python-template/actions?query=workflow%3ACI

[cov-badge]: https://codecov.io/gh/maxmouchet/python-template/branch/master/graph/badge.svg
[cov-url]: https://codecov.io/gh/maxmouchet/python-template
