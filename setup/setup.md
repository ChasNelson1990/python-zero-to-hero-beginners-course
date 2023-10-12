---
header-includes:
  - \hypersetup{colorlinks=true,
    urlcolor=blue,
    linkcolor=blue,
    filecolor=blue,
    citecolor=blue}
---

# Setup

Please install all the below software before attending the course. You will need all this software to take part in the course.

After installation, please complete the pre-course survey (see below).

## Objectives

- To ensure everybody arrives at the course with the right software packages installed

## Where To Find Help

Sometimes installations don't run as smoothly as we would hope. If you get stuck there are a few useful resources online; I suggest the Software Carpentries wiki page [here](https://github.com/carpentries/workshop-template/wiki/Configuration-Problems-and-Solutions).

## A Note on Web Browsers

We will teach using Jupyter Lab, which you interact with via a web browser. For this course you should ensure you have an up-to-date version of Chrome, Safari and Firefox installed.

## Anaconda - Python including Jupyter Lab

As this course is based on programming with Python you need to install Python and Jupyter Lab, which we will use for teaching. For ease, we suggest installing the Anaconda Python distribution.

Anaconda will install, amongst other useful things, Python, Jupyter Lab and a package and environment manager (conda). It will also install useful Python packages including NumPy, SciPy, pandas, matplotlib and seaborn - all of which you will use during this course.

_The most important thing to note is that however you install Python it should be Python version 3.11._

If you choose not to install Anaconda then please make sure you have the following packages(`==<version>`) installed before the course:

- `jupyterlab==3.6`
- `numpy==1.26`
- `scipy==1.11`
- `pandas==2.0`
- `matplotlib==3.7`
- `seaborn==0.12`

### To install Anaconda

- _Windows:_
  1. Download the Python 3.11 Anaconda for Windows installer from [here](https://www.anaconda.com/download#downloads).
  2. Install using the installation defaults.
- _MacOS:_
  1. Download the Python 3.11 Anaconda for macOS installer from [here](https://www.anaconda.com/download#downloads).
  2. Install using the installation defaults.
- _Linux:_
  1. Download the Python 3.11 Anaconda for Linux installer from [here](https://www.anaconda.com/download#downloads).
  2. Open a terminal window and navigate to your Downloads folder (see the Files and Directories page).
  3. Type `bash Anaconda3-` and press [Tab] twice, the full name of the file you downloaded should appear.
  4. Press [Return] and follow the text-only prompts:
  - Use [Spacebar] to scroll through the license, then type `yes` and press [Return] to approve
  - Press [Return] to approve the default location
  - Type `yes` and press [Return] to add Anaconda to your path.

## Pre-course Survey

After installation, if you're attending a face-to-face course, please complete the pre-course survey [here](https://forms.gle/SivqoapmFVWedsnH9).

## Running Jupyter Lab

To run Jupyter Lab, please open the Anaconda Navigator and run an instance of Jupyter Lab. Jupyter Lab will open in your default browser. You can navigate to files from within the Jupyter Lab interface, run Jupyter Notebooks and create your own files.
