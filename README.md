  AI  based  Phishing  link  detection

Welcome to the **Phishing URL Detection** project! This AI  powered system helps detect whether a given URL is legitimate or a phishing attempt using machine learning models trained on real  world data.
      

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

![image alt](https://github.com/ShakibAhmed1230/AI-based-Phishing-link-detection/blob/main/Diagram.png?raw=true)
     
3. Model predicts:
   * Phishing` or Legitimate`
   * Shows probability
     
4. Log saved in Excel DB with timestamp and result.

      

 🧠 Machine Learning Models


  ![image alt](https://github.com/ShakibAhmed1230/AI-based-Phishing-link-detection/blob/main/Screenshot%20(191).png?raw=true)
      

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
BSc in CSE | AI Researchee & Developer 

      

   📬 Contact

Email: [shakibahmedcse@gmail.com]


      

> "Securing the web one click at a time with intelligent, real  time AI."

      
