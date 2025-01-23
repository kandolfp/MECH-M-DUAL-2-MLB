# MECH-M-DUAL-2-MLB - Maschinelles Lernen in der industriellen Bildverarbeitung

Course material for a ~3 * 15 hours (5 ECTS) course on basic concepts for Machine Learning in Industrial Image Processing. All the topics are presented with the Python implementation included.  

# Citing this project

Will be added once the notes are more mature. 

# Development

We use [Quarto](https://quarto.org/) to generate the lecture material.
Where we are creating a book, see [docs](https://quarto.org/docs/books/) for the structure. 
In short, each part has its own folder where you find the `qmd` files and everything is managed via `_quarto.yml`.
In order to make the use easy the entire project is managed with [pdm](https://pdm-project.org/) so to start the preview run

```bash
pdm sync
pdm quarto preview
```

The project is also compatible with the VSCode extension of Quarto, just make sure the the Python environment in `./.venv` is used. 

# Publishing
After pushing the published website will automatically be built and deployed at [kandolfp.github.io/MECH-M-DUAL-2-MLB/](https://kandolfp.github.io/MECH-M-DUAL-2-MLB/).
Due to the dynamic nature of the material this might take a couple of minutes.

You can also create a pdf by calling 
```
 pdm run quarto render --to pdf
```

or the html version
```
 pdm run quarto render --to html
```

You can also find a pdf in the [releases](https://github.com/kandolfp/MECH-M-DUAL-1-DBM/releases)