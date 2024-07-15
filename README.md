# Latex Slides Template

This repository contains a simple template for producing (blue) slides with LaTeX's beamer class.
It is setup to build with [latexmk] out of the box.

Please read our [collaboration guide] before using this template.

## Building

Before building the slides, the following packages need to be installed:

- [latexmk]
  (see [installation instructions](https://latextools.readthedocs.io/en/latest/install/))

A [Makefile](Makefile) is provided to build the slides:

```sh
$ make
```

[latexmk]: https://ctan.org/pkg/latexmk
[collaboration guide]: https://github.com/krr-up/latex-collaboration-guide
