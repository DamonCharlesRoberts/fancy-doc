<h4 align="center">Replication code: The color and shape of politics</h4>
<p align="center">
    <a href="https://github.com/DamonCharlesRoberts/fancy-doc/commits/main">
    <img src="https://img.shields.io/github/last-commit/DamonCharlesRoberts/fancy-doc.svg?style=flat-square&logo=github&logoColor=white"
         alt="GitHub last commit"></a>
    <a href="https://github.com/DamonCharlesRoberts/fancy-doc/issues">
    <img src="https://img.shields.io/github/issues-raw/DamonCharlesRoberts/fancy-doc.svg?style=flat-square&logo=github&logoColor=white"
         alt="GitHub issues"></a>
    <a href="https://github.com/DamonCharlesRoberts/fancy-doc/pulls">
    <img src="https://img.shields.io/github/issues-pr-raw/DamonCharlesRoberts/fancy-doc.svg?style=flat-square&logo=github&logoColor=white"
         alt="GitHub pull requests"></a>
</p>

---

A Quarto extension to generate a PDF document using the `fancyhdr` `LaTeX` package.


## Installation

To use this template, go to the folder you want to work on your project in and then run the following command in your Terminal:

```
quarto install extension DamonCharlesRoberts/fancy-doc
```

## Using the extension

Once you've installed the extension, you should now be able to access it by including the following in your Quarto file's (`.qmd`) yaml section.

```
format:
  fancy-doc-pdf: default
```

## Example
If you want an example, you can download the [`example.qmd` file here in the Github Repository.](https://github.com/DamonCharlesRoberts/fancy-doc/blob/main/example.qmd)

Then make sure to install the extension:

```
quarto install extension DamonCharlesRoberts/fancy-doc
```

Then you can render the document by running

```
quarto render example.qmd
```

It'll produce [`example.pdf` as seen here in the Github Repository.](https://github.com/DamonCharlesRoberts/fancy-doc/blob/main/example.pdf)

## Maintainers

- [Damon C. Roberts](https://github.com/DamonCharlesRoberts)

## License

Shield: [![CC BY 4.0][cc-by-shield]][cc-by]

This work is licensed under a
[Creative Commons Attribution 4.0 International License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg
