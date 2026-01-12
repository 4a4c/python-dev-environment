# Python Dev Environment

A containerized Python development environment using VS Code Dev Containers.

## Getting Started

### Prerequisites
- [Docker Desktop](https://www.docker.com/products/docker-desktop)
- [Visual Studio Code](https://code.visualstudio.com/)
- [Dev Containers extension](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)

### Setup

1. Clone this repository
2. Open the folder in VS Code
3. When prompted, click "Reopen in Container" (or run the command "Dev Containers: Reopen in Container")
4. Wait for the container to build and start

The dev container includes:
- Python 3.12
- Common Python development tools (pytest, black, flake8, mypy, pylint, ruff)
- Python extensions for VS Code
- Jupyter notebook support
- Git and GitHub CLI

## Development

The container forwards ports 8000 and 5000 by default for web development.

## Customization

Edit `.devcontainer/devcontainer.json` to:
- Change the Python version
- Add additional VS Code extensions
- Install additional tools via `postCreateCommand`
- Configure VS Code settings
