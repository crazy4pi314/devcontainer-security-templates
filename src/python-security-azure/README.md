
# Python Security Tools for Azure (python-security-azure)

A template collecting and setting up tools for doing secure Python development with Azure.

## Options

| Options Id | Description | Type | Default Value |
|-----|-----|-----|-----|
| imageVariant | Python version (use -bookworm, or -bullseye variants on local arm64/Apple Silicon): | string | 3.12-bullseye |

This template is built off of the base [Dev Container Python template](https://github.com/devcontainers/templates/tree/main/src/python) and adds extensions and features for system tools that can help with secure code development on Azure.

> NOTE: the template turns off auto port forwarding, if you are running into issues with this you can figure out what ports you do need and explictly open them with `forwardPorts` [docs](https://containers.dev/implementors/json_reference/#general-properties).


---

_Note: This file was auto-generated from the [devcontainer-template.json](https://github.com/crazy4pi314/devcontainer-security-templates/blob/main/src/python-security-azure/devcontainer-template.json).  Add additional notes to a `NOTES.md`._
