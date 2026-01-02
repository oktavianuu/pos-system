pos-system/
│
├── README.md
├── pyproject.toml / requirements.txt
│
├── app/
│   ├── main.py
│   ├── config.py
│   │
│   ├── core/
│   │   ├── database.py
│   │   ├── security.py
│   │   ├── logging.py
│   │   └── exceptions.py
│   │
│   ├── models/
│   │   ├── user.py
│   │   ├── branch.py
│   │   ├── product.py
│   │   ├── inventory.py
│   │   ├── inventory_log.py
│   │   ├── transaction.py
│   │   └── transaction_item.py
│   │
│   ├── schemas/
│   │   ├── user.py
│   │   ├── product.py
│   │   ├── transaction.py
│   │   └── inventory.py
│   │
│   ├── services/
│   │   ├── transaction_service.py
│   │   ├── inventory_service.py
│   │   ├── pricing_service.py
│   │   └── report_service.py
│   │
│   ├── api/
│   │   ├── auth.py
│   │   ├── products.py
│   │   ├── transactions.py
│   │   ├── inventory.py
│   │   └── reports.py
│   │
│   └── utils/
│       ├── time.py
│       ├── constants.py
│       └── validators.py
│
├── frontend/
│   ├── templates/
│   │   ├── login.html
│   │   ├── cashier.html
│   │   ├── inventory.html
│   │   └── reports.html
│   │
│   └── static/
│       ├── css/
│       └── js/
│
├── scripts/
│   ├── init_db.py
│   ├── backup_db.py
│   └── restore_db.py
│
├── data_science/
│   ├── notebooks/
│   │   ├── sales_analysis.ipynb
│   │   ├── inventory_anomaly.ipynb
│   │   └── demand_forecasting.ipynb
│   │
│   ├── datasets/
│   │   └── exported_transactions.csv
│   │
│   └── feature_engineering.py
│
├── tests/
│   ├── test_transactions.py
│   ├── test_inventory.py
│   └── test_reports.py
│
└── docs/
    ├── architecture.md
    ├── data_dictionary.md
    └── decisions.md
