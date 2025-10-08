[![bckrlab.org](https://img.shields.io/badge/bckrlab.org-blue?style=flat)](https://bckrlab.org/course-ml-with-graphs/)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/bckrlab/course-ml-with-graphs/HEAD)

# Machine Learning with Graphs

> Course Materials

## Usage

This book was made using [Jupyter Book version 2](https://next.jupyterbook.org/)!

Currently, Jupyter Book v2 is still in beta. You can install it via pip:

```sh
pip install jupyter-book==2.0.b3
```

### Building the book

If you'd like to develop and/or build the DSC Tutorials book, you should:

1. Clone this repository
2. Run `pip install -r requirements.txt` (it is recommended you do this within a virtual environment)
3. (Optional) Edit the books source files located in the `content/` directory
4. Run `jupyter book clean --all` to remove any existing builds
5. Run `jupyter book start` (Using Jupyter Boook v2)

A fully-rendered HTML version of the book will be built in `_build/html/`.

### Repository Overview

```sh
# main configuration file
# add new files to toc section
myst.yml

# add python requirements for binderhub here
requirements.txt

# actual content of the book (markdown files, notebooks, etc.)
content/
```

## GitHub Pages

Jupyter Book supports generating configuration files for deploying the website via GitHub pages:

```sh
jupyter book init --gh-pages
```


## Contributors

We welcome and recognize all contributions. You can see a list of current contributors in the [contributors tab](https://github.com/chillerb/dsc_tutorials/graphs/contributors).

## Credits

This project is created using the excellent open source [Jupyter Book project](https://jupyterbook.org/).
