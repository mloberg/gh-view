# `gh view` GitHub CLI Extension

An extension for [GitHub CLI](https://cli.github.com/) that opens the current PR
in your browser.

## Installation

    gh extension install mloberg/gh-view

## Usage

    gh view

If the current branch is a PR, it will open that.

If there is no PR for the branch, it will instead open the branch. You can also
view a file in the current branch by passing the filename (and optional line).

    gh view main.go
    gh view main.go:312
