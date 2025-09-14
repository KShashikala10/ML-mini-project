
---

# 🩺 Healthcare Chatbot – Disease Prediction & Doctor Recommendation

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python\&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-ML-yellow?logo=scikit-learn)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Handling-150458?logo=pandas)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-005571?logo=plotly)
![License](https://img.shields.io/badge/License-MIT-green)

---

## 📌 Overview

The **Healthcare Chatbot** is a machine learning project that predicts diseases based on patient-reported symptoms and recommends doctors accordingly.
It uses a **Decision Tree Classifier** trained on a medical dataset and provides:

* Disease prediction
* Symptom analysis with confidence score
* Doctor recommendation with contact info

This project simulates a real-world medical assistant by combining **machine learning** and **expert knowledge (doctor dataset)**.

---

## 🚀 Features

* **Disease Prediction**: Predicts possible diseases based on user responses to symptom questions.
* **Symptom Confidence Score**: Provides a confidence level for the prediction.
* **Doctor Recommendation**: Suggests doctors relevant to the predicted disease.
* **Interactive Chatbot**: Step-by-step conversation with the user in the console.

---

## 🛠️ Technologies Used

* **Python 3.x**
* **NumPy, Pandas** → Data handling
* **Scikit-learn** → Machine learning (Decision Tree)
* **Matplotlib** → Feature importance visualization (optional)

---

## 📂 Project Structure

```
Healthcare_Chatbot/
│── chatbot.py               # Main script
│── Training.csv             # Training dataset
│── Testing.csv              # Testing dataset
│── doctors_dataset.csv       # Doctors info dataset
│── README.md                # Project documentation
```

---

## 📊 Datasets

1. **Training.csv**

   * Contains patient symptoms and corresponding disease labels.
   * Used for training the decision tree model.

2. **Testing.csv**

   * Used to evaluate the trained model.

3. **doctors\_dataset.csv**

   * Contains doctors’ names and links (description/contact).
   * Mapped to diseases for doctor recommendation.

---

## ⚙️ Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/your-username/Healthcare_Chatbot.git
   cd Healthcare_Chatbot
   ```
---

## ▶️ Usage

1. The chatbot will interactively ask:

   * “Do you have \[symptom]?” → reply with **yes** / **no**.

2. It will output:

   * Predicted disease
   * Symptoms matched
   * Confidence score
   * Recommended doctor with contact details

---

## 🖼️ Demo 

Here’s an example of the chatbot in action:

Please reply with yes/Yes or no/No for the following symptoms
palpitations ?
no
pain_behind_the_eyes ?
no
receiving_unsterile_injections ?
no
red_spots_over_body ?
no
unsteadiness ?
no
rusty_sputum ?
no
increased_appetite ?
yes

['You may have Diabetes ']

symptoms present  ['increased_appetite']

symptoms given  ['fatigue', 'weight_loss', 'restlessness', 'lethargy', 'irregular_sugar_level',
'blurred_and_distorted_vision', 'obesity', 'excessive_hunger', 'increased_appetite', 'polyuria']

confidence level is 0.1

The model suggests:

Consult  ['Dr. Anshul Gupta']

Visit  ['https://www.practo.com/delhi/doctor/dr-anshul-gupta-ear-nose-throat-ent-specialist-1?specialization=Ear-Nose-Throat%20(ENT)%20Specialist&practice_id=712546']


---

## 🔮 Future Improvements

* Build a **Streamlit Web App** for GUI-based interaction.
* Expand the **doctors dataset** with more details (location, specialization).
* Integrate **NLP models** to accept free-text user inputs.
* Deploy on **Cloud platforms (Heroku/AWS/GCP)** for public usage.

---
