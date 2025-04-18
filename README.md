# Human Activity Recognition Project

This project was developed as part of the Coursera course **Practical Machine Learning**. The goal was to predict the manner in which participants performed a barbell lift exercise, based on data collected from wearable devices.

## Project Objective

Using data from accelerometers on the belt, forearm, arm, and dumbbell of 6 participants, the task was to predict the variable `classe` which represents the quality of the exercise performed.

## Data Sources

- Training data: `pml-training.csv`
- Test data: `pml-testing.csv`
- Source: [Weight Lifting Exercise Dataset](http://groupware.les.inf.puc-rio.br/har)

## Contents

- `report.Rmd`: R Markdown file with the full analysis and modeling
- `report.html`: Compiled HTML report
- `prediction.txt`: File with final predictions (one per line)

## How to Reproduce

1. Download the training and test datasets
2. Open `report.Rmd` in RStudio
3. Knit the file to HTML to generate `report.html`
4. Run the script to regenerate the prediction file
