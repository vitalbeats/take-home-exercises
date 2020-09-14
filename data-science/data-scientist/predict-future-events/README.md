# Predict Future Medical Events
In this exercise you will develop an algorithm that predict future medical events. While the data is different from what we have at Vital Beats, the overall idea is the same. This exercise should therefore give you a good idea of the kinds of problems you will encounter, should you work with us.

## Getting Started

### The Environment
First, make sure you have already install Poetry. Then you can install the Python environment by running:
```
    poetry install
```

We've gone ahead and added some of the most commonly used packages to the environment: pandas, matplotlib, jupyter. If you need other packages you can add them using Poetry:

```
    poetry add <package-name>
```

To launch Jupyter Notebook run

```
    poetry run jupyter-notebook
```

This makes sure that the command `jupyter-notebook` is run in the proper context.

### The Data
The data comes from Kaggle's [datasets](https://www.kaggle.com/tango911/future-medical-event). This dataset contains historical patient information from Jan 2011 to Dec 2013. It covers 766.787 events spread across 3000 patients. 

### The Notebook
We've supplied you with a notebook to get started. The notebook comes with a rough outline of what you are expected to do. It loads the data and pass it to a series of empty functions defined in the `notebook_helpers.py` script. You don't have to use it if you don't want to, but we expect you to deliver your results as a notebook.

### The Script
We've also supplied you with a Python script that includes some empty functions. The notebook uses the autoreload extension for Jupyter Notebook to continually reload the `notebook_helpers.py` scripts. This keeps most code away from the Notebook and lets you work in your editor of choice.

## Evaluation Criteria
Your deliverable will be a Jupyter Notebook and Python scrips. The notebook should be readable for someone who in not already familiar with the exercise. You should explain the goal, introduce the data, and walk through all steps from raw data to algorithm evaluation.

We expect you have an algorithm that predicts future events and that you are able to tell us how well it works. If you do not make it all the way through due to time constraints you should be able to tell us what you would have done, if you had more time.

If you are unsure about about your approach just go with what you think is best. Then we can discuss it at the interview. The main point of the exercise is to see your work so we have something concrete to discuss. We are interested in the quality of your work as well as how you present and engage in discussions.