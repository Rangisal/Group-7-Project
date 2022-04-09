# Group-7-Project

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## **Project Overview**

As part of the final project of the Data Analytics Bootcamp at the University of Toronto, students have been assigned to groups in order to confirm their knowledge of the underlying concepts of data analytics and data science tools including their proficiency in Python, SQL, Pandas, and their ability to extract, transform, and load (ETL) data, and finally perform an analysis on the data to derive conclusions and provide a recommendation to potential employers. 

Group 7, has selected an open-source dataset from Kaggle that that contains data pertaining to a number of indicators of heart disease. The group will use the heart disease dataset to determine which indicators are factors for heart disease and further go on to test a machine learning model that can accurately predict which factors lead to heart disease. As part of the project, the heart dataset will be stored in a SQL database using PgAdmin, cleaned used the ETL process through Pandas, and tested through a machine learning model that will be developed by the group. Due to the complexity of this task, we will design and train a deep learning neural network that will evaluate all types of input data and produce a clear decision-making result, that will allow us to draw conclusions from our data.


## Goals:

Determine which factors are key indicators of heart disease based on the data provided.
Create a SQL database to store and load the dataset.
Clean the data to provide to allow for testing using machine learning.
Select and develop a machine learning model for testing.
Using the machine learning model, determine its ability to accurately predict heart disease.


---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## **Resources**

