# 

[Project Started] 2023-03-10

[Project Finished] 2023-04-02


**This is the project that I have collaborated with Ravishankar Subramani Iyer, who provided the list of the candidate models & assisted the model tuning.**

**The project is under the instruction of Thomas Trappensberg, who taught us Machine Learning Fundamental (CSCI6505) during January 2023 and April 2023.**

**This final project ranked 2/28 classwide (test MSE = 352, despite interval is needed, see *Project Results.docx*). And the project scored 99/100 in that semester.**

**Abstract**: 

**Original Data: *xTrain.py*, *yTrain.py*, *xTest.py***

***yTest.py* was reveiled & published by instructor after the project. Therefore, we conducted model training & fine-tuning , and outputting *yPred.py* based on three original data files above.**

**References**

[1] Zhihong Wang and Buyang Cao, “Prediction of Office Building Rental upon Spatiotemporal Data,” 2019 2nd International Conference on Data Science and Information Technology (DSIT), Seoul, Republic of Korea, 2019, pp. 168–174, doi: 10.1145/3352411.3352438.

[2] Naser Shanti, Akram Assi, Hamza Shakhshir and Adnan Salman, “Machine Learning-Powered Mobile App for Predicting Used Car Prices,” 2022 3rd International
Conference on Big-data Service and Intelligent Computation (BDSIC), Xiamen, China, 2022, pp. 52–60, doi: 10.1145/3502300.3502307.

[3] M. C. Roziqin, A. Basuki and T. Harsono, "A comparison of Montecarlo linear and dynamic polynomial regression in predicting dengue fever case," 2016 International Conference on Knowledge Creation and Intelligent Computing (KCIC), Manado, Indonesia, 2016, pp. 213-218, doi: 10.1109/KCIC.2016.7883649.

[4] Y. Bowen and C. Buyang, “Research on Ensemble Learning-based Housing Price Prediction Model,” 2018 Big Geospatial Data and Data Science, 2018, pp. 1-8, doi: 10.23977/bgdds.2018.11001.

<!--- The following README.md sample file was adapted from https://gist.github.com/PurpleBooth/109311bb0361f32d87a2#file-readme-template-md by Gabriella Mosquera for academic use ---> 
<!--- You may delete any comments in this sample README.md file. If needing to use as a .txt file then simply delete all comments, edit as needed, and save as a README.txt file --->

# 0. Sensor Values Prediction

**[Abstract]** Regression refers to the technique of modelling data which is continuous (measurable) in nature. To find the best regression model to predict sensor value, we explored multiple regression models from StackOverflow and research literature to make quantitative predictions of the failure scores of 103 sensors. From the 21 different regression models, GBDT performed the best in terms of Root Mean Squared Error (RMSE) (17.94 ± 2.62) and R2 scores (0.17 ± 0.22). Subsequently, we optimised the GBDT model to predict the failure scores of the 103 sensor values of the subsequent year. This project not only considers almost every possibility of regression prediction use cases but also ensures the coverage of the possible appropriate regression model to perform the best result.

* *Date Created*: 10 March 2023
* *Last Modification Date*: 02 April 2023

## Authors

**[Optional]** If what is being submitted is an individual Lab or Assignment, you may simply include your name and email address. Otherwise list the members of your group.

* [Raymond Liu](Raymond.Liu@dal.ca) - *(Data Exploration, Model Tuning, Model Testing)*
* [Ravishankar Subramani Iyer](rv505461@dal.ca) - *(Model Selection, Model Tuning)*

## Getting Started

**[Optional]** If needing to provide the marker with a copy of the project that should run on their local machine for development, testing and/or marking purposes. Please include the following sections.

See deployment for notes on how to deploy the project on a live system.

### Prerequisites

To have a local copy of this lab / assingnment / project up and running on your local machine, you will first need to install the following software / libraries / plug-ins

```
Give examples or provide a list of the required software / libraries / plug-ins

```

See the following section for detailed step-by-step instructions on how to install this software / libraries / plug-ins

### Installing

A step by step series of examples that tell you how to get a development env running

Say what the step will be, assume the marker just acquired a computer

```
Give the example
```

And repeat

```
until finished
```

End with an example of getting some data out of the system or using it for a little demo. You may also include a quick example of what the marker should see if the installation of all required software / libraries / plug-ins was successful.


## Running the tests

If needing to run automated tests, then explain how to run the automated tests for this system. If this section is not needed, ** you may delete **.

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```


## Deployment

Add additional notes about how to deploy this on a live system

## Built With

<!--- Provide a list of the frameworks used to build this application, your list should include the name of the framework used, the url where the framework is available for download and what the framework was used for, see the example below --->

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
* [Maven](https://maven.apache.org/) - Dependency Management
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds

## Sources Used

If in completing your lab / assignment / project you used any interpretation of someone else's code, then provide a list of where the code was implement, how it was implemented, why it was implemented, and how it was modified. See the sections below for more details.

### File Name

*Lines ## - ##*

```
Copy and paste your code on lines mentioned 

```

The code above was created by adapting the code in [NAME](link) as shown below: 

```
Copy and paste the snippet of code you are referencing

```

- <!---How---> The code in [NAME](link) was implemented by...
- <!---Why---> [NAME](link)'s Code was used because...
- <!---How---> [NAME](link)'s Code was modified by...

*Repeat as needed*

### File Name

*Lines ## - ##*

```
Copy and paste your code on lines mentioned 

```

The code above was created by adapting the code in [NAME](link) as shown below: 

```
Copy and paste the snippet of code you are referencing

```

- <!---How---> The code in [NAME](link) was implemented by...
- <!---Why---> [NAME](link)'s Code was used because...
- <!---How---> [NAME](link)'s Code was modified by...

*Repeat as needed*

## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
* etc





