# Streamlit_timeanlytics
🕒 Timelytics: Order to Delivery Time Prediction 🚀
📌 Project Overview
Timelytics is an advanced Order to Delivery (OTD) time prediction model that utilizes an ensemble of XGBoost, Random Forests, and Support Vector Machines (SVM) to accurately forecast delivery times.
This project helps businesses optimize their supply chain operations by identifying potential bottlenecks and reducing lead times.

📊 Features
✅ User-friendly Web Interface using Streamlit
✅ Predict Order Delivery Time based on order details
✅ Machine Learning Model trained using ensemble methods
✅ Real-world Business Use Case for logistics & supply chain management

🛠️ Tech Stack
Python 🐍
Streamlit 🎨 (For Web App Deployment)
Machine Learning (XGBoost, Random Forest, SVM)
NumPy & Pandas (For Data Processing)
Pickle (For Model Serialization)
🔧 Installation Guide
1️⃣ Clone the Repository
[https://github.com/devaldaki3/ai_project](https://github.com/PratikGohel12/Streamlit_timeanlytics)
2️⃣ Install Required Dependencies
pip install -r requirements.txt
🚀 How to Run the App
1️⃣ Ensure the Trained Model Exists
Make sure the xgboost_otd_model.pkl file is in the model folder. If not, train the model first using train_model.py.

2️⃣ Run the Streamlit App
streamlit run app.py
This will start a local web server, and you can access the app in your browser.

🎯 How to Use the App
1️⃣ Open the App in your browser.
2️⃣ Input Order Details (e.g., product size, weight, location, distance).
3️⃣ Click "Predict" to get the estimated delivery time.
4️⃣ See the Predicted Delivery Time displayed on the screen.

📊 Model Information
Trained on: Historical order delivery data
Algorithms used: XGBoost, Random Forest, SVM
Final Model: Voting Ensemble (xgboost_otd_model.pkl)
