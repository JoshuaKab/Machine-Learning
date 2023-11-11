#Machine Learning 

Hello Connections, 
I am happy to share the project that I've worked upon during my internship at MeriSKILL

My objective here was to diagnostically predict whether a patient has diabetes based on certain 
diagnostic measurements included in the dataset.

I had 768 rows of diagnostic measurements of women patients in my dataset from which 34.9% were diabetic 
and 65.1% were non-diabetic.

Here are some key findings:

• 𝐏𝐫𝐞𝐠𝐧𝐚𝐧𝐜𝐢𝐞𝐬: It appears that most women tend to have fewer pregnancies.
• 𝐆𝐥𝐮𝐜𝐨𝐬𝐞: The majority  have normal or lower glucose levels.
• 𝐁𝐥𝐨𝐨𝐝𝐏𝐫𝐞𝐬𝐬𝐮𝐫𝐞: Most individuals likely have higher blood pressure levels which has 30% corration with age.
• 𝐒𝐤𝐢𝐧𝐓𝐡𝐢𝐜𝐤𝐧𝐞𝐬𝐬: Typical skin thickness is 54% correlated with body mass index .
• 𝐈𝐧𝐬𝐮𝐥𝐢𝐧: Most individuals may have low insulin levels, but there are exceptions with very high values.
• 𝐁𝐌𝐈: Most individuals are higher BMIs, That makes me think why it 54% corrated with SkinThiness .
• 𝐃𝐢𝐚𝐛𝐞𝐭𝐞𝐬𝐏𝐞𝐝𝐢𝐠𝐫𝐞𝐞𝐅𝐮𝐧𝐜𝐭𝐢𝐨𝐧: Most show low values, while a select few display high values, indicating a strong family history of diabetes.
• 𝐀𝐠𝐞: The majority are younger.
• 𝐎𝐮𝐭𝐜𝐨𝐦𝐞: There are more individuals without diabetes (Outcome=0) than with diabetes (Outcome=1) in our dataset.

I used few Machine Learning Algorithms for this analysis, DecisionTreeClassifier(),
 and other model performance with metrics like accuracy, precision, recall, F1-score.

here are the metrics for both algorithms:

📌 DecisionTreeClassifier():
Accuracy Score : 0.75
Precision: 0.85
Recall: 0.79
F1-score: 82
Confusion Matrix:
[[84 23]
[15 32]]

---------------------------------
📌AdaBoost Classifier
Model performance for Training set
- Accuracy: 0.8371
- Precision: 0.8355
- Recall: 0.8371
- F1 Score: 0.8360

📌 CatBoostClassifier
CatBoosting Classifier
Model performance for Training set
- Accuracy: 0.9528
- Precision: 0.9541
- Recall: 0.9528
- F1 Score: 0.9521
