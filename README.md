# 🥗 Diet Zen

**Diet Zen** is a personalized web app that generates daily diet plans based on user input such as age, gender, height, weight, activity level, and fitness goals. It focuses on Indian food items and offers simple, goal-oriented meal suggestions.

## 🌟 Features

- 📊 Calculates BMI and daily calorie requirements
- 🎯 Supports weight loss, gain, and maintenance goals
- 🍛 Recommends Indian meals based on nutritional needs
- 🔄 Option to shuffle specific food items for alternatives

## 🧠 How It Works

- Collects basic user info and health goals
- Calculates daily caloric needs using standard formulas
- Applies a **subset-sum-based approach** to match food items to target calories
- Outputs a full meal plan using Indian food combinations

## 🛠 Tech Stack

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Python (Flask)
- **Algorithm:** Subset Sum for food item selection
- **Data:** Custom-built Indian food dataset with nutritional info

## 🚀 Getting Started

1. Clone the repository  
   ```bash
   git clone https://github.com/Vaishnavi0805/Diet-Zen.git
   cd diet-zen
2. Install dependencies
   pip install -r requirements.txt
3. Run the app locally
   python app.py
4. Open your browser at
   http://localhost:5000/
   
## Deployment Link
   Deployed to [render](https://diet-zen.onrender.com/)
