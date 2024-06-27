# Mercedes-Benz Test Time Reduction

## Description
This project aims to reduce the time that Mercedes-Benz cars spend on the test bench by predicting the time it takes to pass testing using various machine learning techniques.

## Problem Statement
Since the first automobile, the Benz Patent Motor Car in 1886, Mercedes-Benz has stood for important automotive innovations. These include the passenger safety cell with a crumple zone, the airbag, and intelligent assistance systems. Mercedes-Benz applies for nearly 2000 patents per year, making the brand the European leader among premium carmakers. Mercedes-Benz is the leader in the premium car industry. With a huge selection of features and options, customers can choose the customized Mercedes-Benz of their dreams.

To ensure the safety and reliability of every unique car configuration before they hit the road, the company’s engineers have developed a robust testing system. As one of the world’s biggest manufacturers of premium cars, safety and efficiency are paramount on Mercedes-Benz’s production lines. However, optimizing the speed of their testing system for many possible feature combinations is complex and time-consuming without a powerful algorithmic approach.

The goal is to reduce the time that cars spend on the test bench, resulting in lower carbon dioxide emissions without reducing Mercedes-Benz’s standards.

## Actions Performed
1. Remove columns with zero variance.
2. Check for null and unique values in test and train sets.
3. Apply label encoding.
4. Perform dimensionality reduction using PCA.
5. Predict test set values using XGBoost.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Installation
Follow these steps to set up the project environment:

```bash
git clone https://github.com/NgumbiBlaise/Mercedes_Test_Time_Reduction.git
cd Mercedes_Test_Time_Reduction
pip install -r requirements.txt
