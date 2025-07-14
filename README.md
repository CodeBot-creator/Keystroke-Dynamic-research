😌 Multimodal Stress Detection & Recommendation System (Keystroke Module)<br>
📌 Keystroke Dynamics Overview
This module captures users' typing behavior to detect stress in real-time using machine learning techniques.

It is designed to support:

Workplace typing pattern analysis

Mental state monitoring through keyboard usage

Research in behavioral biometrics

🧠 How It Works – Keystroke Monitoring
🧑‍💻 Typing Behavior Analysis

Captures typing features like hold time, flight time, typing speed, and error rate during user sessions.

Uses these features to recognize stress-induced typing variations.

📊 Model Used

A Random Forest classifier (or LSTM for time-series experiments) trained on labeled keystroke data (stressed vs relaxed).

Achieves real-time classification based on subtle behavioral shifts in typing patterns.

✅ Output

Predicts user’s stress level continuously during typing sessions.

Can integrate with other modules (e.g., facial recognition or chatbot) for deeper insights and responses.
