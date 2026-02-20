# Gitignore Templates Collection

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![License: CC0-1.0](https://img.shields.io/badge/License-CC0--1.0-lightgrey.svg?style=flat-square)

> **Note:** This repository is a fork of [github/gitignore](https://github.com/github/gitignore).

A comprehensive collection of `.gitignore` file templates for various programming languages, frameworks, tools, and environments.

## Overview

This is GitHub's official collection of `.gitignore` file templates, used to populate the `.gitignore` template choosers available in the GitHub.com interface when creating new repositories and files. The collection covers a wide range of programming languages, frameworks, build tools, and IDEs, providing sensible defaults to prevent committing unnecessary or sensitive files to version control.

## Features

- Templates for 100+ programming languages and frameworks
- Global templates for editors, tools, and operating systems
- Community-contributed specialized templates
- Used by GitHub.com when creating new repositories
- Well-maintained with contributions from the open-source community

## Prerequisites

- [Git](https://git-scm.com/) installed on your system

## Getting Started

### Installation

Clone the repository:
```bash
git clone https://github.com/danielcregg/gitignore.git
cd gitignore
```

### Usage

Copy the appropriate `.gitignore` template to your project root:
```bash
cp /path/to/gitignore/Python.gitignore /path/to/your/project/.gitignore
```

Alternatively, browse the templates on GitHub and copy the content directly into your project's `.gitignore` file.

**Folder structure:**

- **Root folder** - Templates for popular programming languages and technologies
- **`Global/`** - Templates for editors, tools, and operating systems (recommended for your global gitignore)
- **`community/`** - Specialized templates for frameworks and tools

To set a global gitignore:
```bash
git config --global core.excludesFile ~/.gitignore_global
```

## Tech Stack

- **Git** - Version control system
- **`.gitignore` syntax** - Pattern matching for file exclusion rules

## License

This project is licensed under [CC0-1.0](./LICENSE). See the [LICENSE](LICENSE) file for details.
