# Diet Optimization Project

## Overview
This project aims to optimize your diet plan based on your weight and target calorie intake. It utilizes linear programming techniques to create a balanced meal plan that meets your nutritional requirements while minimizing calorie intake.

## Dependencies
- [pandas](https://pandas.pydata.org/): A powerful data manipulation library.
- [numpy](https://numpy.org/): A fundamental package for scientific computing with Python.
- [PuLP](https://coin-or.github.io/pulp/): A Linear Programming (LP) modeler written in Python.

## Installation
Install the required dependencies using pip:

```bash
pip install pandas numpy pulp
```

## Usage

- Input Data: The dataset used is [Indian Cuisine based RDA recommendation diet](https://www.kaggle.com/datasets/tarunrm09/indian-cuisine-based-rda-diet-recommendation-data/data). The CSV file should include columns for food items, calories, fats, proteins, and carbohydrates.
- Run the Script: Execute the script provided in the project. It will prompt you to enter your weight (in kilograms) and target daily calorie intake. Additionally, you can select specific days to view the optimized meal plan.
- View Results: The script will generate a customized diet plan for the selected days, showing meal options and quantities in grams. It ensures that your nutritional requirements are met while minimizing calorie intake.

## Optimization 
- Linear Programming: The optimization problem is formulated as a linear program, where the objective is to minimize calorie intake subject to constraints on protein, fat, and carbohydrate consumption.
- Simplex Method: The Simplex algorithm is employed to solve the linear programming problem efficiently.
- Randomization: The script incorporates randomization to diversify meal options and ensure balanced nutrition throughout the week.

