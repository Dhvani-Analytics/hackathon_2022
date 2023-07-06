# Hackathon-2022
Welcome to our Hackathon-2022. Through this hackathon we are trying to select interns have passion to work in computer vision and deep learning. We have internships positions for a couple of projects from Defect Recognition to Multi-Camera Multi object Tracking. You can select either C++/Python to solve these coding assignments. Best of luck everyone  

* Use issues to ask any queries 

* Only make use you use the images given in the dataset rather than using any other public images. That is if a problem has limited dataset that is a constraint and you have to develop a algorithm optimal with respect to the constraint 

1. Write an algorithm that will detect the defect in the images given below. Breakup of the mark is as given below
** Expecting a general algorithm that works for different diameter, transaltions during image acquisiton etc . 

  > Flowchart - 20 marks
  
  > Basic algorithm to find defects - 40 marks
  
  > Localizing the defect - 20
  
  > Classify the defect to flashes and cut marks - 20
  
### Good Image
<img src=good.png width="20%" height="20%">

### Defective Images
1. Flashes

<img src=defect1.png width="20%" height="20%"> <img src=defect4.png width="20%" height="20%">

2. Cuts

<img src=defect2.png width="20%" height="20%"> <img src=defect3.png width="20%" height="20%">

2. Write a program to plot following equation over time. the equation defines a dynamical system in which position of the system changes with time . you have to plot the positions over time. Think of this as a Bee moving in 3d space. you need to plot the path taken by the Bee. 

Assume $x,y,z$ are points in 3d space in which $x_{0} = 0, y_{0} = 1, z_{0} = 1.05$ and $a = 10,b = 28,c = 2.667$ are the parameters and $\dot{x} = \frac{dx}{dt}$, similar for $y$ and $z$.The equations are $\dot{x}=a*(y - b)$, and $\dot{y} = b*x - y - x*z$ and $\dot{z} = x*y - c*z$


Total : 100 marks

3. The objective is to predict the location and type of vehicle found in the scene using the images provided. The images have annotations in xml format, and the task is to create an Object Detector and Classifier.Eg: Cars, Bus, Motorbikes etc. Select 3 or 4 classes from the provided dataset and build the training module. Each Image may or may not have the classes to identify. You can find description along with the dataset.
> Dataset for : https://www.kaggle.com/datasets/pratikbarua/vehicle-detection-dataset
 
> Visualize the object data distribution as graph or in any meaningful representation. Eg. number of objects in each classes, Area, width and height etc.- 10 marks

> Flowchart/Blockdiagram - 25 marks

> Create a deep learning model to identify the objects and classify - 40 (Percentile. The person who submitting the highest accuracy will get 40 and others mark will be normalised) 

> Evaluation metrics and plots - 25

## Time Line
- Late submissions will not be considered for evaluation
- The submission consists of a document which describes the flowcharts and explain why you make use of the particular algorithm to solve the problem along with the results and discussions on the accuracy (if your model is not working on some data, show the same and explain why it is not working as per your understanding)
- The code has to be properly commented and should follow PEP8 rules. The code should be written in modular format. For example, data preparation, model training and model inference and result visualisations 

## Email Your github repo to : hr@dhvaniai.com 
## Last Date for Submission : September - 8, 2022
