
# German Linguistics in Heidelberg: Citations
Welcome to the German Linguistics in Heidelberg Citations project! 📚 This endeavor aims to create a citation style tailored to the guidelines outlined in the [Vademecum](https://www.uni-heidelberg.de/md/neuphil/gs/abteilungen/linguistik/vademecum_germanistische_linguistik_final.pdf) for German Linguistics at Heidelberg University.

## Project Status
🚧 Work in Progress: Please note that this project is an ongoing effort, and no elements are considered final at this stage.

## Zotero Citation Style
The current focus is on a citation style designed for Zotero. While it is functional for standard entry types, be aware that there might be bugs, especially for more uncommon document types.
To use the style in Zotero, simply open the `universitat-heidelberg-germanistische-linguistik.csl` file with Zotero by right-clicking.

The style should then be installed automatically in Zotero.

## LaTeX Citation Style
The included LaTeX citation style is a modified version of the `authoryear` style. It is designed to be used with the `biblatex` package.
In order to use the style, follow these steps:

1. Add the `biblatex.cfg` file to your project directory.
2. Add the following lines to your LaTeX document:
    ```latex
    \usepackage[backend=biber, style=authoryear]{biblatex}
    \addbibresource{your_bibliography.bib}
    ```

## LaTeX Template
The `template/` folder contains a ready-to-use LaTeX scaffold for an empirical Hausarbeit (title page, structured sections, numbered example environment). Copy its contents into a new project, **also copy `biblatex.cfg` from this repo's root** into the project directory (it is required for the citation style), fill in the title-page fields in `main.tex`, and compile with the `biber` backend.

## How to Contribute
🤝 I welcome all contributions! Feel free to fork the repository, make your improvements, and submit a pull request.
I am also happy about any feedback or suggestions you might have. Please feel free to open an issue or contact me directly via my [institute email](bruno.brocai@gs.uni-heidelberg.de).
