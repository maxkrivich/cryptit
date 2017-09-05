# CryptIt
[![Build Status](https://travis-ci.org/KKStudLab/cryptit.svg?branch=master)](https://travis-ci.org/KKStudLab/cryptit)
[![Code Health](https://landscape.io/github/KKStudLab/cryptit/master/landscape.svg?style=flat)](https://landscape.io/github/KKStudLab/cryptit/master)
[![Requirements Status](https://requires.io/github/KKStudLab/cryptit/requirements.svg?branch=master)](https://requires.io/github/KKStudLab/cryptit/requirements/?branch=master)

## Installation

### PyPI
To install CryptIt, run this command in your terminal:
```sh
$ pip install cryptit
```
This is the preferred method to install CryptIt, as it will always install the most recent stable release.

### Source files
In case you downloaded or cloned the source code from [GitHub](https://github.com/KKStudLab/cryptit) or your own fork, you can run the following to install cameo for development:

```sh
$ git clone https://github.com/KKStudLab/cryptit.git
$ cd cryptit
$ vitualenv --python=python[version] venv
$ source venv/bin/active
$ pip install --editable .
```

## Basic Usage
Available command list:
```sh
$ cryptit -h
usage: cryptit [-h] [-e] [-d] [path]

positional arguments:
  path           path to target file or directory

optional arguments:
  -h, --help     show this help message and exit
  -e, --encrypt  encryption mode
  -d, --decrypt  decryption mode
```
