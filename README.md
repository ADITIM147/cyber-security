# cyber-security
This interactive Streamlit-based app allows users to upload and analyze web traffic logs (like from AWS CloudWatch) to detect suspicious activities and anomalies using machine learning. Designed for cybersecurity and data analysis tasks.
🔍 Key Features
📊 Exploratory Data Analysis (EDA)

Histogram of traffic (bytes_in, bytes_out)

Protocol usage distribution

Country-wise interaction heatmap

Port-based analysis for suspicious traffic

🧪 Anomaly Detection

Uses Isolation Forest to flag abnormal sessions

Visualizes normal vs. suspicious data using scatter plots

🧠 Supervised Learning Models

Random Forest Classifier and a Neural Network (Keras)

Classifies whether a session is suspicious (WAF-detected)

Provides model accuracy, confusion matrix, and ROC curve

🌐 Network Graph

Shows source-to-destination IP interactions using NetworkX

📈 Model Comparison Dashboard

Compares Isolation Forest, Random Forest, and Neural Network

🚀 Deployment Instructions (Google Colab)
Just upload your CloudWatch_Traffic_Web_Attack.csv file

The app runs in a Google Colab environment

Exposed publicly using localtunnel (no need for ngrok token)

Can be accessed from any device via a shared link

🛡️ Ideal For
Security analysts and researchers

Students working on cybersecurity ML projects

Quick threat visualization without installing anything
