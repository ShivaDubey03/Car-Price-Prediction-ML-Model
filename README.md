🚗 Car Price Prediction ML Web App

A Machine Learning-based web application that predicts the selling price of used cars based on user inputs such as brand, year, fuel type, transmission, and more.

Built using Python, Scikit-learn, and Streamlit.

📌 Features
🔮 Real-time car price prediction
🎯 Simple and interactive UI using Streamlit
📊 Supports multiple input features:
Car brand
Manufacturing year
Kilometers driven
Fuel type
Seller type
Transmission
Owner type
Mileage
Engine capacity
Max power
Number of seats
🛠️ Tech Stack
Python
Pandas & NumPy
Scikit-learn
Streamlit
Pickle
📂 Project Structure
├── app.py               # Streamlit web application
├── model.pkl           # Trained machine learning model
├── Cardetails.csv      # Dataset
├── requirements.txt    # Dependencies
└── README.md
⚙️ Installation & Setup
1️⃣ Clone the repository
git clone https://github.com/ShivaDubey03/Car-Price-Prediction-ML-Model.git
cd Car-Price-Prediction-ML-Model
2️⃣ Install dependencies
pip install -r requirements.txt
3️⃣ Run the application
streamlit run app.py
📊 How It Works
User selects car details from the UI
Input data is preprocessed and encoded
The trained ML model predicts the price
Predicted price is displayed instantly
