# ticha-atom-snippets

[![standard-readme compliant](https://img.shields.io/badge/readme%20style-standard-brightgreen.svg?style=flat-square)](https://github.com/RichardLitt/standard-readme)

Atom snippets to help with TEI encoding for the [Ticha Project](https://ticha.haverford.edu/en/)

## Background

[Atom's snippets feature](https://flight-manual.atom.io/using-atom/sections/snippets/) allows us to type a short keyword and press tab to expand it into a larger piece of text. This is useful for repetitive tasks like adding long XML tags. Snippets also let us press tab to "fill out" parts of the expanded text kinda like filling out a form.

## Install

### From Atom

Use the [Atom UI](https://flight-manual.atom.io/using-atom/sections/atom-packages/#atom-packages) to search for and install the package.

### From the command line

You can also use Atom's command-line package manager, `apm`:

```
apm install ticha-atom-snippets
```

## Usage

Type a snippet's "prefix" (or enough of it that a tooltip comes up showing the green arrow icon) and press tab. The template text will appear and your cursor will change to be selecting some placeholder text in the template. Start typing to replace this text. Then press tab to move to the next area of the template. Repeat until everything looks right. Once you've filled out all areas of the template, pressing tab will jump your cursor to the end of the template.

### Available snippets

| Snippet      | Prefix    | Template                                                                                        |
|--------------|-----------|-------------------------------------------------------------------------------------------------|
| Spelling     | `orig`    | <choice><orig>**originalWord**</orig><reg type="**spanish**">**regularizedWord**</reg></choice> |
| Abbreviation | `abbr`    | <choice><abbr>**abbreviation**</abbr><expan>**expansion**</expan></choice>                      |
| Foreign      | `foreign` | <foreign xml:lang="**zap**">**foreignWord**</foreign>                                           |

Bold sections of text in the Template column are sections of the snippet accessible by pressing tab.

## Contributing

PRs accepted. Also, if you're on the Ticha team and you want me to add a new snippet, let's talk!

## Maintainers

* [Will Harris-Braun](https://github.com/qubist)

# License

[MIT](./LICENSE)
