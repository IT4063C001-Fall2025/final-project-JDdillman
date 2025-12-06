# Final-Project-The Rising Impact of Data Breaches in the U.S.
<!-- Edit the title above with your project title -->

## Project Overview

## Self Assessment and Reflection

<!-- Edit the following section with your self assessment and reflection -->

### Self Assessment
<!-- Replace the (...) with your score -->

| Category          | Score    |
| ----------------- | -------- |
| **Setup**         | 8 / 10 |
| **Execution**     | 15 / 20 |
| **Documentation** | 10 / 10 |
| **Presentation**  | 30 / 30 |
| **Total**         | 63 / 70 |

### Reflection
<!-- Edit the following section with your reflection -->

#### What went well?
This project's general structure and analysis workflow were successful. Following the cleaning and merging of the records, the visualizations made it evident which industries were most impacted and how breach trends evolved over time. Additionally, the machine-learning pipeline that used Logistic Regression and TF-IDF performed flawlessly and produced insightful predictions based on breach descriptions. I was successful in creating a comprehensive end-to-end notebook that comprised ML modeling, data cleansing, EDA, visualization, and narrative explanation. The project was considerably easier to handle when a standard procedure was followed.
#### What did not go well?
Finding a trustworthy, free dataset that met the project's needs was the largest obstacle. Numerous breach databases were difficult to acquire, incomplete, or hidden behind paywalls. At first, I also had trouble keeping the notebook organized and ensuring that every step was done in the right order. Combining several data sources presented another challenge because the datasets' formats and column names weren't always consistent. The pipeline had to be cleaned and rewritten, which took more time. In general, development was slowed down throughout the early stages of data collecting and preprocessing.
#### What did you learn?
I discovered that when developing a data-analysis system, clean, organized, and well documented data are crucial. Additionally, I learnt how to use preprocessing pipelines, how TF-IDF text vectorization functions, and how text descriptions can be used to identify different types of breaches using machine learning models. I developed expertise in feature engineering, exploratory data analysis, visualization design, and troubleshooting issues that arise from improper dataset alignment. Beyond the technical abilities, I discovered how to effectively communicate a complete data project using narrative, illustrations, and methodical procedures.
#### What would you do differently next time?
The next time, before beginning any modeling or analysis, I would make sure that all datasets were secure and that they could be combined. Additionally, I would establish a more transparent project structure right away, complete with folders for data, photos, and notebook outputs. Trying more sophisticated machine-learning models and comparing results across several techniques would be another enhancement. Lastly, rather than waiting until the very end, I would make visualizations earlier in the process to help direct the study. 

## Getting Started
### Installing Dependencies

To ensure that you have all the dependencies installed, and that we can have a reproducible environment, we will be using `pipenv` to manage our dependencies. `pipenv` is a tool that allows us to create a virtual environment for our project, and install all the dependencies we need for our project. This ensures that we can have a reproducible environment, and that we can all run the same code.

```bash
pipenv install
```

This sets up a virtual environment for our project, and installs the following dependencies:

- `ipykernel`
- `jupyter`
- `notebook`
- `black`
  Throughout your analysis and development, you will need to install additional packages. You can can install any package you need using `pipenv install <package-name>`. For example, if you need to install `numpy`, you can do so by running:

```bash
pipenv install numpy
```

This will update update the `Pipfile` and `Pipfile.lock` files, and install the package in your virtual environment.

## Helpful Resources:
* [Markdown Syntax Cheatsheet](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
* [Dataset options](https://it4063c.github.io/guides/datasets)