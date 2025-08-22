# **StyleGrade 👗**  
*A clothing recommendation and rating prediction web app built using Streamlit and Machine Learning.*

---

## 📌 **Overview**
**StyleGrade** predicts whether a clothing item will be rated as **GOOD 😊**, **OKAY 😐**, or **BAD 😞** based on various fashion attributes such as gender, category, color, season, and usage. The application uses a trained machine learning model deployed with **Streamlit** for an interactive user experience.

---

## ✨ **Features**
✅ Select clothing attributes (gender, category, color, etc.)  
✅ Predicts rating instantly as **GOOD**, **OKAY**, or **BAD**  
✅ Built using **Logistic Regression** for classification  
✅ Intuitive and stylish UI built with **Streamlit**  
✅ Real-time predictions without page refresh  

---

## 🛠 **Tech Stack**
- **Frontend:** Streamlit
- **Backend:** Python
- **ML Model:** Logistic Regression (scikit-learn)
- **Data Processing:** Pandas, NumPy
- **Deployment:** Streamlit

---

## 📂 **Project Structure**
```
StyleGrade/
├── app.py                # Main Streamlit app
├── requirements.txt      # Dependencies
├── LabelEncoder.pkl      # Saved encoders for categorical features
├── SIBTC_model.pkl       # Trained ML model
├── Labeled_fashion_data.csv # Dataset (if included)
```

---

## ▶️ **How to Run the App Locally**
1. **Clone the repository**
   ```bash
   git clone https://github.com/<your-username>/StyleGrade.git
   cd StyleGrade
   ```

2. **Create and activate a virtual environment**
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Streamlit app**
   ```bash
   streamlit run app.py
   ```

5. **Access the app**
   ```
   http://localhost:8501
   ```

---

## 🧠 **How It Works**
- The app uses **Label Encoding** for categorical variables like gender, category, and season.
- Inputs are transformed into numerical format before prediction.
- The ML model predicts one of three labels: **GOOD**, **OKAY**, or **BAD**.

---

## 📊 **Sample Input Parameters**
- **Gender:** Male / Female
- **Master Category:** Apparel / Accessories
- **Sub Category:** T-Shirts / Shoes / Bags
- **Article Type:** Sports Shoes / Casual Shirt
- **Base Colour:** Blue / Black / Red
- **Season:** Summer / Winter
- **Year:** 2012
- **Usage:** Casual / Sports

---

## 🔮 **Future Enhancements**
- Deploy on **Streamlit Cloud** or **Render**
- Add image-based prediction using **CNN**
- Add **user profiles** and **favorites**
- Implement **recommendation system**
- Link this to online shopping sites/apps

---


## 📜 **License**
This project is licensed under the MIT License.

---

## 🤝 **Contributing**
Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.
