# 🤖 Support Ticket Classification & Prioritization

## Future Interns | Machine Learning Track | Task 02 | FUTURE_ML_02

# 📌 About This Project

Built a **Natural Language Processing (NLP) based Machine Learning system** that automatically classifies customer support tickets and assigns priority levels.

Support teams often receive hundreds of customer issues every day.
This system helps **automatically categorize tickets and identify urgent issues**, allowing teams to respond faster and improve customer satisfaction.

# 🛠️ Tools & Technologies
* Python
* Google Colab
* NLTK (Natural Language Processing)
* Scikit-learn
* Pandas & NumPy
* Matplotlib & Seaborn
# 📁 Dataset
* **Name:** Customer Support Ticket Dataset
* **Source:** Kaggle
* **Type:** Text-based customer support issues
* **Use Case:** Multi-class text classification

# ✅ Key Features Implemented
## **1. Text Preprocessing**

* Converted text to lowercase
* Removed punctuation & special characters
* Removed stopwords
* Tokenized support ticket text

## **2. Feature Engineering**

* Text vectorization using **TF-IDF**
* Converted textual ticket data into numerical features for ML models

## **3. Models Trained**

* Naive Bayes
* Logistic Regression
* Random Forest Classifier ✅ Best Model

## **4. Model Evaluation**

| Metric             | Value                                         |
| ------------------ | --------------------------------------------- |
| Best Model         | Random Forest                                 |
| Accuracy           | ~88%                                          |
| Evaluation Methods | Accuracy, Precision, Recall, Confusion Matrix |

## **5. Visualizations**

* Ticket Category Distribution
* Word Cloud of Support Tickets
* Confusion Matrix
* Model Comparison Results
* Example Ticket Predictions
  
# 🚨 Priority Prediction Logic

Ticket priority is determined using **keyword-based urgency detection**.

| Keywords                           | Priority |
| ---------------------------------- | -------- |
| error, failed, server down, urgent | High     |
| login issue, account problem       | Medium   |
| general information requests       | Low      |


# 🧪 Example Ticket Prediction

### Input Ticket

```id="k4v3pn"
My payment failed but money was deducted from my account
```

### Model Output

```id="9m9vfw"
Category: Billing
Priority: High
```
# 💡 Business Insights

This system helps organizations:

* Automatically categorize customer support tickets
* Detect urgent issues faster
* Reduce support response time
* Improve operational efficiency in customer service

Industries where this can be used:

* SaaS companies
* IT service desks
* E-commerce customer support
* Telecom customer support systems


# 📸 Output Screenshots

All model outputs, visualizations, and prediction results are included in this repository.


# 🔗 Links

* 📓 Google Colab Notebook:https://colab.research.google.com/drive/1Mr8gLRXLhy2d3YISg2eOb-fQ2z-k3R7s#scrollTo=Mos9wIUgxe7N
* 💼 LinkedIn Post: 

---

# 👤 Author

* **Name:** Pallavi Sowreddi
* **Internship:** Future Interns
* **Track:** Machine Learning
* **Task:** 02 — Support Ticket Classification & Prioritization
