Dataset link: https://www.kaggle.com/competitions/ieee-fraud-detection/data

Cấu trúc dự án:
Tên dự án/
├── data/                         
│   ├── raw/                      # các file CSV  gốc
│   ├── processed/            # dữ liệu sau xử lý : train.csv, test.csv
│   └── sample/                 # dữ liệu mẫu để demo
├── docs/ 		           # các file tài liệu cho dự án
├── notebooks/                  # các file notebooks 
│   ├── 01_data_understanding.ipynb     # Đọc CSV, khảo sát dữ liệu
│   ├── 02_postgresql_pipeline.ipynb    #PostgreSQL, Import dữ liệu, Join, Aggregation
│   ├── 03_data_cleaning.ipynb             # Missing values ,Outliers 
│   ├── 04_eda_visualization.ipynb       # eda , Visualization
│   ├── 05_feature_engineering.ipynb  # 10 feature mới , trực quan, rút insight
│   ├── 06_machine_learning.ipynb    # Train/Test , So sánh model
│   ├── 07_prediction_demo.ipynb     # Load model , Dự đoán
├── sql/                                                 # các SQL (tạo bảng, view, import data)
│   ├── 01_create_tables.sql
│   ├── 02_import_data.sql
│   ├── 03_views.sql
│   ├── 04_aggregation.sql
│   └── 05_indexes.sql
├── prompts/                   # các file prompts  
├── app/                           # Code ứng dụng web (Streamlit + FastAPI)
│   ├── streamlit_app.py
│   ├── api.py
│   ├── utils
│   ├── pages/
│   └── prediction.py
├── models/                      # File mô hình đã train (.pkl)
│   ├── model.pkl
│   └── scaler.pkl
├── reports/                      # Báo cáo Word, PPTX và hình ảnh
│   ├── tai-lieu-du-an-nhom-1.docx
│   ├── slide-du-an-nhom-1.pptx
│   └── images/
├── README.md            # Hướng dẫn chi tiết chạy dự án, cấu hình, cài đặt
├── Task_Tracker.xlsx      # phân công, theo dõi công việc
└── requirements.txt         # Danh sách thư viện
