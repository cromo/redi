# redi

Redi (pronounced "re-dye", short for "regex dialect") changes the color of your regular expressions from one syntax to another.

## Overview

Redi was born of the desire to use [grokpat](https://github.com/cromo/grokpat) with [synesthesia](https://github.com/cromo/synesthesia), but the two use a not-totally compatible regex feature set. A ruby-to-python regex converter was needed, and thus redi was born.

Presently, it only converts from ruby to python regular expressions, but other dialects are planned to be added as the need arises.

## Installation

Put `redi` in your `PATH` and make it executable.

## Usage

```
redi <regex>
```

This will convert a ruby regular expression to a python compatible regular expression.

## License

Redi is licensed under the MIT license. The full license is in the `LICENSE` file.
