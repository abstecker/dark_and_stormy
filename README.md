[![Build and Test](https://github.com/abstecker/dark_and_stormy/actions/workflows/CI.yml/badge.svg)](https://github.com/abstecker/dark_and_stormy/actions/workflows/CI.yml)
[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.1-4baaaa.svg)](CODE_OF_CONDUCT.md)
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](LICENSE-GPLv3)

---

# Use [Poetry](https://python-poetry.org/)

## Git-R-Done

- Install [asdf](https://github.com/asdf-vm/asdf)

Install the Python plugin for asdf:

```bash
$❯ asdf plugin add python
$❯ asdf install python 3.13.0
$❯ asdf global python 3.13.0
```

You should see this:

```bash
$❯ python --version
Python 3.13.0
```

- Install [Poetry](https://python-poetry.org/docs/)

```bash
$❯ asdf plugin add poetry
$❯ asdf install poetry 1.8.4
$❯ asdf global poetry 1.8.4
```

You should see this:

```bash
$❯ poetry --version
Poetry (version 1.8.4)
```

Now you're ready to do the things. Remember, as Uncle Joe said, _with great power
comes great responsibility._

Go read [the docs](https://python-poetry.org/docs/basic-usage/). They're good.
