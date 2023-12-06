# An Exploratory Data Analysis Over Sleep Health and Lifestyle 
This repository contains both a public dataset sourced from Kaggle and a Jupyter Notebook that details the steps taken in conducting exploratory data analysis.
## Dataset
The dataset that I'm working with is taken from Laksika Tharmalingam's [Sleep Health and Lifestyle Dataset ](https://www.kaggle.com/datasets/uom190346a/sleep-health-and-lifestyle-dataset/)on Kaggle. It comprises 400 rows and 13 columns, covering a wide range of variables related to sleep and daily habits. It includes details such as gender, age, occupation, sleep duration, quality of sleep, physical activity level, stress levels, BMI category, blood pressure, heart rate, daily steps, and the presence or absence of sleep disorders.
| Header                      | Description            | Data Type          |
| --------------------------- | ---------------------- | ------------------ |
| Person ID                   | An identifier for each individual. | int64              |
| Gender                      | The gender of the person (Male/Female). | object             |
| Age                         | The age of the person in years. | int64              |
| Occupation                  | The occupation or profession of the person. | object             |
| Sleep Duration              | The number of hours the person sleeps per day. | float64            |
| Quality of Sleep            | A subjective rating of the quality of sleep, ranging from 1 to 10. | int64              |
| Physical Activity Level     | The number of minutes the person engages in physical activity daily. | int64              |
| Stress Level                | A subjective rating of the stress level experienced by the person, ranging from 1 to 10. | int64              |
| BMI Category                | The BMI category of the person (e.g., Underweight, Normal, Overweight). | object             |
| Heart Rate                  | The resting heart rate of the person in beats per minute. | int64              |
| Daily Steps                 | The number of steps the person takes per day. | int64              |
| Sleep Disorder              | The presence or absence of a sleep disorder in the person (None, Insomnia, Sleep Apnea). | object             |
| Blood Pressure              | The blood pressure measurement of the person, indicated as systolic pressure over diastolic pressure. | object              |
## An Exploratory Data Analysis
Initially, I sought to uncover relationships with categorical variables, prompting the question: "To what extent do potential relationships exist between sleep and physical activity patterns and categorical variables such as Gender, Occupation, and BMI?"

Upon deeper analysis, a subsequent question emerged: "Is there a notable association between exercise engagement and stress levels, and how does this interaction influence BMI?"
