# 🚗 Used Car Price Prediction

A Machine Learning project that predicts the market price of used cars
based on features like brand, year, kilometers driven, fuel type, and more.

## 📁 Project Structure
- `PROJECTAI.ipynb` → Main ML notebook (EDA, model training, evaluation)
- `app.py`          → Streamlit web app for price prediction
- `car_details_v4_1.csv` → Dataset (2059 used car listings)

## 🧠 Models Used
| Model | R2 Score |
|-------|----------|
| Random Forest | 0.818 |
| Polynomial Regression | 0.810 |
| Decision Tree | 0.799 |
| Multiple Linear Regression | 0.713 |
| Simple Linear Regression | 0.001 |
| Support Vector Regression | -0.116 |

## ✅ Best Model
**Random Forest Regression** with R² = 0.818

## 🛠️ Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Streamlit

## 🚀 How to Run
1. Install dependencies:
   pip install pandas numpy scikit-learn matplotlib seaborn streamlit
2. Run the notebook:
   Open PROJECTAI.ipynb in Jupyter
3. Run the web app:
   streamlit run app.py

## 📊 Dataset
2059 used car listings with features:
Make, Model, Year, Kilometer, Fuel Type, Transmission,
Engine, Max Power, Max Torque, Location, Owner, and more.
```

---

### Step 7 — Create a `.gitignore` file (optional but good practice)

In your project folder, create a file named **`.gitignore`** and write:
```
__pycache__/
*.pkl
.ipynb_checkpoints/
.env
