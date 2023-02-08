# Self_Assessment

## Cohesive Written analysis

As part of the project team, I helped in choosing the dataset for the project. We were debating on what type of dataset we should choose and I suggested that we should focus on the Heathcare sector and choose a classification dataset on which Supervised machine learning models can be used. I believe the biggest challenege was to chose a Dataset that would suffice our requirements since a bad dataset would have compeletely derailed our analysis and coul have had a major impact on the deliverables. 
To ensure that we had a good dataset, we shortlisted some three to four datasets on the first day of the Project and then took some time to evaluate them. Finally we decided to puruse the Heart Risk dataset which everybody agreed on. 
As part of my deliverables, I carried out the analysis of the dataset including Preprocessing, training of the model, and final results and also made the Dashboard for visulization. 

## Cohesive written summary

After choosing the dataset, we divided the responsibilites within our team and started working on our sections. As part of the team, I used to provide constructive feedback to team members on their deliverables. I was constantly asking probing questions to team mates on their deliverables/sections and even requested them to carry out necessary changes after some persuation. Incase, I had doubts, I would ask one of the TA's for more clarification. For my own deliverbales, I used to regularly share them with my project team for their feedback. 

## Project and Team Summary

Our project team decided to meet every Monday and Wednesday during the class room hours to discuss any issues, challenges and progress made. Incase some one had encountered any major issues with their deliverbales, they would post it on the Project team chanel for others to comment/advise. On mutliple occasions, when we were not sure about a topic, we would request to TA's to guide us and sometimes we would put it to vote (which was very seldom). 

One of the challenges was creating the ERD diagram, as we had only one CSV file and 918 rows and 14 columns of data. The unique values were not sufficient enough so we decided to create a Patient ID column (Primary key) and then link this feature accross all tables. Later, during the analysis this column would be dropped and not included as part of the analysis. Apart from this, creating Dashboard for visualization was another challenge and we managed to resolve it by using Tableau. 

Some advise I would like to give to new Cohort members is to spent more time in choosing the right dataset. This step I feel is very important as everything else depends on it. Also, it is important to identify the strength and weakness of your team members and then allocate tasks to them and also provide team members with support when required. 

The dataset which we selected was surprisingly very clean without any null and duplicted values. We did not actipiate this and were expecting some amount of work required for preprocessing. Also, we did not have to carry out any additional binning operations for the "Object" columns prior to using OneHotEncoder. The only preprocessing step required was to check the features for their importance and drop the less relevant features. Also, upon reviewing the number of More and Less Risk cases, we found that the dataset was well balanced and hence did not require Under and Over sampling. 

![Heatmap](https://github.com/Manishthapa2022/Self_assessment/blob/main/Images/HeatMap_feature.png)

As part of the evaluation for this dataset, we carried out the analysis using three models that is RandomForestClassifier, LogisticsRegression and AdaBoostClassifier. Also, it is important to note that we did not carry out any Over and under sampling as the data was evenly divided among the More and Less risk patients.

![More and Less Risk](https://github.com/Manishthapa2022/Self_assessment/blob/main/Images/data%20imbalance%20check.png)


![Results Summary](https://github.com/Manishthapa2022/Self_assessment/blob/main/Images/Overall_summary.png)

Based on the analysis for the given dataset, we have achieved good Precision, Recall and F1 scores for all the models and the highest in this instance was for the RandomForestClassifier model. The most importance score is the Recall score for More risk that is 0.93 which showcases that we had a few wrongly diagnosed Actual More Risk cases which were Predicted low.







