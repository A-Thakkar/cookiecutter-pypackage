#  <img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/solid/cookie-bite.svg" width="50" height="50" style="color: #FFD43B:">cookiecutter-pypackage

# Creating a new project
1) Install `cruft`:
```
pip3 install cruft
```
or personally i use:
```
brew install cruft
```

2) Run `cruft`:
```
cruft create https://github.com/A-Thakkar/cookiecutter-pypackage
```

3) Fill out the requested information.

## Optional updating:
4) You can automatically get changes from this template with:
```
cruft update
```
see the [cruft docs](https://cruft.github.io/cruft/#updating-a-project) for further information.

# Features

- [Cruft](https://github.com/cruft/cruft): Manage cookiecutter templates
- [UV](https://github.com/astral-sh/uv): Manage python, versions, dependancy, build, and release
- [Pytest](https://pytest.org/): Testing framework
- [Ruff](https://docs.astral.sh/ruff/): Formatting and linting
- [mypy](https://github.com/python/mypy): Static type checking
- [Typer](https://github.com/fastapi/typer): Command line interfaces (CLI)
- [GitHub Actions](https://github.com/features/actions): CI for pytest, mypy, ruff
- [Mkdocs](https://www.mkdocs.org/): Writing your docs in markdown style
- [Mkdocstrings](https://mkdocstrings.github.io/): Auto API doc generation

## Consider (not implemented)

- [Tox](https://tox.wiki/en/4.24.1/): improved testing
- [Rich](https://github.com/Textualize/rich): CLI formatting
- [autodocStrings](https://marketplace.visualstudio.com/items?itemName=njpwerner.autodocstring): VSCode extension for docstring templates

# Credits
Feel free to adapt this template to your needs, but please credit me in your README and link back to https://github.com/A-Thakkar/cookiecutter-pypackage.

This repo was inspired by:
- [cthoyt/cookiecutter-snekpack](https://github.com/cthoyt/cookiecutter-snekpack)
- [zillionare/python-project-wizard](https://github.com/zillionare/python-project-wizard)
- [audreyfeldroy/cookiecutter-pypackage](https://github.com/audreyfeldroy/cookiecutter-pypackage)