# Churn-Prediction


This project predicts whether a bank customer is likely to **churn** (leave the bank) based on their profile and account activity. It uses an **Artificial Neural Network (ANN)** trained on the **Churn_Modelling.csv** dataset.

A **Streamlit app** is also included to allow interactive predictions by entering customer details.


**⚙️ Installation**

1. Clone the repository:

  git clone https://github.com/Aastha-Jainn/Churn-Prediction.git

  cd Churn-Prediction


2. Create a virtual environment (optional but recommended):

  python -m venv venv

  source venv/bin/activate   # On Linux/Mac

  venv\Scripts\activate      # On Windows


3. Install dependencies:

  pip install -r requirements.txt

**🚀 Running the Streamlit App**

Run the app with:

streamlit run app.py


Then open the provided URL (usually http://localhost:8501/) in your browser.

**🧠 Model**

Model: Artificial Neural Network (ANN) built with TensorFlow/Keras

Input features include:

Credit score

Geography

Gender

Age

Tenure

Balance

Number of products

Has credit card (Yes/No)

Active member (Yes/No)

Estimated salary

Output: Probability of churn (0 → Not likely, 1 → Likely)



**📌 Requirements**

See requirements.txt:

TensorFlow 2.15

Streamlit

Pandas, NumPy

scikit-learn

Matplotlib

scikeras


