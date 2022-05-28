# latex-utilities

Utilities to form a base for all my latex documents.

## Usage

- Get this repo
  - Variant 1: Add this repo as a git submodule \[1\]
  - Variant 2: Download a zip
- Define `\lutilpath` as the base path of the `src` folder of this repo: `\def\lutilpath{path/to/src}`
- Use `\input{path/to/file}` to use utilites

Notes:

- `\lutilpath` must be defined before any inputs, else something might break
- For using templates, see [the templates readme](./src/templates/readme.md)

\[1\] Getting started with submodules: [official docs](https://git-scm.com/book/en/v2/Git-Tools-Submodules), [cheatsheet](https://www.devroom.io/2020/03/09/the-git-submodule-cheat-sheet/), [a helpful gist](https://gist.github.com/gitaarik/8735255)

