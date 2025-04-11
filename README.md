# 🏡 House Price Prediction using Machine Learning

A beginner-friendly project to predict house prices based on various factors such as square footage, number of bedrooms, location, and more. This project walks through data exploration, visualization, linear regression, and gradient boosting to achieve high model accuracy.

---

## 📂 Project Structure

- `data/` – Dataset used for training and testing (you can provide a CSV or link here).
- `house_price_prediction.ipynb` – Main Jupyter Notebook with all code.
- `requirements.txt` – Python dependencies.
- `README.md` – This file.

---

## 📊 Dataset

This dataset contains details of house listings including:

- Number of bedrooms and bathrooms
- Square footage (with and without basement)
- Waterfront presence
- Location via latitude and longitude
- Zipcode
- Year built and renovated
- Price of the house

Source: [Mention source or link here if applicable]

---

## 🧪 Models Used

### 1. **Linear Regression**
- First model used to understand relationships in data.
- Achieved ~73% accuracy.

### 2. **Gradient Boosting Regressor**
- Powerful ensemble model using decision trees.
- Achieved ~91.94% accuracy.

---

## 📈 Key Visualizations

- Most common house types by bedroom count
- Price vs. Living Area
- Price vs. Location (Latitude and Longitude)
- Influence of features like basement area, floors, condition, and waterfront on price

---

## 🔧 Requirements

Install dependencies using:

```bash
pip install -r requirements.txt
Main libraries:

pandas

numpy

matplotlib

seaborn

scikit-learn

🚀 How to Run
Clone this repo:

bash
Copy
Edit
git clone https://github.com/Shreyas3108/house-price-prediction.git
cd house-price-prediction
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Run the Jupyter Notebook:

bash
Copy
Edit
jupyter notebook house_price_prediction.ipynb
🎯 Goal
To achieve over 85% prediction accuracy in estimating house prices using regression techniques. Final model using Gradient Boosting achieved 91.94%.

📚 Learning Points
Data cleaning and preprocessing

Exploratory data analysis

Feature engineering

Linear Regression vs Gradient Boosting

Model evaluation using r2_score

📌 Credits
Written by Shreyas Raghavan
Originally published on Medium: Link to article

🌟 Contribute
Feel free to fork this project, improve the model, or apply it to other real estate datasets!

📬 Contact
For queries or collaborations, reach out on GitHub or comment on the Medium article.








