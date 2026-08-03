# Real-Time Context-Aware Text Classification & Live Stream Routing

## 📌 Project Overview

This project implements a **Real-Time Context-Aware Text Classification and Live Stream Routing System** that automatically classifies incoming customer feedback messages into predefined categories and routes them to the appropriate department. The system is designed to process high-volume, unstructured customer feedback efficiently using Natural Language Processing (NLP) and Machine Learning techniques.

The project uses **TF-IDF Vectorization** for feature extraction and a **Multinomial Naive Bayes** classifier for text classification. It also detects message priority based on predefined keywords and simulates real-time message routing.

---

## 🎯 Objectives

* Classify customer feedback into relevant categories.
* Automatically route messages to the appropriate department.
* Detect high-priority messages using keyword analysis.
* Simulate a real-time customer feedback stream.
* Evaluate the performance of the machine learning model.

---

## 📂 Dataset

**Dataset:** `customer_feedback - customer_feedback.csv`

The dataset contains customer feedback messages along with their corresponding categories.

Example columns:

* **Feedback** – Customer feedback text.
* **Category** – Target classification label.

---

## 🛠 Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* WordCloud
* Jupyter Notebook

---

## 📊 Machine Learning Workflow

1. Load the dataset.
2. Perform data exploration.
3. Visualize category distribution.
4. Generate a Word Cloud.
5. Split data into training and testing sets.
6. Convert text into numerical features using TF-IDF.
7. Train a Multinomial Naive Bayes classifier.
8. Evaluate model performance.
9. Detect message priority.
10. Route classified messages to the appropriate department.
11. Simulate live message streaming.

---

## 📁 Project Structure

```
Real-Time-Text-Classification/
│
├── customer_feedback - customer_feedback.csv
├── Real_Time_Context_Aware_Text_Classification_Live_Stream_Routing.ipynb
├── README.md
└── requirements.txt
```

---

## ⚙ Installation

Clone the repository:

```bash
git clone <repository-url>
```

Navigate to the project directory:

```bash
cd Real-Time-Text-Classification
```

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn wordcloud
```

---

## ▶ Running the Project

Open the Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```
Real_Time_Context_Aware_Text_Classification_Live_Stream_Routing.ipynb
```

Run all cells sequentially.

---

## 📈 Model Used

* **Feature Extraction:** TF-IDF Vectorizer
* **Classifier:** Multinomial Naive Bayes

---

## 📊 Evaluation Metrics

The notebook evaluates the model using:

* Accuracy Score
* Classification Report
* Confusion Matrix

---

## 🚦 Live Stream Routing

Each incoming message is:

* Classified into a category.
* Checked for priority keywords.
* Routed to the appropriate department.

Example:

```
Incoming Message:
Need refund immediately

Predicted Category:
Billing

Priority:
HIGH

Route To:
Finance Team
```

---

## 🏢 Routing Logic

| Predicted Category | Routed Department      |
| ------------------ | ---------------------- |
| Billing            | Finance Team           |
| Delivery           | Logistics Team         |
| Product            | Quality Assurance Team |
| Technical Support  | IT Support Team        |
| General Inquiry    | Customer Care Team     |

---

## 🔥 Priority Detection

The system marks messages as **HIGH** priority if they contain keywords such as:

* urgent
* immediately
* critical
* refund
* error
* failed
* not working

Otherwise, the message is marked as **NORMAL** priority.

---

## 📌 Features

* Real-time text classification
* Automatic message routing
* Priority detection
* TF-IDF feature extraction
* Naive Bayes classifier
* Interactive user input
* Live stream simulation
* Data visualization
* Word Cloud generation
* Confusion Matrix visualization

---
**OUTPUTS**:
<img width="676" height="502" alt="image" src="https://github.com/user-attachments/assets/24ffc812-1ee3-45a3-bd85-65c1f7c09c4c" />


<img width="515" height="290" alt="image" src="https://github.com/user-attachments/assets/0e231985-e978-4955-8121-f805a46db5e5" />


## 🚀 Future Enhancements

* Deep Learning models (LSTM, GRU, BERT)
* Real-time streaming with Apache Kafka
* REST API using Flask or FastAPI
* Database integration (MySQL/Firebase)
* Web dashboard for monitoring
* Email and SMS notifications
* Cloud deployment

---

## 👨‍💻 Author

**Pradeepa**

Bachelor of Computer Applications (BCA)

---

## 📄 License

This project is intended for educational and academic purposes.
