  AI  based  Phishing  link  detection
  Phishing URL Detection System

Welcome to the **Phishing URL Detection** project! This AI  powered system helps detect whether a given URL is legitimate or a phishing attempt using machine learning models trained on real  world data.


 ![image alt](https://github.com/ShakibAhmed1230/AI-based-Phishing-link-detection/blob/main/Screenshot%20(193).png?raw=true)

      

   🔍 Project Description

This project is a complete prototype that uses advanced feature engineering techniques and machine learning algorithms (CatBoost, XGBoost, Deep Neural Networks) to classify URLs as *phishing* or *legitimate*. It also includes a live web interface for real  time predictions and stores each search log for analysis.

      

   📌 Key Features

* Real  time URL analysis
* Chrome extension and Flask  based web deployment
* Logs all user inputs, predictions, and processing time
* Advanced models like CatBoost, XGBoost, Deep NN
* Feature  based detection using entropy, digits, subdomains, and more
* Graphical probability result + log database viewer

      

   🚀 Demo Screenshots

  

  🔗 Input Interface

![input](https://github.com/ShakibAhmed1230/AI-based-Phishing-link-detection/blob/main/Screenshot%20(193).png?raw=true)

    ✅ Prediction Result





    📁 Log File Confirmation

![Log Saved](snaps/Screenshot%20\(188\).png)

    🔄 Backend Prediction Running

![Model Running](snaps/Screenshot%20\(189\).png)

    🎯 Final Result View

![Success](snaps/Screenshot%20\(190\).png)

      

   ⚙️ How It Works

1. User enters a URL via the web interface.
2. Features are extracted:

   * URL Length
   * Digits Count
   * Special Characters
   * Entropy
   * Subdomain Count
3. Model predicts:

   * Phishing` or Legitimate`
   * Shows probability
4. Log saved in Excel DB with timestamp and result.

      

 🧠 Machine Learning Models

| Model    | Accuracy | F1 Score | ROC AUC |
|                  |                  |                 
| CatBoost | 87.01%   | 0.8113   | 0.9147  |
| XGBoost  | 85.12%   | 0.7942   | 0.9025  |
| Deep NN  | 82.43%   | 0.7811   | 0.8894  |

      

   📦 Technologies Used

* Python
* Flask
* Pandas
* Matplotlib
* Joblib
* CatBoost, XGBoost, Keras
* PyNgrok (for testing via tunnel)

      

📁 Project Structure

project/
├── phishing_model.pkl
├── copy_of_final_pproject.py
├── templates/
│   └── index.html
├── phishing_logs_<timestamp>.xlsx
├── snaps/
│   ├── Screenshot (180).png
│   ├── Screenshot (181).png
│   ├── ...
```

      

📊 Log Management

All predictions are logged automatically to a timestamped Excel file with:

* Input URL
* Result
* Confidence Score
* Date & Time
* Processing Duration

  <img width="1366" height="768" alt="Screenshot (190)" src="https://github.com/user-attachments/assets/4c2e5f2d-d1e1-41ee-9edb-2d37ba2e6d75" />


How to Run

bash
pip install   r requirements.txt
python copy_of_final_pproject.py


You will get a live URL from ngrok. Open in browser to test.

      

   📌 Future Scope

* Chrome Extension Deployment
* Mobile App Version
* Adversarial Training
* Feedback Loop Learning
* Integration into enterprise cybersecurity platforms

      

   👨‍💻 Author

**Shakib Ahmed**
BSc in CSE | AI Researcher | Cybersecurity Enthusiast

      

   📬 Contact

Email: [shakibahmedcse@gmail.com](mailto:shakibahmedcse@gmail.com)
GitHub: \[Your GitHub link]
LinkedIn: \[Your LinkedIn link]

      

> "Securing the web one click at a time with intelligent, real  time AI."

      
