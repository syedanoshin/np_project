# np_project
Let us build a project to learn more about NumPy:

Features of the data set:

Age: Age of the person

education-num: No. of years of education they had

race: Person's race 0 - Amer-Indian-Eskimo
1 - Asian-Pac-Islander
2 - Black
3 - Other
4 - White

sex: Person's gender 0 - Female
1 - Male

capital-gain: Income from investment sources, apart from wages/salary

capital loss: Losses from investment sources, apart from wages/salary

hours-per-week: No. of hours per week the person works

income: Annual Income of the person
0 : Less than or equal to 50K
1 : More than 50K
# Step 1 : Read the Data!
# Step 2 : Append the Data
# Step 3 : Check if it's a young country or old country
* Create a new array called 'age' by taking only age column(age is the column with index 0) of 'census' array.

* Find the max age and store it in a variable called 'max_age'.

* Find the min age and store it in a variable called 'min_age'.

* Find the mean of the age and store it in a variable called 'age_mean'.

* Find the standard deviation of the age and store it in a variable called 'age_std'
# Step 4: Let's check the country's race distribution to identify the minorities
* Create four different arrays by subsetting 'census' array by Race column(Race is the column with index 2) and save them in 'race_0','race_1', 'race_2', 'race_3' and 'race_4' respectively(Meaning: Store the array where 'race'column has value 0 in 'race_0', so on and so forth)

* Store the length of the above created arrays in 'len_0', 'len_1','len_2', 'len_3' and 'len_4' respectively

* Find out which is the race with the minimum no. of citizens

* Store the number associated with the minority race in a variable called 'minority_race'(For eg: if "len(race_5)" is the minimum, store 5 in 'minority_race' because that is the index of the race having the least no. of citizens )

# Step 5: As per govt. records citizens above 60 should not work more than 25 hours a week. Let us check if the policy is in place
* Create a new subset array called 'senior_citizens' by filtering 'census' according to age>60 (age is the column with index 0)

* Add all the working hours(working hours is the column with index 6) of 'senior_citizens' and store it in a variable called 'working_hours_sum'

* Find the length of 'senior_citizens' and store it in a variable called 'senior_citizens_len'

* Finally find the average working hours of the senior citizens by dividing 'working_hours_sum' by 'senior_citizens_len' and store it in a variable called 'avg_working hours'.

* Print 'avg_working_hours' and see if the govt. policy is followed.

# Step 6: Let's check that higher educated people have better pay in general.
* Create two new subset arrays called 'high' and 'low' by filtering 'census' according to education-num>10 and education-num<=10 (education-num is the column with index 1) respectively.

* Find the mean of income column(income is the column with index 7) of 'high' array and store it in 'avg_pay_high'. Do the same for 'low' array and store it's mean in 'avg_pay_low'.
