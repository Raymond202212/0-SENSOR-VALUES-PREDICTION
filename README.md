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

To have a local copy of this lab, you can use either google colab or jupyterlab to execute the `Code.ipynb` file. You shall execute the code block in order.<br>
Please also download `xTrain.py`, `yTrain.py`, `xTest.py`, and `yTest.py` in the same directory as the `Code.ipynb` file.
You can finally output the corresponding prediction as `yPred.py` file by executing the code.

## Sources Used

All the reference are marked as the comment within the corresponding code block.

### Other References
[1] Zhihong Wang and Buyang Cao, “Prediction of Office Building Rental upon Spatiotemporal Data,” 2019 2nd International Conference on Data Science and Information Technology (DSIT), Seoul, Republic of Korea, 2019, pp. 168–174, doi: 10.1145/3352411.3352438.

[2] Naser Shanti, Akram Assi, Hamza Shakhshir and Adnan Salman, “Machine Learning-Powered Mobile App for Predicting Used Car Prices,” 2022 3rd International
Conference on Big-data Service and Intelligent Computation (BDSIC), Xiamen, China, 2022, pp. 52–60, doi: 10.1145/3502300.3502307.

[3] M. C. Roziqin, A. Basuki and T. Harsono, "A comparison of Montecarlo linear and dynamic polynomial regression in predicting dengue fever case," 2016 International Conference on Knowledge Creation and Intelligent Computing (KCIC), Manado, Indonesia, 2016, pp. 213-218, doi: 10.1109/KCIC.2016.7883649.

[4] Y. Bowen and C. Buyang, “Research on Ensemble Learning-based Housing Price Prediction Model,” 2018 Big Geospatial Data and Data Science, 2018, pp. 1-8, doi: 10.23977/bgdds.2018.11001.

## Acknowledgments

* The project is under the instruction of Thomas Trappensberg, who taught us Machine Learning Fundamental (CSCI6505) during January 2023 and April 2023.
* This final project ranked 2/28 classwide (test MSE = 352, despite interval is needed, see `Project Results.docx`). And the project scored 99/100 in that semester.
* Original Data including `xTrain.py`, `yTrain.py`, and `xTest.py`.
* `yTest.py` was reveiled & published by instructor after the project. Therefore, we conducted model training & fine-tuning , and outputting `yPred.py` based on three original data files above.





