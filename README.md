# ML-Olympiad-Nashik-Weather
Nashik being the best climate city has experienced every season like summer, winter, and rainy season with time. This competition aims to predict the condition of weather given the data of Nashik from the year 2022-2024(present-feb).

# code to import dataset 
import pandas as pd
df = pd.read_csv("train.csv")
Evaluation
Being classification problem where you have the classify the weather-condition between rain, partly-cloudy, and cloudy. The evaluation criteria for the submissions is F1 score

Submissions are evaluated on F1 Score



Submission File
For each datetime in the test set, you must predict a the weather-conditions for the TARGET variable. The file should contain a header and have the following format:

ID, weather-condition
1456, clear-day
2345, partly-cloudy-day
1678, rain