-Data Source: `heart_disease_key_indicators.csv', 'binary_data.csv, 'heart_dummies.csv', 'heart_undersampled.csv', 'heart_clean.csv', 'non-binary_data.csv', 'HeartDisease_ERD.png'.

-Software: `Python 3.7.10`, `Visual Studio Code 1.38.1`, `Jupyter Notebook`, `Anaconda3`, `PgAdmin`. 

-Resources: https://www.kaggle.com/datasets?search=heart+disease.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## **Project Deliverables** 

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Segment 1 Deliverables

**Presentation**

**Approach**
We will be using the Agile approach to project management. Based on the fact that team members are not familiar with each other and come from different skill levels, we required a methodology that is be flexible, yet still provide clear goals and tasks. This seemed particularly relevant as each team member can harness their own strengths for deliverables and apply them to weekly tasks. 
Furthermore, this approach prevents members from being solely responsible for one task throughout and encourages a collaborative team. 

**Topic Selection**
We selected a dataset that analyses factors that lead to heart disease. We reviewed several other open-source datasets however, we selected this one based on interest, its relevancy, and the ability of the created machine learning model to be applicable to real world scenarios and provide a foundation from which similar datasets could be analysed.

A link to the dataset can be found [here](https://github.com/Rangisal/Group-7-Project/blob/main/Resources/heart_disease_key_indicators.csv):

**Questions To Be Answered**

We hope to answer the following questions throughout the project:

1. What are the key indicators that lead to heart disease. 
2. What factors had the greatest influence on a person developing heart disease and in what proportions.
3. Can a machine learning model accurately predict whether a person will develop heart disease based on the data provided.

**GitHub**

A link to the main page of the Group 7 Final Project GitHub repository can be found [here](https://github.com/Rangisal/Group-7-Project):


[Branches](https://github.com/Rangisal/Group-7-Project/blob/mcbride_branch/Images/Segment_1_Image_1_Active_Branches.png) have been created for each member of the group.
![Segment_1_Image_1_Active_Branches](https://user-images.githubusercontent.com/92111396/159023203-74e01501-5741-4d6e-b2c6-e72b47893cda.png)

**Communication Protocols - Standard Operating Procedures (SOPs)**
1. Weekly meeting will be held on Tuesday and Thursday of each week (1900-2100).
2. All group discussion will be conduced on the “Group 7 Chat” on Slack.
3. Consult weekly task list.
4. Provide initial/update code as required.
5. After each major update to code or 1 hour of work, upload to GitHub under individual branch.
6. Once committed to individual branch, tag to a specific member for review. 
7. The reviewing member is to make changes/suggestions as necessary for the specified code to which they have been tagged.
8. The reviewing member will then upload code to their own branch and tag the original member.
9. Original member will review code and upload to main page.
10. Alert the team to all commits to main GitHub page.
11. All code uploaded to the main page should be reviewed by at least 1 other member.

A weekly tracker has also been created and will be uploaded to GitHub outlining each member’s tasks and the priority of work for the week. A link to the PowerPoint presentation and weekly task tracker can be found [here](https://github.com/Rangisal/Group-7-Project/blob/main/Data%20Analytics%20Group%207%20Workflow%20Procedure.pptx): 


**Machine Learning Model**

A preview of the machine learning model code can be found [here](https://github.com/Rangisal/Group-7-Project/blob/main/Logistic_Regression_Heart_Disease.ipynb):

![Logistic_Regression_Heart_Disease](https://user-images.githubusercontent.com/42978221/159191274-773cead5-839b-4f86-a682-ac65068c2521.png)


**Database**

A preview of the SQL Database code can be found [here](https://github.com/Rangisal/Group-7-Project/blob/main/HeartDisease_DB%20creation.sql):

![pgAdmin Heart_Disease_db creation](https://user-images.githubusercontent.com/42978221/159190443-a7a88b8c-921f-4dda-b5fa-1bded3193aea.png)


---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Segment 2 Deliverables

**Presentation**

A link to the Google Slides presentation can be found [here](https://github.com/Rangisal/Group-7-Project/blob/main/Project%20-%20Group%207.pptx).

The above presentation will outline:
1.	The selected topic.
2.	Reason why the topic was selected.
3.	Questions we hope to answer with the data.
4.	A description of the data exploration phase of the project.

**GitHub**

A link to the main page of the Group 7 Final Project GitHub repository can be found [here](https://github.com/Rangisal/Group-7-Project).

A link to the branches of the Group 7 Final Project GitHub repository can be found [here](https://github.com/Rangisal/Group-7-Project/branches).

**Machine Learning Model**

A link to the machine learning of the Group 7 Final Project GitHub repository can be found [here](https://github.com/Rangisal/Group-7-Project/blob/main/Random%20Forest%20Classifier%20Model..ipynb).

The Logistic Regression model compares the actual outcome (y-test) from the test set against the model's predicted values (predictions). 
We obtained the accuracy score of the model, which is simply the percentage of predictions that are correct. In our case, the model's accuracy score is 0.916, meaning that the model was correct 91.6% of the time.

![Seg2 - Regression - Model validation Results](https://user-images.githubusercontent.com/42978221/161459329-e99ca650-0438-448e-88c9-38c3c6c3f7d4.png)

Additionally, we implemented a random forest algorithm into our analysis to rank the importance of input variables in our predictions.
It is clear that the most relevant features to impact decisions based on our model are SleepTime, PhysicalHealth and MentalHealth, followed by others.

![Seg2 - Randon Forest - Rank Important Features](https://user-images.githubusercontent.com/42978221/161459364-ce49f15b-710b-4b2e-a1af-ecedd6eb1abd.png)


**Database**

A link displaying the code in the database of the Group 7 Final Project GitHub repository can be found [here](https://github.com/Rangisal/Group-7-Project/blob/main/binary_nonbinary_tables.sql) where two tables were created, one with binary data and the second table only containing non-binary data. We were able to join both tables using an inner join on the **id** column, the join can be found [here](https://github.com/Rangisal/Group-7-Project/blob/main/tables_join.sql).

![image](https://user-images.githubusercontent.com/91766276/161567395-db098bfb-6429-4fd0-a77e-43695c2a18b2.png) ![image](https://user-images.githubusercontent.com/91766276/161568335-0967fd5d-024b-4974-8e41-e16e763810ff.png)



**Dashboard**

A link to the dashboard of the Group 7 Final Project GitHub repository can be found [here](https://public.tableau.com/app/profile/ethan.mcbride/viz/HeartDiseaseKeyIndicatorsDashboard/GeneralOverview).

Tableau Public was the tool used to create the dashboard. The dashboard tells the story of the data and presents it in a visually appealing way that aims to allow audiences, particularly physicians, and to a lesser extent the lay public as to what the main influencers are of heart disease and to what degree each factor can influence an individual’s ability to develop heart disease. The dashboard was comprised of elements that outline each factors relationship to the overall data. Visually, individual health concerns and factors such gender and smoking habits are delineated by colour and hovering over each parcel of data on a particular graph provides a specific insight for that datum.  


---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Segment 3 Deliverables

**Presentation**
A link to the Google Slides presentation can be found [here](https://github.com/Rangisal/Group-7-Project/blob/main/Project%20-%20Group%207.pptx).

The above presentation will outline with more information than the segment 2:

1. The selected topic.
2. Reason why the topic was selected.
3. Description of source of data.
4. Questions we hope to answer with the data.
5. A description of the data exploration phase of the project.
6. A description of the analysis phase of the project.
7. Technologies , languages , tools and algorithms used throughout the project.

**Github**

A link to the main page of the Group 7 Final Project GitHub repository can be found [here](https://github.com/Rangisal/Group-7-Project).

A link to the branches of the Group 7 Final Project GitHub repository can be found [here](https://github.com/Rangisal/Group-7-Project/branches).


**Machine Learning Model**

A link to the machine learning model for logistic regression of the Group 7 Final Project GitHub repository can be found [here](https://github.com/Rangisal/Group-7-Project/blob/main/Logistic_Regression_Heart_Disease.ipynb)

A link to the machine learning model for random forest model of the Group 7 Final Project GitHub repository can be found [here](https://github.com/Rangisal/Group-7-Project/blob/main/Random%20Forest%20Classifier%20Model..ipynb)

Each model describes the following information,

1. Description of data preprocessing 
2. Description of feature engineering and the feature selection, including their decesion making process.
3. Description of how data was split in to training and testing sets.
4. Expalnation of model choice including limitations and benefits.
5. Explanation of changes in model choice.( between seg 2 seg 3)
6. Description of how the data have been trained the model and any additional training that took place.
7. Description of current accuracy score. 


**Dashboard**

A link to the dashboard of the Group 7 Final Project GitHub repository can be found [here](https://public.tableau.com/app/profile/ethan.mcbride/viz/HeartDiseaseKeyIndicatorsDashboard/GeneralOverview).

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Segment 4 Deliverables
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## **Purpose**



---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## **Results**


---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## **Summary**

**Data Results**


**Recommendation**

