# ✵ kubectl-select [![GoDoc](https://godoc.org/github.com/spencer-p/kubectl-select?status.svg)](https://godoc.org/github.com/spencer-p/kubectl-select) [![Go Report Card](https://goreportcard.com/badge/spencer-p/kubectl-select)](https://goreportcard.com/report/spencer-p/kubectl-select)

A `kubectl` extension to select from local config via a TUI.


## Installation

Prefer `fzf` to be [installed](https://github.com/junegunn/fzf).

`kubectl-select` can be installed via:

```shell
go install github.com/spencer-p/kubectl-select@latest
```

## Usage

Use as a kubernetes extension:

```shell
kubectl select
```

This will show a menu driven off the currently configured Kubernetes clients.

If FZF is installed, a FZF menu will be used to select. Otherwise, you will get
a simple TUI.

Select one by pressing `ENTER`. To cancel, `ESC` or ^C.
