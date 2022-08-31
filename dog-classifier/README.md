# Project Brief: Image Classification for a City Dog Show

## Project Goal

* Improving your programming skills using Python.

In this project, you will use a created image classifier to identify dog breeds. We ask you to focus on Python and not on the actual classifier.


## Principal Objectives

* Correctly identify which pet images are of dogs (even if the breed is misclassified) and which pet images aren't of dogs.
* Correctly classify the breed of dog, for the images that are of dogs.
* Determine which CNN model architecture (ResNet, AlexNet, or VGG), "best" achieve objectives 1 and 2.
* Consider the time resources required to best achieve objectives 1 and 2, and determine if an alternative solution would have given a "good enough" result, given the amount of time each of the algorithms takes to run.

## Answer to 3 and 4 Principal Objective

For Principal Objective 3 based on results stats gathered from this project, the **best** CNN model architecture to achieve Principal Objective 1 and 2 is **VGG**.

For Principal Objective 4 based on results stats gathered from this project, the **good enough** and sustainable CNN model architecture to achieve Principal Objective 1 and 2 is **ResNet**. Combining stats from *pet-images* data and *uploaded-images* data, ResNet give more conservative result than AlexNet and VGG.

## *pet-images* Result Table

| Number of Total Images     | 40 |
|----------------------------|----|
| Number of Dog Images       | 30 |
| Number of Not-a-Dog Images | 10 |

| CNN Model Architectures | % Not-a-Dog Correct | % Dog Correct | % Breed Correct | % Match Labels | Time (s) |
|-------------------------|---------------------|---------------|-----------------|----------------|----------|
| ResNet                  | 90                  | **100**       | 90              | 82.5           | 6        |
| AlexNet                 | **100**             | **100**       | 80              | 75             | **3**    |
| VGG                     | **100**             | **100**       | **93.3**        | **87.5**       | 39       |

## *upladed-images* Result Table

| Number of Total Images     | 4 |
|----------------------------|----|
| Number of Dog Images       | 2 |
| Number of Not-a-Dog Images | 2 |

| CNN Model Architectures | % Not-a-Dog Correct | % Dog Correct | % Breed Correct | % Match Labels | Time (s) |
|-------------------------|---------------------|---------------|-----------------|----------------|----------|
| ResNet                  | **100**             | **100**       | **100**         | 50             | **0**    |
| AlexNet                 | **100**             | **100**       | **100**         | 50             | **0**    |
| VGG                     | **100**             | **100**       | 0               | 0              | 3        |