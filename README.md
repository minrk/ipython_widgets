# ipywidgets: Interactive HTML Widgets

[![Version](https://img.shields.io/pypi/v/ipywidgets.svg)](https://pypi.python.org/pypi/ipywidgets)
![Build Status](https://img.shields.io/github/workflow/status/jupyter-widgets/ipywidgets/Test/master)
[![Documentation Status](http://readthedocs.org/projects/ipywidgets/badge/?version=stable)](https://ipywidgets.readthedocs.io/)
[![Join the chat at https://gitter.im/ipython/ipywidgets](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/jupyter-widgets/Lobby)
[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/jupyter-widgets/ipywidgets/master?filepath=docs%2Fsource%2Fexamples)

ipywidgets are [interactive HTML widgets](https://github.com/jupyter-widgets/ipywidgets/blob/master/docs/source/examples/Index.ipynb)
for Jupyter notebooks, JupyterLab and the IPython kernel.

Notebooks come alive when interactive widgets are used. Users gain control of
their data and can visualize changes in the data.

Learning becomes an immersive, fun experience. Researchers can easily see
how changing inputs to a model impact the results. We hope you will add
ipywidgets to your notebooks, and we're here to help you get started.

## Core Interactive Widgets

A [demonstration notebook](https://github.com/jupyter-widgets/ipywidgets/blob/master/docs/source/examples/Index.ipynb) provides an overview of the core interactive widgets, including:

- sliders
- progress bars
- text boxes
- toggle buttons and checkboxes
- display areas
- and more

## Jupyter Interactive Widgets as a Framework

Besides the widgets already provided with the library, the framework can be
extended with custom widget libraries.

A template project is available in the form of a cookie cutter [here](https://github.com/jupyter-widgets/widget-ts-cookiecutter).

This project is meant to help custom widget authors get started with the
packaging and the distribution of Jupyter interactive widgets.

It produces a project for a Jupyter interactive widget library following the
current best practices for using interactive widgets. An implementation for a
placeholder "Hello World" widget is provided.

Popular widget libraries such as
[bqplot](https://github.com/bloomberg/bqplot),
[pythreejs](https://github.com/jovyan/pythreejs) and
[ipyleaflet](https://github.com/ellisonbg/ipyleaflet)

follow exactly the same template and directory structure. They can serve as
more advanced examples of usage of the Jupyter widget infrastructure.

For detailed information, please refer to the [ipywidgets documentation](https://ipywidgets.readthedocs.io/en/latest/).

## More advanced examples

Examples of custom widget libraries built upon ipywidgets are

- [bqplot](https://github.com/bloomberg/bqplot) a 2d data visualization library
  enabling custom user interactions.
- [pythreejs](https://github.com/jovyan/pythreejs) a Jupyter - Three.js wrapper,
  bringing Three.js to the notebook.
- [ipyleaflet](https://github.com/ellisonbg/ipyleaflet) a leaflet widget for Jupyter.

## Install

Install the current version of ipywidgets using pip or conda.

- With pip:

```
pip install ipywidgets
jupyter nbextension enable --py --sys-prefix widgetsnbextension  # can be skipped for notebook version 5.3 and above
```

- With conda:

```
conda install -c conda-forge ipywidgets
```

- Add ipywidgets to JupyterLab after installing with pip or conda (note that this requires nodejs to be installed and that the package name is different):


```
jupyter labextension install @jupyter-widgets/jupyterlab-manager
```

See the [Installation](docs/source/user_install.md) section of the documentation for additional details.

### Installing from git

If you want to install ipywidgets from git, **you will need the
[yarn](https://yarnpkg.com/) package manager version 1.2.1 or later**.
Installing from git is more complicated and requires a developer install, see the [developer install](docs/source/dev_install.md) instructions.

To install the latest master version from the root directory of the source
code, run ``dev-install.sh``. To only build the Python package enter ``pip install -e .``.

#### Compatibility

| ipywidgets version  | Required notebook version |
| ------------------- | ------------------------- |
| master              | 4.4                       |
| 5.x                 | 4.2                       |
| 4.1.x               | 4.1                       |
| 4.0.x               | 4.0                       |

[Change log](docs/source/changelog.md)

## Usage

See the [examples](docs/source/examples.md) section of the documentation. The widgets are being used in a variety of ways; some uses can be seen in these notebooks:

- [Demo notebook of interactive widgets](https://github.com/jupyter-widgets/ipywidgets/blob/master/docs/source/examples/Index.ipynb)

## Contributing to ipywidgets

- [Developer information](CONTRIBUTING.md)

## License

We use a shared copyright model that enables all contributors to maintain the
copyright on their contributions.

See the [LICENSE](LICENSE) file in this repository for details.

## Project Jupyter resources

- [Project Jupyter website](https://jupyter.org)
- [Online Demo of Jupyter Notebook at try.jupyter.org](https://try.jupyter.org)
- [Documentation for Project Jupyter](https://jupyter.readthedocs.io/en/latest/index.html) [[PDF](https://media.readthedocs.org/pdf/jupyter/latest/jupyter.pdf)]
- [![Google Group](https://img.shields.io/badge/-Google%20Group-lightgrey.svg)](https://groups.google.com/forum/#!forum/jupyter)
