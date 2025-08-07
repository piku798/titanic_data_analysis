# titanic_data_analysis
🎯 Objective
The purpose of this analysis is to understand the survival patterns among passengers on the Titanic using the Titanic dataset, with a focus on features such as age, sex, and passenger class (Pclass). After careful observation and visualizations, we concluded that:

🔍 "Most of the passengers who died were males from the 3rd class, aged between 20–30 years."

📊 Key Dataset Columns Used
Survived – 1 (survived), 0 (did not survive)

Pclass – Ticket class (1st, 2nd, 3rd)

Sex – Gender of the passenger

Age – Age of the passenger

AgeRange – Derived from Age, grouped into bins like 0–10, 11–20, etc.

Columns like Parch, Ticket, Fare, Cabin, and Embarked were not crucial for this conclusion and are omitted from this detailed analysis.

📈 1. Overall Survival Count
The total number of passengers who survived and those who didn’t was visualized using a bar plot. It revealed:

More passengers died than survived.

Only ~38% of passengers survived the disaster.

💺 2. Survival by Passenger Class (Pclass)
A grouped bar chart showed:

1st class passengers had the highest survival rate.

3rd class passengers had the highest death count.

The class of travel played a significant role in survival.

It is evident that passengers in lower classes had less access to lifeboats and safety measures, especially during chaotic evacuation processes.

🧍‍♂️🧍‍♀️ 3. Survival by Sex
Visualization of survival count by gender showed:

Most females survived, while most males died.

This supports the historical record of "women and children first" policy.

Among all males onboard, a large percentage perished.

📊 4. Survival by Age Range
We binned the Age into ranges and plotted survival counts. Findings:

Children (0–10) had relatively better survival chances, especially in 1st/2nd class.

Passengers aged 20–30 had the highest death count.

The 20–30 age group was mostly young adult males from the 3rd class.

This group may have been physically fit but lacked the social status or access to safety resources.

👨‍👩‍👦 5. Age + Pclass + Survival Combined
A stacked bar plot comparing age ranges by class for survived passengers highlighted:

Most 1st-class survivors were aged between 30–50.

Few 3rd-class passengers over age 50 survived.

The survivors aged 20–30 were mostly from 1st/2nd class; very few from 3rd class survived.

🚺🚹 6. Age + Sex + Survival
Side-by-side histograms for males and females showed:

Female survivors were present in all age groups, especially between 20–40.

Male survival was heavily skewed — most young adult males (20–30) died.

Even elderly women had better survival chances than young men, especially in lower classes.

👨‍👩‍👧‍👦 7. SibSp (Siblings/Spouses) vs Survival
Analysis showed:

Passengers with 1 or 2 family members had higher survival rates.

Those traveling alone (SibSp = 0) had a higher death rate.

Large family groups (SibSp > 3) had low survival — possibly due to inability to stay together or get seats in lifeboats.

🚫 8. Columns Not Required for Final Conclusion
We examined Parch, Ticket, Fare, Cabin, Embarked, and AgeRange, but for the final conclusion, these were not necessary because:

Fare, Ticket, and Cabin mostly correlated with Pclass.

Embarked had minimal impact compared to class, sex, and age.

Parch behaved similarly to SibSp, with minimal unique insight.

Thus, the focus remained on the strongest predictors: Pclass, Age, and Sex.

🧾 Final Conclusion
After in-depth analysis of the Titanic dataset:

Majority of the victims were males aged 20–30, especially from the 3rd class.

Females, particularly those in 1st and 2nd class, had much higher survival chances.

Age, gender, and class are the most critical factors in determining survival.

This pattern reflects social priorities of the time ("women and children first"), as well as systemic class bias, where those with more wealth and access (1st class) were prioritized for safety.


