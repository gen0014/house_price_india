# House Price Prediction App

This is a simple Streamlit-based web application that predicts house prices using a machine learning model.

## 🚀 Features

- User-friendly interface for inputting house features
- Machine learning model for predicting house prices
- Deployed on **GitHub** and **Hugging Face**

## 🛠 Installation

### 1️⃣ Clone the Repository

```sh
git clone https://github.com/your-username/house_price_india.git
cd ML_Projects
```

### 2️⃣ Install Dependencies

```sh
pip install -r requirements.txt
```

### 3️⃣ Run the Streamlit App

```sh
streamlit run app.py
```

---

## 📂 File Structure

```
ML_Projects/
│-- app.py               # Streamlit application
│-- model.pkl            # Trained machine learning model
│-- requirements.txt      # List of dependencies
│-- README.md            # Project documentation
```

## 🌍 Deploying on GitHub

### 1️⃣ Initialize Git Repository

```sh
git init
git add .
git commit -m "Initial commit"
```

### 2️⃣ Push to GitHub

```sh
git remote add origin https://github.com/your-username/house_price_india.git
git branch -M main
git push -u origin main
```

## 🤗 Deploying on Hugging Face Spaces

### 1️⃣ Install Hugging Face CLI (if not installed)

```sh
pip install huggingface_hub
```

### 2️⃣ Login to Hugging Face

```sh
huggingface-cli login
```

### 3️⃣ Create a New Space on Hugging Face

1. Go to [Hugging Face Spaces](https://huggingface.co/spaces)
2. Click **"Create New Space"**
3. Set:
   - **Space Name:** House-Price-Prediction
   - **SDK:** Streamlit
   - **Visibility:** Public or Private
   - **Create Repository**

### 4️⃣ Clone Hugging Face Space

```sh
git clone https://huggingface.co/spaces/your-username/House-Price-Prediction
cd House-Price-Prediction
```

### 5️⃣ Copy Your Files to the Space

```sh
cp -r ../ML_Projects/* .
```

### 6️⃣ Push to Hugging Face

```sh
git add .
git commit -m "Deploying to Hugging Face"
git push
```

Your app will be deployed at:

```
https://huggingface.co/spaces/your-username/House-Price-Prediction
```

## ✨ Usage

1. Open the app in a browser.
2. Enter house details (bedrooms, bathrooms, living area, etc.).
3. Click **Predict!** to see the estimated price.


## 🤝 Contributing

Feel free to **fork**, **clone**, and submit **pull requests**!

---

## 📞 Contact

For any queries, reach out via GitHub or Hugging Face.

live demo - https://huggingface.co/spaces/genuu/House-Price-Prediction
---

🚀 Happy Coding!

