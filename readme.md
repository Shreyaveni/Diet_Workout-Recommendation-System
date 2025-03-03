# Diet and Workout Recommendation System

## 📌 Overview
Diet and Workout Recommendation System is a Flask-based web application that generates **personalized diet and workout plans** using Google's **Gemini AI**. The system provides tailored recommendations based on user preferences, fitness goals, lifestyle, and dietary restrictions.

## 🚀 Features
- 🔹 AI-powered diet and workout suggestions  
- 🔹 Custom meal and fitness plans based on user input  
- 🔹 Dynamic meal recommendations (breakfast, dinner, snacks, hydration tips)  
- 🔹 Flask-based web interface  
- 🔹 Waitress server for production deployment  

## 🛠️ Installation  

### 1️⃣ Clone the Repository  
```sh
git clone https://github.com/your-username/diet-workout-recommendation.git
cd diet-workout-recommendation
```

### 2️⃣ Install Dependencies  
Create a `requirements.txt` file with the following content:
```sh
Flask
dotenv
waitress
google-generativeai
```
Then, install the dependencies:
```sh
pip install -r requirements.txt
```

### 3️⃣ Set Up API Key  
Create a `.env` file and add:  
```sh
GOOGLE_API_KEY=your_google_gemini_api_key
```

### 4️⃣ Run the Application  
```sh
python app.py
```
Access the web app at `http://127.0.0.1:5000/`

## 📌 Tech Stack  
- **Backend:** Flask, Google Gemini AI  
- **Frontend:** HTML, Jinja2  
- **Deployment:** Waitress (for production)  

