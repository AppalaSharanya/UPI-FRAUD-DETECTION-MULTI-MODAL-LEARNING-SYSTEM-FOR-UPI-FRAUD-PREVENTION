🛡️ UPI Fraud Detection & Multi-Modal Learning System
A simple web app that predicts whether a UPI transaction is fraudulent or safe, using a trained LSTM model and Flask-based frontend.

⚙️ Features
📊 Takes user input like transaction amount, device type, IP/location change, etc.

🤖 Uses a pre-trained LSTM model for fraud detection

🧠 Multi-modal design approach (backend + frontend)

🎨 Responsive UI with fraud/safe result display

🧪 Inputs Required
Transaction Amount

Device Type

IP Change Flag

Location Change Flag

Multiple Quick Transactions

Hour of Transaction

Day of the Week

🚀 How to Run
Install dependencies:

bash
Copy
Edit
pip install flask numpy joblib
Make sure your .pkl model is correctly loaded in the script.

Run the app:

bash
Copy
Edit
python app.py
Open in browser:

cpp
Copy
Edit
http://127.0.0.1:5000/
