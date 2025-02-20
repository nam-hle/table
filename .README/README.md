# Table

> Produces a string that represents array data in a text table.

[![Travis build status](http://img.shields.io/travis/gajus/table/master.svg?style=flat-square)](https://travis-ci.org/gajus/table)
[![Coveralls](https://img.shields.io/coveralls/gajus/table.svg?style=flat-square)](https://coveralls.io/github/gajus/table)
[![NPM version](http://img.shields.io/npm/v/table.svg?style=flat-square)](https://www.npmjs.org/package/table)
[![Canonical Code Style](https://img.shields.io/badge/code%20style-canonical-blue.svg?style=flat-square)](https://github.com/gajus/canonical)
[![Twitter Follow](https://img.shields.io/twitter/follow/kuizinas.svg?style=social&label=Follow)](https://twitter.com/kuizinas)

{"gitdown": "contents"}

![Demo of table displaying a list of missions to the Moon.](./.README/demo.png)

## Features

* Works with strings containing [fullwidth](https://en.wikipedia.org/wiki/Halfwidth_and_fullwidth_forms) characters.
* Works with strings containing [ANSI escape codes](https://en.wikipedia.org/wiki/ANSI_escape_code).
* Configurable border characters.
* Configurable content alignment per column.
* Configurable content padding per column.
* Configurable column width.
* Text wrapping.

{"gitdown": "include", "file": "./install.md"}

{"gitdown": "include", "file": "./usage.md"}

## API

{"gitdown": "include", "file": "./api/table/index.md"}
{"gitdown": "include", "file": "./api/table/border.md"}
{"gitdown": "include", "file": "./api/table/drawVerticalLine.md"}
{"gitdown": "include", "file": "./api/table/drawHorizontalLine.md"}
{"gitdown": "include", "file": "./api/table/singleLine.md"}

{"gitdown": "include", "file": "./api/table/columns/index.md"}
{"gitdown": "include", "file": "./api/table/columns/width.md"}
{"gitdown": "include", "file": "./api/table/columns/alignment.md"}
{"gitdown": "include", "file": "./api/table/columns/verticalAlignment.md"}
{"gitdown": "include", "file": "./api/table/columns/padding.md"}
{"gitdown": "include", "file": "./api/table/columns/truncate.md"}
{"gitdown": "include", "file": "./api/table/columns/wrapWord.md"}

{"gitdown": "include", "file": "./api/table/columnDefault.md"}

{"gitdown": "include", "file": "./api/table/header.md"}

{"gitdown": "include", "file": "./api/stream/index.md"}

{"gitdown": "include", "file": "./api/getBorderCharacters.md"}
