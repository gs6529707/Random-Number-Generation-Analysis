<h1>#Random Number Generator Analysis</h1><br>
This repository contains a Python script for generating random alphanumeric strings and analyzing the distribution of the highest digit base in those strings. The code is provided in the Jupyter Notebook file Untitled2.ipynb, which was originally created in Google Colaboratory. The notebook can be accessed here.

<h2>#Overview</h2><br>
The script generates random alphanumeric strings by combining digits (0-9) and uppercase letters (A-Z) in a pseudo-random manner. The highest digit in each string determines the base of the number. The distribution of these bases is then analyzed and visualized using a bar chart.

<h2>#Code Explanation</h2><br>
**1.Mapping Dictionary Creation**<br>

A mapping dictionary is created to associate each digit (0-9) with itself and each uppercase letter (A-Z) with a corresponding numerical value.

**2.Random Alphanumeric String Generation**<br>

Random alphanumeric strings are generated by selecting digits or letters based on the mapping dictionary.
The length of the strings varies, with a minimum length of 2 and a maximum length of 10.

**3.Reverse Mapping Dictionary**<br>

A reverse mapping dictionary is created to map the generated alphanumeric characters back to their numerical values.

**4.Base Frequency Analysis**<br>

The highest digit in each generated string determines the base of the number.
The frequency of each base is recorded in the base_frequency dictionary.

**5.Visualization**<br>

A bar chart is created using Matplotlib to visualize the distribution of bases.<br>

<h2>#Instructions for Use</h2><br>
To run the code locally or in your preferred environment, follow these steps:

1.Download the Untitled2.ipynb file.<br>
2.Open the file using a Jupyter Notebook environment or any compatible platform.<br>
3.Execute the code cells sequentially to generate random alphanumeric strings and visualize the distribution of bases.<br>

**-Feel free to experiment with the code and modify parameters to explore different scenarios.-**<br>

<h2>Dependencies</h2><br>
1.Python 3.x<br>
2.Matplotlib<br>
