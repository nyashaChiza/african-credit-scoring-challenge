### README: African Credit Scoring Challenge

#### **Project Overview**
This repository is designed for the African Credit Scoring Challenge, where the goal is to develop a machine learning model that predicts credit risk, improving access to financial services.

#### **Repository Structure**
- **`data/`**  
  - `raw/`: Stores the original dataset files.  
  - `processed/`: Contains processed iterations of the data for modeling.  
- **`models/`**: Stores trained model files.  
- **`pipelines/`**: Contains serialized preprocessing and modeling pipelines (`.pkl` files).  
- **`scripts/`**: Holds Python scripts for various tasks.  
- **`notebooks/`**: Jupyter notebooks for exploration, analysis, and experiments.  
- **`main.py`**: A FastAPI application for serving the trained model.  

#### **Problem Statement**
Predict customer credit risk using anonymized financial data, enabling financial institutions to assess creditworthiness accurately.

#### **Solution Approach**
- Perform **Exploratory Data Analysis (EDA)** to understand data distribution and relationships.  
- Engineer meaningful features and preprocess data.  
- Train and optimize machine learning models.  
- Deploy the final model using **FastAPI** for real-time scoring.  

#### **How to Run the Application**
1. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```
2. Start the FastAPI application:  
   ```bash
   uvicorn main:app --reload
   ```
3. Access the API at `http://127.0.0.1:8000` for predictions.  

#### **Contact**  
Feel free to reach out for contributions or queries!