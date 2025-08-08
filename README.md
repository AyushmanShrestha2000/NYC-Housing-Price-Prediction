# New York Housing Price Prediction

# Project Overview
This project uses machine learning to estimate pricing of properties in New York. The final model analyzes different property features (property size, room count, location) from a Kaggle dataset. From different models, Random Forest performed the best. The model includes interactive dashboard for getting price estimates.

# Features 
- Interactive Dashboard
- Data Exploration
- Market Analysis
- Model Training
- Price Prediction

# Technologies Used: Python, Streamlit
- Streamlit
- Python
- Machine Learning: Scikit-learn, XGBoost
- Data Visualization: Matplotlib, Seaborn
- Data Processing: Pandas, NumPy

# Installation 
Clone the repository:
   ```bash
   git clone https://github.com/AyushmanShrestha2000/NYC-Housing-Price-Prediction
   cd ny-housing-price-prediction

#Install dependencies:
pip install -r requirements.txt

#Download the dataset:
Place NY-House-Dataset.csv in the project root directory

#Run the application:
streamlit run app.py

#File Structure 
ny-housing-price-prediction/
├── app.py                # Main Streamlit application
├── NY-House-Dataset.csv  # Housing dataset 
├── README.md             # This file
├── requirements.txt      # Python dependencies

Data source: [Kaggle New York Housing Market](https://www.kaggle.com/datasets/nelgiriyewithana/new-york-housing-market?resource=download)
