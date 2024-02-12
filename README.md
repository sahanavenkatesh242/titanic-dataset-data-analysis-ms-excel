# titanic-dataset-data-analysis-ms-excel

INTRODUCTION

This popular open-source dataset offers information on the passengers onboard the Titanic ship when it sank on April 15, 1912. 
It can be used by data analytics beginners interested in data cleaning and preprocessing, descriptive statistics, data visualization and predictive modeling.

Some of the variables included in the dataset:

  PassengerId - A unique identifier for each passenger.
  Survived - This shows whether the passenger survived or not (0 = No, 1 = Yes).
  Pclass - A passenger's class (1 = 1st, 2 = 2nd, 3 = 3rd).
  Name - A passenger's name.
  Sex - A passenger's gender.
  Age - A passenger's age. Male=0, Female=1
  SibSp - The number of siblings/spouses aboard.
  Parch - The number of parents/children aboard.
  Ticket - The ticket number.
  Fare - The fare paid for the ticket.
  Cabin - The cabin number.
  Embarked - The port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton). Act of boarding into the ship 

Since the values in the cabin column are very less, and after removing the empty cells from the given data, the data gets reduced to 182 rows which is very less when compared to original data with 891 rows. 
Hence by removing the cabin column makes no difference in the dataset. 
Also those empty cells in other columns are also removed(row delete)

The aim is to analyze the dataset with the help of a pivot table and data visualization using MS EXCEL.

The revised dataset is as follows:

![image](https://github.com/sahanavenkatesh242/titanic-dataset-data-analysis-ms-excel/assets/157820520/0dbbd308-e743-471a-af76-0e489c58d4ec)

1. What is the survival rate of passengers?
     ![image](https://github.com/sahanavenkatesh242/titanic-dataset-data-analysis-ms-excel/assets/157820520/cf873405-0fcd-4b14-9e3f-ef156f19b9b2)

This infers that there were 424 passengers who died (around 60%) and 288 passengers who survived (around 40%)

2. What is the proportion of male and female passengers?

   ![image](https://github.com/sahanavenkatesh242/titanic-dataset-data-analysis-ms-excel/assets/157820520/b3c255bf-8e4a-4e58-a8bb-1ff43566c8b8)
This infers that there were more of male than female. There were 63.63 % proportion of male when compared to female.

3. Which class of passengers had the highest survival rate?

   ![image](https://github.com/sahanavenkatesh242/titanic-dataset-data-analysis-ms-excel/assets/157820520/ebd83331-fc05-4b6b-9be0-68d815058973)

This infers that passengers at Pclass 1 had higher survival rate of 17% (120 passengers survived)

4. What is the distribution of fare paid by the passengers?

   ![image](https://github.com/sahanavenkatesh242/titanic-dataset-data-analysis-ms-excel/assets/157820520/f143ae53-ea13-4999-b407-a280bd4904c5)

  This infers that there were 406 passengers who paid the fare of around 0 to 21 dollars 

5. Find how many female who embarked at Q, C and S are dead.

     ![image](https://github.com/sahanavenkatesh242/titanic-dataset-data-analysis-ms-excel/assets/157820520/a6fb714f-07aa-4d18-9804-9a416d15a95c)

  This infers that around 53 female who embarked in S were dead.

6. What is the dead case in all the passenger class?

  ![image](https://github.com/sahanavenkatesh242/titanic-dataset-data-analysis-ms-excel/assets/157820520/233a81c7-2239-4d4c-b714-9e45cf081318)

  ![image](https://github.com/sahanavenkatesh242/titanic-dataset-data-analysis-ms-excel/assets/157820520/c2f3678a-1fda-4aaa-86eb-81ecf3376fd8)

  This infers that in class 3 there were 270 deaths happened.

7. How many ParCh (parents and children ) did the female and male had?

  ![image](https://github.com/sahanavenkatesh242/titanic-dataset-data-analysis-ms-excel/assets/157820520/aceee2e8-7d5d-4c6e-9955-a02524fd6e6a)

  This infers that female had more Pach (parents and childern) and male had more number of SibSp (siblings and spouse).

8. How many passengers  who had the age greater than 30 were survived?

     ![image](https://github.com/sahanavenkatesh242/titanic-dataset-data-analysis-ms-excel/assets/157820520/face7d45-903a-44bd-b197-dd7bc81d2201)

  This infers that 69% of female with age > 30 were survived.

9. How many passengers were survived(1) from Embarked southampthon(S) with high fare > 40?

      ![image](https://github.com/sahanavenkatesh242/titanic-dataset-data-analysis-ms-excel/assets/157820520/4df73b65-5366-412d-a38a-f9ea035b413a)

  ![image](https://github.com/sahanavenkatesh242/titanic-dataset-data-analysis-ms-excel/assets/157820520/5af4262c-b036-4265-8660-5957bef5a991)

This infers that female count were more with repsect to the survival, and who had embarked from S with fare >40.

10. How many females in the class 3 (P=3) with the age between 40 and 50 dead ?
    
      ![image](https://github.com/sahanavenkatesh242/titanic-dataset-data-analysis-ms-excel/assets/157820520/ea4738de-2470-4e00-b70a-f10fa284f9a7)

  With the help of pivot table, we can infer that there were 9 females who were aged between 40-50 in class 3 were died.

11. What is the distribution of age with respect to sex?

    ![image](https://github.com/sahanavenkatesh242/titanic-dataset-data-analysis-ms-excel/assets/157820520/05e44164-6008-4d96-a512-52f77896dc2a)

Steps involved in creating / merging 2 histogram in one:
      create a pivot table and drag age into the row and value column 
      convert the value into count 
      select the first values from the pivot table and from the analyse tab, select the group selection and decide the bin 
      then the data in the pivot table is been grouped 
      now add the next variable(sex) into the columns 
      now we can see the range of distribution from the pivot table 
      draw a bar chart and do change the specifications from the color and border 
      select anyone bar and right click and select format data series
      series overlap increase and gap width decrease

  ![image](https://github.com/sahanavenkatesh242/titanic-dataset-data-analysis-ms-excel/assets/157820520/7cb22244-84a2-44a4-8ba8-35145f6bc928)


This infers that there are 148 male in the age group between 20-30 and 72 females in the same age group which tends to be the highest.





This analysis is performed using Microsoft Excel, and no additional libraries or tools are required.
