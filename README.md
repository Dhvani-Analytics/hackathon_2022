# Hackathon-2022
1. Write an algorithm that will detect the defect in the images given below. Breakup of the mark is as given below
  1. Flowchart - 20 marks
  2. Basic algorithm to find defects - 40 marks
  3. Localizing the defect - 20
  4. Classify the defect to flashes and cut marks - 20
### Good Image
<img src=good.png width="20%" height="20%">

### Defective Images
1. Flashes

<img src=defect1.png width="20%" height="20%"> <img src=defect4.png width="20%" height="20%">

2. Cuts

<img src=defect2.png width="20%" height="20%"> <img src=defect3.png width="20%" height="20%">

2. Write a program to plot following equation over time. Assume $x,y,z$ are points in 3d space in which $x_{0} = 0, y_{0} = 1, z_{0} = 1.05 $and $a = 10,b = 28,c = 2.667$ are the parameters and $\dot{x} = \frac{dx}{dt}$, similar for $y$ and $z$

$ \dot{x} = a*(y - b) $ 

$ \dot{y} = b*x - y - x*z $

$ \dot{z} = x*y - c*z $ 





## Problem Definition
The objective is to predict the location and type of vehicle found in the scene using the images provided. The images have annotations in xml format, and the task is to create an Object Detector and Classifier.Eg: Cars, Bus, Motorbikes etc. Select 3 or 4 classes from the provided dataset and build the training module. Each Image may or may not have the classes to identify. You can find description along with the dataset

## Objectives:
- Data Analysis
  - Visualize the object data distribution as graph or in any meaningful representation. Eg. number of objects in each classes, Area, width and height etc..
- The entire deep learning modules has has to be written in Pytorch 

- Deep Learning:
  - Create an algorithm to identify the objects and classify.
  - Proper documentation and report the evaluation metrices

## Time Line
- The last date of submission is before 
- Late submissions will not be considered for evaluation
- The submission consists of a document which describes the flowcharts and explain why you make use of the particular algorithm to solve the problem along with the results and discussions on the accuracy (if your model is not working on some data, show the same and explain why it is not working as per your understanding)
- The code has to be properly commented and should follow PEP8 rules. The code should be written in modular format. For example, data preparation, model training and model inference and result visualisations 

> Dataset Link: https://www.kaggle.com/datasets/pratikbarua/vehicle-detection-dataset

## Evaluation
The evaluation will be on following parameters 
- Model Accuracy - 40%
- Code Style - 30%
- Documentation - 30%

## Email Your github repo to : hr@dhvaniai.com 
## Last Date for Submission : 
