# Predict No-Show for Medical Appointments
In this exercise you will develop an algorithm that predicts if a patient will show up for their upcoming appointment. We don't have this feature in our product, but it is something that realistically could come up during discussions. This exercise should therefore give you a good idea of the kinds of problems you will encounter, should you work with us.

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
The data comes from Kaggle's [datasets](https://www.kaggle.com/joniarroba/noshowappointments). It covers 110.527 medical appointments spread over 62.299 patients.

### The Notebook
We've supplied you with a notebook to get started. You don't have to use it if you don't want to.

### Scripts
A single script is included. This keeps most code away from the Notebook and lets you work in your editor of choice. The notebook uses the autoreload reload extension for Jupyter Notebook to continually reload the `notebook_helpers.py` scripts. 

## Evaluation Criteria
Your deliverable will be a Jupyter Notebook and Pytho scrips. The notebook should be readable for someone who in not already familiar with the exercise. You should explain the goal, introduce the data, and walk through all steps from raw data to algorithm evaluation.

We expect you have an algorithm that predicts if a patient will show up for their upcoming appointment. If you do not make it all the way through due to time constraints you should be able to tell us what you would have done, if you had more time.

If you are unsure about about your approach just go with what you think is best. Then we can discuss it at the interview. The main point of the exercise is to see your work so we have something concrete to discuss. We are interested in the quality of your work as well as how you present and engage in discussions.