# Laptop Price Prediction System

## 📌 Project Overview
The **Laptop Price Prediction System** is a machine learning application that predicts laptop prices based on key specifications such as brand, processor, RAM, storage, and display features. It utilizes a trained model to provide price estimates for different laptop configurations.

## 🚀 Features
- 📊 **Data Preprocessing**: Cleans and prepares the dataset for training.
- 🤖 **Machine Learning Model**: Implements a regression model to predict laptop prices.
- 🎯 **Feature Engineering**: Extracts meaningful features to improve model performance.
- 📈 **Model Evaluation**: Assesses the model's accuracy and performance metrics.
- 🖥️ **Web Interface**: Provides a simple UI for users to enter laptop specs and get price predictions.

## 🏗️ Tech Stack
- **Programming Language**: Python 🐍
- **Machine Learning Libraries**: Scikit-learn, Pandas, NumPy, Matplotlib, Seaborn
- **Web Framework**: Flask
- **Data Storage**: CSV Dataset

## 📁 Project Structure
```
Laptop-Price-Prediction/
│── app.py                 # Flask web application
│── model.py               # Machine learning model training and prediction
│── requirements.txt       # Required dependencies
│── static/
│   ├── styles.css         # CSS for UI
│── templates/
│   ├── index.html         # Web interface for user input
│── dataset/
│   ├── laptops.csv        # Dataset containing laptop specifications and prices
│── notebooks/
│   ├── exploratory_data_analysis.ipynb  # EDA and visualization
│   ├── model_training.ipynb             # Model training and evaluation
│── README.md              # Project documentation
```

## 🛠️ Installation & Setup
### 1️⃣ Clone the Repository
```sh
git clone https://github.com/your-username/laptop-price-prediction.git
cd laptop-price-prediction
```

### 2️⃣ Install Dependencies
```sh
pip install -r requirements.txt
```

### 3️⃣ Run the Application
```sh
python app.py
```
The application will run on **http://127.0.0.1:5000/**.

## 📊 Model Training
To train the model:
```sh
python model.py
```

## 📷 Screenshots
![Web Interface](static/screenshot.png)

## 📌 Future Improvements
- Enhance the model with deep learning techniques.
- Expand the dataset for better accuracy.
- Deploy the application online using AWS or Heroku.

## ✨ Contributors
- **Your Name** - Developer
- **Other Contributors** (if any)

## 📜 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
💡 *If you like this project, give it a ⭐ on GitHub!*

