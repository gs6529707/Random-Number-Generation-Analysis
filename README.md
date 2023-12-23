**Random Number Generator Analysis**
This repository contains a Python script for generating random alphanumeric strings and analyzing the distribution of the highest digit base in those strings. The code is provided in the Jupyter Notebook file Untitled2.ipynb, which was originally created in Google Colaboratory. The notebook can be accessed here.

**Overview**
The script generates random alphanumeric strings by combining digits (0-9) and uppercase letters (A-Z) in a pseudo-random manner. The highest digit in each string determines the base of the number. The distribution of these bases is then analyzed and visualized using a bar chart.

**Code Explanation**
**1.Mapping Dictionary Creation:**

A mapping dictionary is created to associate each digit (0-9) with itself and each uppercase letter (A-Z) with a corresponding numerical value.
Random Alphanumeric String Generation:

**Random alphanumeric strings are generated by selecting digits or letters based on the mapping dictionary.**
The length of the strings varies, with a minimum length of 2 and a maximum length of 10.
Reverse Mapping Dictionary:

A reverse mapping dictionary is created to map the generated alphanumeric characters back to their numerical values.
Base Frequency Analysis:

The highest digit in each generated string determines the base of the number.
The frequency of each base is recorded in the base_frequency dictionary.
Visualization:

A bar chart is created using Matplotlib to visualize the distribution of bases.
Instructions for Use
To run the code locally or in your preferred environment, follow these steps:

Download the Untitled2.ipynb file.
Open the file using a Jupyter Notebook environment or any compatible platform.
Execute the code cells sequentially to generate random alphanumeric strings and visualize the distribution of bases.
Feel free to experiment with the code and modify parameters to explore different scenarios.

Dependencies
Python 3.x
Matplotlib
