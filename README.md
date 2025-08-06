


## Features 
- **Interactive Dashboard**: Beautifully designed UI with custom styling
- **Data Exploration**: 
  - Dataset overview with statistics
  - Missing value analysis
  - Correlation matrices
- **Market Analysis**:
  - Price distribution visualizations
  - Feature vs price relationships
- **Model Training**:
  - Multiple ML models (Linear Regression, Random Forest, XGBoost)
  - Performance metrics comparison
- **Price Prediction**:
  - Interactive input form
  - Instant price estimation


## Technologies Used:
- **Frontend**: Streamlit
- **Backend**: Python
- **Machine Learning**:
  - Scikit-learn
  - XGBoost
- **Data Visualization**:
  - Matplotlib
  - Seaborn
- **Data Processing**: Pandas, NumPy

## Installation 
Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ny-housing-price-prediction.git
   cd ny-housing-price-prediction


##Create and activate a virtual environment:
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`


##Install dependencies:
pip install -r requirements.txt


##Download the dataset:
Place NY-House-Dataset.csv in the project root directory


##Run the application:
streamlit run app.py


##File Structure 
ny-housing-price-prediction/
├── app.py                # Main Streamlit application
├── NY-House-Dataset.csv  # Housing dataset 
├── README.md             # This file
├── requirements.txt      # Python dependencies             
