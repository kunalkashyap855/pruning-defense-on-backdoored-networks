# pruning-defense-on-backdoored-networks

NYU ECE-GY 9163 Machine Learning for Cyber Security Lab 2

## How to Run from Scratch

1. Open the Python notebook in Colab and run the first 3 cells, until the CSAW-HackML-2020 GitHub repository is cloned.
2. Then before moving on to the next cell, download the datasets from [Lab 3 Datasets Drive](https://drive.google.com/drive/folders/1Rs68uH8Xqa4j6UxG53wzD0uyI8347dSq). Upload them to your runtime and place them inside `CSAW-HackML-2020/lab3/data/`.
3. Run rest of the cells in their order.

## How to Create Repaired Net G using B_prime Models

Instead of running the whole Python Notebook fromscratch, you can also directly use the B_prime models provided in this repository and create the Repaired BadNet G for evaluation. To do that, load all three or any one of the B_prime models to the Colab runtime, then just run all the cells from cell 13 onwards where we have defined the Repaired BadNet G.

### Extra Info

- The clean test accuracy and attack success rate for both, B_prime and G models is similar, so to evaluate the repaired models, you can simply use the B_prime models given in this repository to evaluate their performance, wihtout converting them into G models.
- This is running code with no errors, but if you find any problems, please let me know!

## Submitted by:

Kunal Kashyap (kk4564)