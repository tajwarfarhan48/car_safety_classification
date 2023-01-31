# Car Safety Classification

A machine learning model made using sklearn that predicts the acceptability of cars based on a multitude of input factors. To test the model in your device, run the following code in your terminal (**Important: installing Jupyter Notebook in your machine may be required to properly run the files in the project**)

```
git clone https://github.com/tajwarfarhan48/car_safety_classification.git
cd car_safety_classification
```

## Model Description

The model takes in the following attributes:
- **buying -** The relative buying price of the car. Classified as:
  - v-high 
  - high 
  - med
  - low
- **maint -** The relative price of maintaining the car. Clasified as:
    - v-high 
    - high
    - med
    - low
- **doors -** Number of doors in the car. Classified as: 
  - 2
  - 3
  - 4
  - 5-more
- **persons -** The capacity of the car in terms of number of persons. Classified as:
  - 2
  - 4
  - more
- **lug_boot -** The relative size of the luggage boot. Classified as:
  - small
  - med
  - big
- **safety -** The estimated safety of the car. Classified as:
  - low
  - med
  - high

The output of the model is the acceptability of the car. There are 4 possible classifications:
- unacc (Unacceptable)
- acc (Acceptable)
- good (Good)
- v-good (Very Good)

## Approach

The program compares two different approaches for this classification problem: K-Nearest-Neighbors and Decision Tree classification. Afterwards, the program tries to optimize the Decision Tree classifier used to examine the cars.
