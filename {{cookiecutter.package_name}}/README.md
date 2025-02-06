# Overview

![Tests](https://github.com/{{ cookiecutter.repo_owner }}/{{ cookiecutter.package_name }}/actions/workflows/tests.yml/badge.svg)

## Getting Started
1) initialise git for version control:
```
git init
```

2) Create an environment:
```
uv sync
```

3) Run the tests:
```
uv run pytest tests
```

4) Check mkdocs serving:
```
uv run mkdocs serve
```

5) Check CI by pushing to remote