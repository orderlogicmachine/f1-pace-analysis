# F1 Pace Analysis

*By JD D'Annunzio*

Hello! Welcome to my project for the second term of Code Louisville's Data Analysis course.

## Purpose

This project is intended to visualize and analyze data from the 2021 Italian Grand Prix (officially known as the *Formula 1 Heineken Gran Premio d'Italia 2021*) while reading in the style of an article about the event. The race was notable for a contentious crash, some unexpected successes, its overall impact on the 2021 championship (to learn more, view the project!), and a persistent hypothetical question arising from its unusual circumstances. My goal is to make the subject matter approachable for a general audience and interesting enought to guide a reader through to the end, with stylistic inspiration from journalist Jon Bois and [his Dorktown series of videos](https://www.youtube.com/playlist?list=PLUXSZMIiUfFTxGgtC_DSPolFqD7KlcZ17).

## Packages

This project was built using the following resources:
* Anaconda/Python
* Jupyter Notebooks
* fastf1
* pandas
* numpy
* matplotlib
* requests

## Features

I have implemented the following features:

* Read TWO data sets in with an API (or use two different APIs that have data you can combine to answer new questions).
    * API calls in Python cells 3, 6, and 10
* If you’re using text data, get some information from your separate documents and summarize them in a DataFrame. This isn’t literally a join but accomplishes a similar idea. For example, getting the most frequent word distributions from both documents and then summarizing them in a table.
    * Driver selection and loops in Python cells 12 and 13
* Make 3 matplotlib or seaborn (or another plotting library) visualizations to display your data.
    * Charts created in Python cells 5, 9, 12, and 13
* Utilize a virtual environment and include instructions in your README on how the user should set one up
    * See below
* Annotate your code with markdown cells in Jupyter Notebook, write clear code comments, and have a well-written README.md. Tidy up your notebook, and make sure you don’t have any empty cells or incomplete cells that don’t do anything. Make sure it’s all functional before your final github commit.
    * Markdown cells and Python cell comments have rich detail throughout

## Setup

*Note: this project was created on a Mac running macOS 12.6.1. The steps below were developed and verified on a Windows 11 computer. If they do not work for you, please notify the developer.*

#### Requirements
* [Git](https://git-scm.com/downloads)
* [Anaconda](https://www.anaconda.com/)
    * This project was built in and expects Anaconda
    * Other Python implementations may work, but your setup steps may vary slightly
    * A `requirements.txt` file is included for non-Anaconda users

#### Clone the project
* Open Git in your directory of choice
* Clone the project by typing `git clone https://github.com/orderlogicmachine/f1-pace-analysis.git`

#### Create a virtual environment
* Launch the Anaconda Prompt and use `cd` to change to your chosen directory
* Create a virtual environment by typing `conda env create -f environment.yml`
* Activate your virtual environment by typing `conda activate f1-env`
    
#### Run the notebook
* Launch **Jupyter Notebook (f1-env)**
* In the browser window that opens, navigate to `main.ipynb`
* Run the full project by clicking on the fast-forward symbol
