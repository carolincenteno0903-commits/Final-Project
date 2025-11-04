# Final-Project

This dataset shows the relationship between lifestyle choices and their effects on overall sleep health.

Link to dataset https://www.kaggle.com/datasets/minahilfatima12328/lifestyle-and-sleep-patterns

Data Cleaning was necessary to check for missing values and duplicate rows. There were some missing values in the Sleep Disorder column that i filled in with 'Unknown'.

The data manipulation steps were necessary because by grouping by Sleep Disorder i was able to see the frequency of each sleep disorder to analyze which ones are more common than others. 

The other data manipulation step I took was filtering by BMI Category. I specifically wanted to see the individuals in the Overweight category so I can analyze characteristics in this specific group.

Bar Chart of Sleep Disorder Counts: <img width="571" height="455" alt="image" src="https://github.com/user-attachments/assets/5a1d3880-679f-4791-ad22-d5062bd3c999" />
This Bar Chart shows the Counts of Each Sleep Disorder where Insomnia and Sleep Apnea were the same count but the Unknown category had the most counts. 

Scatter Plot of Sleep Duration vs. Quality of Sleep: <img width="554" height="455" alt="image" src="https://github.com/user-attachments/assets/80fdf881-71dd-40ce-b5e9-d198f94aa4ee" />
This scatter plot shows that when sleep duration tends to increase, quality of sleep tends to increase as well.

Box Plot of Physical Activity Level by BMI Category: <img width="841" height="547" alt="image" src="https://github.com/user-attachments/assets/9fee4f01-0b89-4ce3-9f6a-2e92755526ff" />
This box plot shows the physical activity level for each BMI category which was Overweight, Normal, Obese and Normal Weight.


Based on the correlation matrix:

Strong Positive Correlation:

Sleep Duration and Quality of Sleep have a strong positive correlation (around 0.88). This suggests that as sleep duration increases, the quality of sleep also tends to increase.
Physical Activity Level and Daily Steps have a strong positive correlation (around 0.77). This is expected, as more physical activity often means more daily steps
Strong Negative Correlation:

Sleep Duration and Stress Level have a strong negative correlation (around -0.81). This indicates that as sleep duration increases, stress level tends to decrease.

Quality of Sleep and Stress Level have a strong negative correlation (around -0.89). This suggests that higher quality of sleep is associated with lower stress levels.

Quality of Sleep and Heart Rate have a moderately strong negative correlation (around -0.66). This implies that better sleep quality is associated with a lower heart rate.

Moderate Positive Correlation:

Stress Level and Heart Rate have a moderate positive correlation (around 0.67). Higher stress levels are associated with a higher heart rate.
