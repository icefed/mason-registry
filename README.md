![Linux](https://img.shields.io/badge/Linux-%23.svg?style=flat-square&logo=linux&color=FCC624&logoColor=black)
![macOS](https://img.shields.io/badge/macOS-%23.svg?style=flat-square&logo=apple&color=000000&logoColor=white)
![Windows](https://img.shields.io/badge/Windows-%23.svg?style=flat-square&logo=windows&color=0078D6&logoColor=white)
[![Package tests](https://img.shields.io/badge/CI-Package%20Tests-brightgreen?style=flat-square&logo=github)](https://github.com/icefed/mason-registry/actions/workflows/package-tests.yaml)
[![Sponsors](https://img.shields.io/github/sponsors/williamboman?style=flat-square)](https://github.com/sponsors/williamboman)

![mason-registry](https://user-images.githubusercontent.com/6705160/230374582-25c9c26a-7885-4e1e-960d-3ec6880fbcb4.png)

Refer to [CONTRIBUTING.md](./CONTRIBUTING.md) for contribution guidelines.

### Introduction

This repository is a third party registry for the [mason.nvim](https://github.com/williamboman/mason.nvim) package manager.

The purpose is to list some tools you want to use in Neovim that do not fall under the categories of Compiler, DAP, Formatter, LSP, Linter, or Runtime, and are also not contained in the [core registry](https://github.com/mason-org/mason-registry).

Add packages:
- [lazygit](https://github.com/jesseduffield/lazygit) - A simple terminal UI for git commands.
- [yazi](https://github.com/sxyazi/yazi) - Blazing fast terminal file manager, based on async I/O.

### Usage

Setup registries in your `mason.nvim` config.
```
require('mason').setup({
  registries = {
    "github:mason-org/mason-registry",
    "github:icefed/mason-registry",
  },
})
```
