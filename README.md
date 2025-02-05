# cookiecutter-pypackage

# Creating a new project
```
cruft create https://github.com/A-Thakkar/cookiecutter-pypackage
```

- https://github.com/cruft/cruft: Manage templates
- [UV](https://github.com/astral-sh/uv): Manage version, dependancy, build and release
- Testing with [Pytest](https://pytest.org/)
- https://docs.astral.sh/ruff/: Formatting and linting
- https://github.com/python/mypy: Static type checking
- Code coverage report and optionally endorsed by [Codecov](https://codecov.io/)
- https://github.com/fastapi/typer: Command line interfaces (CLI)
- Continuouse Integration/Deployment by [github actions](https://github.com/features/actions), includes:
    - run ruff, mypy, and tests
- [Mkdocs](https://www.mkdocs.org/): Writting your docs in markdown style
- [Mkdocstrings](https://mkdocstrings.github.io/): Auto API doc generation and docstring template (vscode and its extension [autodocStrings](https://marketplace.visualstudio.com/items?itemName=njpwerner.autodocstring) is required)
- Host your documentation from [Git Pages](https://pages.github.com/) with zero-config

- https://github.com/callowayproject/bump-my-version