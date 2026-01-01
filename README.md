🏠 Bengaluru House Price Prediction
An end-to-end Machine Learning project that predicts house prices in Bengaluru based on key property features such as location, total square feet, BHK, and number of bathrooms. The project also includes a Flask-based web application for real-time price prediction.


📌 Project Overview
The real estate market in Bengaluru is highly dynamic, making price estimation difficult for buyers and sellers. This project uses machine learning regression techniques to analyze historical housing data and predict accurate house prices.

The trained model is deployed using Flask, providing a simple and user-friendly web interface for predictions.


🚀 Features
Data cleaning & preprocessing
Feature engineering (location handling, BHK extraction, sqft conversion)
One-hot encoding for categorical variables
Linear Regression model using Scikit-learn
End-to-end ML pipeline
Flask web application for live predictions
Clean and responsive UI


🧠 Machine Learning Workflow

Data Collection

Dataset: Bengaluru House Price Dataset (CSV)

Data Preprocessing

Handling missing values

Converting total_sqft ranges into numerical values

Extracting BHK from size

Reducing dimensionality of location feature

Model Building

OneHotEncoder for categorical features

Linear Regression model

Pipeline using ColumnTransformer

Model Deployment

Flask-based web app

User inputs → Model prediction → Output price



🛠️ Tech Stack

Programming Language: Python

Libraries: Pandas, NumPy, Scikit-learn

Web Framework: Flask

Frontend: HTML, CSS

Tools: Jupyter Notebook



📊 Input Features

Location
Total Square Feet
BHK (Bedrooms)
Number of Bathrooms


📈 Output
Estimated house price (in Lakhs ₹)


▶️ How to Run the Project
1️⃣ Clone the repository
git clone https://github.com/your-username/bengaluru-house-price-prediction.git
cd bengaluru-house-price-prediction
2️⃣ Install dependencies
pip install -r requirements.txt
3️⃣ Run the Flask app
python app.py
4️⃣ Open in browser
http://127.0.0.1:5000



📸 Screenshots
<img width="877" height="922" alt="Screenshot 2026-01-02 014416" src="https://github.com/user-attachments/assets/bf25458a-432d-4ec6-90ec-f54fdf47bdab" />
<img width="609" height="815" alt="Screenshot 2026-01-02 014320" src="https://github.com/user-attachments/assets/b20b835c-3e8e-4985-b9ba-6f1f7ca80596" />
<img width="1022" height="926" alt="Screenshot 2026-01-02 014302" src="https://github.com/user-attachments/assets/0f08373a-3daa-4f91-83c9-38efef9b5b59" />



🎯 Future Enhancements
Improve model accuracy using advanced regression models
Add model persistence using joblib
Deploy on cloud platforms (Render / AWS / GCP)
Add authentication and database support


👤 Author
Ashish Deswal
MCA | Machine Learning Enthusiast
📫 GitHub: https://github.com/Ashish-1628


⭐ If you find this project useful, feel free to star the repository!
