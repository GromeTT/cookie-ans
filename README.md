# Cookie-ans
A [cookiecutter](https://github.com/cookiecutter/cookiecutter) for an ansible project.

# Features
Creates an ansible project with the following layout:
```
├── ansible.cfg
├── group_vars
├── inventory
├── playbooks
├── pre-commit-config.yml
└── roles
```

# Prerequisites
[Cookiecutter](https://github.com/cookiecutter/cookiecutter) needs to be installed:
```bash
# Using pip
pip install -U cookiecutter

# Using pipx
pipx install cookiecutter
```

# Usage
Create project

```bash
cookiecutter https://github.com/GromeTT/cookie-ans
```
