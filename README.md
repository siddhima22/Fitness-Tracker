# Fitness-Tracker

A personal fitness web app built using **Streamlit** and **Machine Learning** to predict **calories burned** during exercise based on user parameters such as age, gender, BMI, duration, heart rate, and body temperature.Preprocessing data with BMI calculation, one-hot encoding. It compares user metrics with the dataset, calculates similarity percentages and displays users with similar characteristics based on the predicted calorie range.




## 🚀 Features

- 🔢 Predict calories burned using a trained **Random Forest Regressor**
- 🎛️ Interactive sliders and radio buttons for user input
- 📊 Real-time insights on how your stats compare to others
- 🔍 Shows similar cases from the dataset
- 📈 Visualization of prediction progress for better UX



## 🧠 How It Works

- Combines two datasets: `exercise.csv` and `calories.csv`
- Calculates **BMI** from weight and height
- Uses one-hot encoding for gender
- Trains a Random Forest Regressor on historical data
- Predicts calories burned using the model
- Compares your data against others for context



## ⚙️ Technologies Used

- **Python**
- **Streamlit** (for the web app UI)
- **Pandas**, **NumPy** (for data manipulation)
- **Scikit-learn** (for ML modeling)
- **Matplotlib**, **Seaborn** (for data visualization)



## 🧪 Input Parameters

- Age
- BMI
- Duration of exercise
- Heart rate
- Body temperature
- Gender




## 📬 Contact
If you liked this project, have any queries or want to collaborate feel free to reach out! email: siddhimade@gmail.com

