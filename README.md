[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/StAResComp/stfc-solar-summer-school-python/HEAD) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

# Introduction to Python

Python lesson to be taught at STFC Introductory Course in Solar and Solar-Terrestrial Physics at the University of St Andrews, August 2023

Based on the Software Carpentry lesson [Plotting and Programming in Python](http://swcarpentry.github.io/python-novice-gapminder/index.html).

The lesson is composed of a set of [Jupyter Notebooks](https://jupyter.org). You can:
 - Clone this repository (or download a zip archive of the contents) and run the notebooks on your own computer (see below), **or**
 - Run them in [Binder](https://mybinder.org/) using the 'launch binder' button above.

## Starting JupyterLab

You can start the JupyterLab server through the command line or through an application called `Anaconda Navigator`. Anaconda Navigator is included as part of the Anaconda Python distribution.

### macOS - Command Line

To start the JupyterLab server you will need to access the command line through the Terminal.
There are two ways to open Terminal on Mac.

1. In your Applications folder, open Utilities and double-click on Terminal
2. Press <kbd>Command</kbd> + <kbd>spacebar</kbd> to launch Spotlight. Type `Terminal` and then
  double-click the search result or hit <kbd>Enter</kbd>

After you have launched Terminal, type the command to launch the JupyterLab server.

```bash
$ jupyter lab
```

### Windows Users - Command Line

To start the JupyterLab server you will need to access the Anaconda Prompt.

Press <kbd>Windows Logo Key</kbd> and search for `Anaconda Prompt`, click the result or press enter.

After you have launched the Anaconda Prompt, type the command:

```bash
$ jupyter lab
```

### Anaconda Navigator

To start a JupyterLab server from Anaconda Navigator you must first [start Anaconda Navigator (click for detailed instructions on macOS, Windows, and Linux)](https://docs.anaconda.com/free/navigator/getting-started/#navigator-starting-navigator). You can search for Anaconda Navigator via Spotlight on macOS (<kbd>Command</kbd> + <kbd>spacebar</kbd>), the Windows search function (<kbd>Windows Logo Key</kbd>) or opening a terminal shell and executing the `anaconda-navigator` executable from the command line.

After you have launched Anaconda Navigator, click the `Launch` button under JupyterLab. You may need to scroll down to find it.

Here is a screenshot of an Anaconda Navigator page similar to the one that should open on either macOS or Windows.

---

![Anaconda Navigator landing page](http://swcarpentry.github.io/python-novice-gapminder/fig/0_anaconda_navigator_landing_page.png)

---

And here is a screenshot of a JupyterLab landing page that should be similar to the one that opens in your
default web browser after starting the JupyterLab server on either macOS or Windows.

---

![JupyterLab landing page](http://swcarpentry.github.io/python-novice-gapminder/fig/0_jupyterlab_landing_page.png)
