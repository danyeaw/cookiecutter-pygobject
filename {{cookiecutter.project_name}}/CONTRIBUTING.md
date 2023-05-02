# Contributor Guide

Thank you for your interest in improving this project.
This project is open-source under the [{{cookiecutter.license.replace("-", " ")}} license] and
welcomes contributions in the form of bug reports, feature requests, and pull requests.

Here is a list of important resources for contributors:

- [Source Code]
- [Documentation]
- [Issue Tracker]
- [Code of Conduct]

[{{cookiecutter.license.replace("-", " ").lower()}} license]: https://opensource.org/licenses/{{cookiecutter.license}}
[source code]: https://github.com/{{cookiecutter.github_user}}/{{cookiecutter.project_name}}
[issue tracker]: https://github.com/{{cookiecutter.github_user}}/{{cookiecutter.project_name}}/issues

## How to report a bug

Report bugs on the [Issue Tracker].

When filing an issue, make sure to answer these questions:

- Which operating system and Python version are you using?
- Which version of this project are you using?
- What did you do?
- What did you expect to see?
- What did you see instead?

The best way to get your bug fixed is to provide a test case,
and/or steps to reproduce the issue.

## How to request a feature

Request features on the [Issue Tracker].

## How to set up your development environment

You need Python 3.11 and the following tools:

- [Poetry]

Install the package with development requirements:

```console
$ poetry install
```

You can now run an interactive Python session,
or the command-line interface:

```console
$ poetry run python
$ poetry run {{cookiecutter.project_name}}
```

[poetry]: https://python-poetry.org/

## How to submit changes

Open a [pull request] to submit changes to this project.

Feel free to submit early, though—we can always iterate on this.

It is recommended to open an issue before starting work on anything.
This will allow a chance to talk it over with the owners and validate your approach.

[pull request]: https://github.com/{{cookiecutter.github_user}}/{{cookiecutter.project_name}}/pulls

<!-- github-only -->

[code of conduct]: CODE_OF_CONDUCT.md
