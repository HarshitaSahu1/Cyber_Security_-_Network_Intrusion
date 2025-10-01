# Cyber_Security_-_Network_Intrusion
Cybersecurity project for intrusion detection: binary vs multi-class attack classification using ML.

Cyber_Security_- Network_Intrusion

This project focuses on Network Intrusion Detection using Machine Learning techniques. The dataset used in this project is highly imbalanced, with the majority of samples belonging to the "Normal" class and very few belonging to specific attack categories.

[Attack_Distribution](Attack_Type_Distribution.png)

🔍 Classification Approaches

Binomial Classification → Attack vs. Normal

Multinomial Classification → Normal vs. Back, Buffer Overflow, FTP Write, Guess Password, Neptune, N-Map, Port Sweep, Root Kit, Satan, Smurf

📊 Key Insights

Due to heavy class imbalance, traditional models often struggle to detect minority attacks.

In this project, different classification models were tested.

The models achieved 100% accuracy, showing their strong ability to distinguish between normal and malicious traffic in this dataset.

⚠️ Important Note

While achieving 100% accuracy is impressive, in highly imbalanced datasets, accuracy alone may not fully represent model performance. For example:

A model might predict mostly the majority class and still achieve high accuracy.

Hence, additional evaluation metrics like Precision, Recall, and F1-score are crucial to understand the true effectiveness of the model, especially for rare attack classes.
