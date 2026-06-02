**Problem Statement:** The dataset of the titanic comes in with a lot of missing values and many other data issues. Therefore, we need clean and prepocess the data. So here we clean the data by handling missing and duplicate values. We also rename the columns and convert there data types to prepare the raw data.

**Dataset Details:** The dataset of the titanic contains the data of those people who travelled on the titianic and were some being drowned and some being survived. The columns like age, sex, name, pclass,sbsp, embarked, city,adult_male are their personal informatons while some others like class,fare,alive,alone,survived are related to titanic and the tragedy. Some of the data specially ages of some are missing.

**Approach:** We store the dataset in the panda's dataframe where we check the missing values through isnull() , sum and arrange them and then remove the rows if missing% of a column<5  and remove the column if missing% of col>35 and take the mean if missing% is in between 5 and 30. we use pandas functions to remove values

**Results**: We get a very clean data after removing the missing and duplicate values which is very useful to be utilized in upcoming works
