#  Equitable AI in Dermatology - AJL Kaggle Competition Team 9

---

### **👥 Team Members**

| Name | GitHub Handle | Contribution |
| ----- | ----- | ----- |
| Mia Chen | @miachen67 | contributions |
| Eduard Bueno | @L4S3RB0Y | contributions |
| Jacquelyn Garcia | @JacquelynGarcia | contributions |
| Leon Ren | @leonren19 | contributions |
| Parini Gandhi | @pg-19 | contributions |

---

## **🎯 Project Highlights**

**Example:**

* Built a Convolutional Neural Network using TensorFlow/Keras to classify dermatological conditions  
* Implemented data augmentation techniques to improve generalization and address skin tone representation  
* Planned fairness evaluation using performance across different skin tone groups  
* Leveraged Kaggle datasets and starter notebooks to create a baseline model  

🔗 [Equitable AI for Dermatology | Kaggle Competition Page](https://www.kaggle.com/competitions/bttai-ajl-2025/overview)

---

## **👩🏽‍💻 Setup & Execution**

```bash
# Clone the repository
git clone https://github.com/your-team/dermatology-ai-ajl.git
cd dermatology-ai-ajl

# Create a virtual environment
python -m venv venv

# On Windows: venv\Scripts\activate
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Run the Jupyter Notebook
jupyter notebook Copy_of_AJL_Starter_Notebook.ipynb
```

---

## **🏗️ Project Overview**

This project is part of the AJL 2025 Kaggle Competition, run in collaboration with Break Through Tech AI. The goal is to build a dermatology classifier that works well across a wide range of skin tones, addressing fairness and bias in AI-driven healthcare.

---

## **📊 Data Exploration**

**Describe:**

* Dataset: Dermatology images and metadata from the Kaggle competition (train.csv, test.csv)
* Explored class distributions and imbalances
* Planned data augmentation to expand representation
* Identified potential fairness gaps due to uneven sample counts per condition

**Potential visualizations to include:**

* Plots, charts, heatmaps, feature visualizations, sample dataset images

---

## **🧠 Model Development**

* Used CNN - sequential model with Conv2D and MaxPooling layers
* Data preprocessing with rescaling, resizing, and augmentation
* Training on ~80% of data, validating on ~20%
* Evaluation metric: Accuracy

---

## **📈 Results & Key Findings**

* Early baseline model achieved 0.06105% accuracy

* Next phase includes hyperparameter tuning and deeper model evaluation

* Ongoing analysis of model performance across skin tone groups

**Potential visualizations to include:**

* Confusion matrix, precision-recall curve, feature importance plot, prediction distribution, outputs from fairness or explainability tools

---

## **🖼️ Impact Narrative**

**Answer the relevant questions below based on your competition:**

**WiDS challenge:**

1. What brain activity patterns are associated with ADHD; are they different between males and females, and, if so, how?
2. How could your work help contribute to ADHD research and/or clinical care?

**AJL challenge:**

1. What steps did you take to address [model fairness](https://haas.berkeley.edu/wp-content/uploads/What-is-fairness_-EGAL2.pdf)?
* Applied data augmentation to improve representation of under-sampled skin tones
* Plan to use a validation strategy that measures performance across different groups
* Incorporated fairness in evaluation planning

2. What broader impact could your work have?
* Enhances equitable AI in dermatology
* Increases awareness around algorithmic bias in clinical tools
* Inspires responsible ML development by integrating fairness from the ground up

---

## **🚀 Next Steps & Future Improvements**

* Evaluate performance across Fitzpatrick skin types
* Add explainability tools to interpret CNN decisions
* Test deeper architectures - ResNet, EfficientNet
* Include fairness metrics such as demographic parity
* Collect or synthesize more diverse training data if possible

---

## **📄 References & Additional Resources**

* AJL Fairness Guide
* TensorFlow/Keras Documentation
* Keras ImageDataGenerator


---


To run the notebook:
1. Make sure you’re in a Kaggle Notebook environment or have access to the dataset.
2. Install any missing libraries:
   ```bash
   pip install keras tensorflow numpy pandas
