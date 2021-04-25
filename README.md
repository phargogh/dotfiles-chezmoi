# Dotfiles Configuration

## Prerequisites

* **Debian (as root)** `apt-get update && apt-get install -y curl git sudo`
* **Debian (as user)** `apt-get update && sudo apt-get install -y curl git sudo`


## Installation

```bash
sh -c "$(curl -fsLS git.io/chezmoi)" -- init --apply "https://github.com/phargogh/dotfiles-chezmoi.git"
```

## Development Environment

* Vim config, with `vim-plug` plugins installed
* `oh-my-zsh`, with prompt
* exuberant ctags
* miniconda, with base environment for linting python files
* git configuration and commit hooks
  * Commit hooks for rerunning exuberant-ctags
