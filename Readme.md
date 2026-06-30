Dataset link: https://www.kaggle.com/competitions/ieee-fraud-detection/data

## 📂 Project Structure

```text
IEEE-CIS-Fraud-Detection/
├── data/
│   ├── raw/               # Original CSV files
│   ├── processed/         # Cleaned data: train.csv, test.csv
│   └── sample/            # Sample data for demo
├── docs/                  # Project documentation
├── notebooks/             # Jupyter notebooks
│   ├── 01_data_understanding.ipynb     # Load CSV, basic exploration
│   ├── 02_postgresql_pipeline.ipynb    # PostgreSQL import, join, aggregation
│   ├── 03_data_cleaning.ipynb          # Handle missing values, outliers
│   ├── 04_eda_visualization.ipynb      # Exploratory analysis, visualization
│   ├── 05_feature_engineering.ipynb    # Create new features, insights
│   ├── 06_machine_learning.ipynb       # Train/Test, model comparison
│   └── 07_prediction_demo.ipynb        # Load model, prediction demo
├── sql/                   # SQL scripts
│   ├── 01_create_tables.sql
│   ├── 02_import_data.sql
│   ├── 03_views.sql
│   ├── 04_aggregation.sql
│   └── 05_indexes.sql
├── prompts/              # Prompt files
├── app/                  # Web app (Streamlit + FastAPI)
│   ├── streamlit_app.py
│   ├── api.py
│   ├── utils/
│   ├── pages/
│   └── prediction.py
├── models/               # Trained models (.pkl)
│   ├── model.pkl
│   └── scaler.pkl
├── reports/              # Reports and slides
│   ├── tai-lieu-du-an-nhom-1.docx
│   ├── slide-du-an-nhom-1.pptx
│   └── images/
├── README.md             # Project guide
├── Task_Tracker.xlsx     # Task assignment & tracking
└── requirements.txt      # Python dependencies
