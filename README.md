# Python for Beginners Course

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ChasNelson1990/python-zero-to-hero-beginners-course/main)

This repository contains materials for a beginners python course (delivery dates/information abotu self-taught options below).

## Aim

The overall aim of this course it to:

1. introduce the basic concepts of programming in Python within the comfort of the Jupyter framework
2. showcase some of the advanced functionality available in Python by demonstrating (and providing take-home resources) numpy, scipy, matplotlib, seaborn and pandas code

## Philosophy

Our general philosophy for this course is

1. teach in small chunks starting by introducing theory, demonstrating an example, working through a simple case and then setting an exercise. Each exercise is then gone through as a group.
2. teach through errors, error messages and documentation - so that trainees can debug their own codes after they leave the course
3. create a safe environment for asking any and all questions.

## Contributors

- [Chas Nelson](https://github.com/ChasNelson1990)
- [Mikolaj Kundegorski](https://github.com/mixmixmix)

## Using Binder to Explore the Course

If you wish to quickly explore the course, you could use Binder (by clicking the button above). However, this won’t save your progress as you go along so we suggest installing locally as described below.

## Self-taught On-line Version (12+ hours)

We have designed this course in such a way that it should be easy to follow and work through on your own. Each notebook stands alone and should provide you with all the information needed to complete the tasks (green boxes) and exercises (orange boxes).

In order to aid working through the notebooks we have provided short videos for all tasks and exercises. These videos provide complete answers for every task and should be viewed after attempting each task or exercise.

In order to work through the notebooks please follow the instructions in [`setup.pdf`](https://github.com/ChasNelson1990/python-zero-to-hero-beginners-course/blob/main/setup/setup.pdf) for installing Python and Jupyter Lab on your computer, dowload this repository as a `.zip` file (using the green button at the top of the landing page), unzip the files and navigate to them from within Jupyter Lab.

We suggest you work through each notebook in turn, attempting at least the tasks on your first run-through. You can then use the exercises to revisit and revise topics when you go through the notebooks again in the future. As with all languages, practice makes perfect.

## In Person Course Delivery Dates (1 day course)

- **2019-04-05**: Programming for Biologists, Royal Society of Biology, Charles Darwin House, London, UK
- **2019-10-18**: Programming for Biologists, Royal Society of Biology, 1 Naoroji Street, London, UK

## Other Information

These materials also form the prerequisite knowledge for following course:

- [Python for Data](https://github.com/ChasNelson1990/python-for-data-course)
- **2019-12-09**: IAFIG-RMS: Bioimage analysis with Python, Craik-Marshall Building, Cambridge, UK

## Developer Information

When taught in person we recommend getting participants to install Anaconda (as per [`setup.pdf`](https://github.com/ChasNelson1990/python-zero-to-hero-beginners-course/blob/main/setup/setup.pdf)); all the dependencies are pre-installed this way.
However, for developing (and presenting) the course we use pipenv to ensure that we're using the same version of packages as Anaconda but without having to pollute our own computers with a tools that we find great for using to teach but not great for real life.

To install this repository into a clean system (assuming you have pipenv installed):

```bash
pipenv install --dev
```

To run Jupyter Lab (for demoing):

```bash
pipenv run jupyter lab
```

To run Jupyter Notebook (for presenting slides):

```bash
pipenv run jupyter notebook
```
