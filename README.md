  __AI  based  Phishing  link  detection__


  

Welcome to the **Phishing URL Detection** project! This AI  powered system helps detect whether a given URL is legitimate or a phishing attempt using machine learning models trained on real  world data
      

   __🔍 Project Description__

This project is a complete prototype that uses advanced feature engineering techniques and machine learning algorithms (CatBoost, XGBoost, Deep Neural Networks) to classify URLs as *phishing* or *legitimate*. It also includes a live web interface for real  time predictions and stores each search log for analysis.

      

   __📌 Key Features__

* Real  time URL analysis
* Chrome extension and Flask  based web deployment
* Logs all user inputs, predictions, and processing time
* Advanced models like CatBoost, XGBoost, Deep NN
* Feature  based detection using entropy, digits, subdomains, and more
* Graphical probability result + log database viewer

      

   __🚀 Demo Screenshots__





**1/1**
![image alt](https://github.com/ShakibAhmed1230/AI-based-Phishing-link-detection/blob/main/Screenshot%20(188).png?raw=true)



**1/2**
![image alt](https://github.com/ShakibAhmed1230/AI-based-Phishing-link-detection/blob/main/Screenshot%20(189).png?raw=true )








**2**  
  
![image alt](https://github.com/ShakibAhmed1230/AI-based-Phishing-link-detection/blob/main/Screenshot%20(187).png?raw=true)
  




__🔗 Input Interface__



![input](https://github.com/ShakibAhmed1230/AI-based-Phishing-link-detection/blob/main/Screenshot%20(193).png?raw=true)

  **✅ Prediction Result**
    
 ![image alt](https://github.com/ShakibAhmed1230/AI-based-Phishing-link-detection/blob/main/Screenshot%20(184).png?raw=true)


   __⚙️ How It Works__

**1. User enters a URL via the web interface.**

__2. Features are extracted:__
   * URL Length
   * Digits Count
   * Special Characters
   * Entropy
   * Subdomain Count

![image alt](https://github.com/ShakibAhmed1230/AI-based-Phishing-link-detection/blob/main/Diagram.png?raw=true)
     
__3. Model predicts:__
   * Phishing` or Legitimate`
   * Shows probability
     
__4. Log saved in DB with timestamp and result.__


   ![image alt](https://github.com/ShakibAhmed1230/AI-based-Phishing-link-detection/blob/main/Screenshot%20(190).png?raw=true)

      

 __🧠 Machine Learning Models__


  ![image alt](https://github.com/ShakibAhmed1230/AI-based-Phishing-link-detection/blob/main/Screenshot%20(191).png?raw=true)
      

  __📦 Technologies Used__

* Python
* Flask
* Pandas
* Matplotlib
* Joblib
* CatBoost, XGBoost, Keras
* PyNgrok (for testing via tunnel)

      

__**📊 Log Management**__

All predictions are logged automatically to a timestamped Excel file with:

* Input URL
* Result
* Confidence Score
* Date & Time
* Processing Duration

 


**How to Run:**

bash

pip install   r requirements.txt

python copy_of_final_pproject.py


You will get a live URL from ngrok. Open in browser to test.

      

  __📌 Future Scope__

* Chrome Extension Deployment
* Mobile App Version
* Adversarial Training
* Feedback Loop Learning
* Integration into enterprise cybersecurity platforms

      

   __👨‍💻 Author__

**Shakib Ahmed**
BSc in CSE | AI Researcher & Developer 

      

   __📬 Contact__

**Email: [shakibahmedcse@gmail.com]**


      

> "Securing the web one click at a time with intelligent, real  time AI."

      
