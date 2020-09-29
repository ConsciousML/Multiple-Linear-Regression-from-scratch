# Multi-Variable-Linear-Regression-on-CarDekho

## Objective
The goal of this project is to explain how linear regression works on multiple variables.
The solution will be implemented from scratch using PyTorch.

## Blog Post
The experiment can be found in this [post](https://consciousml.github.io/blog/linear-regression/car-price/pca/pytorch/from-scratch/2020/09/10/Multivariate-Linear-Regression.html).

## Dataset
The CarDekho dataset contains information about used cars listed on the website of the same name.
This dataset has 301 unique entities with the following features:
- car name
- year of release
- selling price
- present price
- kilometers driven
- fuel: such as petrol or diesel
- transmission: such as manual or automatic
- owner: how many times the car changed owner

## Setup
In order to install the conda environment needed to run the notebook, run the following line:
```console
conda env create --file requirements.yml
conda activate torch
```
