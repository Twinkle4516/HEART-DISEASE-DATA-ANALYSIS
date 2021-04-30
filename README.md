# Heart-Disease-Data-Analysis

Heart disease is one of the major causes of death for people in in united states. Some disturbing facts about heart disease is,
• A single person goes through death every 36 seconds in united states from cardiovascular diseases or heart diseases that accounts for 6,55,000 deaths every year and that totally counts for 1 in every 4 deaths which is actually a very big reason for deaths in the country.
• The cost spent on united states on heart and cardiovascular disease is close to 219 billion dollars from 2014 to 2015, although the number of deaths saw a drastic change of number to 3,75,980 in 2017.
So, my analysis has been made on the following issues and after careful consideration the project it has been divided into 4 categories for complete analysis and prediction of this deadly disease. Below are the 4 categories:

1. Introduction to Business problem:
Determining the presence of heart disease in people with the help of predictive analytics.

2. Diagnosis:
For performing on the diagnosis, I have created EDA on the heart disease dataset and a thorough analysis provided the insights of the dataset.

3. Predictive Models:
Model to use after performing the EDA we need to find out that what kind of different models to be used and even check the accuracy for the following.

4. Future scope:
After careful consideration of EDA and predictive models we need to check what are the observations and how we can improve them in near future applications.

Exploratory Analysis
There are thirteen features and one target as below:

age: The person's age in years
sex: The person's sex (1 = male, 0 = female)
cp: The chest pain experienced (Value 1: typical angina, Value 2: atypical angina, Value 3: non-anginal pain, Value 4: asymptomatic)
trestbps: The person's resting blood pressure (mm Hg on admission to the hospital)
chol: The person's cholesterol measurement in mg/dl
fbs: The person's fasting blood sugar (> 120 mg/dl, 1 = true; 0 = false)
restecg: Resting electrocardiographic measurement (0 = normal, 1 = having ST-T wave abnormality, 2 = showing probable or definite left ventricular hypertrophy by Estes' criteria)
thalach: The person's maximum heart rate achieved
exang: Exercise induced angina (1 = yes; 0 = no)
oldpeak: ST depression induced by exercise relative to rest
slope: the slope of the peak exercise ST segment (Value 1: upsloping, Value 2: flat, Value 3: downsloping)
ca: The number of major vessels (0-3)
thal: A blood disorder called thalassemia (3 = normal; 6 = fixed defect; 7 = reversable defect)

target: Heart disease (0 = no, 1 = yes)


Analysis: 

A co-variable relationship could be positive, which means the two factors move a similar way, or negative, implying that when one variable's worth expands, the other factors' qualities decline. Factors inside a dataset can be connected for loads of reason. A clear indication between the heat matrix or the correlation matrix can be seen for some variables where chest pain is very much dependent on the age of the patient where higher age patient sees a clear indication between the chest pain. A similar pattern was seen for cholesterol of the patient and age of the patient where higher age patient had chest pain. Target is much related to two of the attributes, chest pain and the maximum heart rate.

<img width="1000" alt="Screen Shot 2021-04-30 at 3 07 23 PM" src="https://user-images.githubusercontent.com/77697669/116742773-db6df500-a9c5-11eb-8a8a-1c18fed87128.png">


From the bubble chart, we can observe the relation between five variables. These attributes are B.P, cholesterol, age, sex, and heart rate. We see that most dense part are the people who are suffering are of the age of 58, followed by 57. Majorly, people belonging to the age group 50+ are suffering from the disease. We can check the age range by changing the slider.


Conclusion:

For several years, cardiovascular disease has been the leading cause of death. I believe the causes are our lack about understanding of heart disease and our lifestyle choices. We know which features we can do daily self-examinations based on the model and features analysis.

The most noticeable symptom, in my opinion, is chest pressure. Just atypical angina is closely linked to heart failure among the three forms of chest pain. Go to the hospital regardless of the kind of chest pressure you're experiencing.

Furthermore, everybody should keep a close watch on their sleeping blood pressure. While the average resting blood pressure is less than 120mmHg, if the blood pressure is any lower than that, you are at a high risk of heart failure. Furthermore, as blood pressure exceeds 150mmHg, the issue is not limited to the heart.

There are many electronic sensors that can calculate heart rate, making it easy to keep track of your own. Keep track of the maximum heart rate to ensure that your heart is still in good shape. There must be something wrong with you if the trend continues to climb year after year.

We must get an annual inspection regardless of how safe we are and such features cannot be taken care of by ourselves. Finally, keep in mind that the older we become, the greater the threats get.
