# S1: Applied Data Science - Coursework

This repository is for the submission of the M1 Applied Data Science Module as part of the MPhil in Data Intensive Science at the University of Cambridge. The task was to provide solutions to the problems set out in the coursework instructions `DIS_MPhil_M1_Coursework.pdf`.

## Installation
To install the required packages into a new conda environment, run the following command in the root directory:
```
$ conda env create -f environment.yml
```
To activate the environment, run the following command in the root directory:
```
$ conda activate cambridge
```

## Usage
It was decided to use `.ipynb` files for the coursework, as this allows for the inclusion of code, plots, and text in a single document. To run the code from the command line, run the following command in the root directory:
```
$ jupyter execute src/Qx.ipynb
```
Where `x` is the question number (1-5), so to run the code for question 1, run the following command:
```
$ jupyter execute src/Q1.ipynb
```
Alternatively, the code can be run in the browser with the following command:
```
$ jupyter notebook src/Qx.ipynb
```

## Expected Runtime
The code was developed on a 2019 MacBook Pro with a 2.4 GHz 8-Core Intel Core i9 processor and 32 GB of RAM. The runtime for each question is was found to be as follows:
- **Q1:** 12 seconds
- **Q2:** 11 seconds (around 10 minutes with empty `Data/pickles` folder)
- **Q3:** 1 minute 45 seconds
- **Q4:** 3 minutes 20 seconds
- **Q5:** 1 minute 5 seconds

## Use of AI
GitHub copilot was used in auto-completion for basic functionality code. The use of AI was not used for idea generation, proofreading, optimisation, or any other task.

## Support
For any questions or issues, please contact me at [dp702@cam.ac.uk](mailto:dp702@cam.ac.uk).