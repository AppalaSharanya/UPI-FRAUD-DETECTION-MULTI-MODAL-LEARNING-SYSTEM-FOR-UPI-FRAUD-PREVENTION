# 🛡️ UPI Fraud Detection & Multi-Modal Learning System

🔍 About the Project
This project aims to detect fraudulent UPI (Unified Payments Interface) transactions using a deep learning-based approach. It combines behavioral features like transaction time, device type, and quick repeat transactions with an LSTM model to predict the likelihood of fraud in real-time.

The application includes a minimal and intuitive Flask-based frontend, allowing users to input transaction details and receive instant feedback on whether the transaction is potentially fraudulent or safe. The system demonstrates how machine learning can be integrated into financial systems for real-time fraud detection and prevention.

🚀 Features
🧠 LSTM-based Fraud Prediction
Uses a trained LSTM model to analyze transaction patterns and detect suspicious activity.

🎨 Interactive Web Interface
Clean, user-friendly UI built with HTML & CSS inside Flask for easy input and real-time results.

📥 Inputs Considered

Transaction Amount

Device Type

IP Address Change Flag

Location Change Flag

Multiple Quick Transactions

Hour of the Day

Day of the Week

⚠️ Instant Result Display
Shows prediction as Fraudulent (in red) or Safe (in green) based on model output.

🛡️ Focused on UPI-specific Behavior
Designed to mimic real-life UPI fraud patterns like unusual hours, device swaps, and IP/location changes.
