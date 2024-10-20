# data-extraction-from-invoice
Project on Invoice Data Extraction from custom dataset using Document OCR models and Vision-Language Models


invoice-data-extraction/
│
├── README.md                 # Overview of the project
├── requirements.txt          # List of all dependencies and libraries
├── setup.py                  # Package configuration if necessary
├── LICENSE                   # License for your repository
├── .gitignore                # Ignored files
│
├── data/                     # Folder for dataset (invoice PDFs)
│   ├── raw/                  # Raw PDF files
│   ├── processed/            # Processed/cleaned files
│
├── src/                      # Source code folder
│   ├── preprocessing/        # Preprocessing scripts (conversions, OCR, etc.)
│   ├── extraction/           # Data extraction logic
│   ├── models/               # Trained model files or scripts for training models
│   ├── evaluation/           # Scripts for accuracy checking, trust determination
│   ├── utils/                # Utility functions and helpers
│
├── notebooks/                # Jupyter notebooks for experimentation
│
├── tests/                    # Unit and integration tests
│
└── docs/                     # Documentation folder
    └── report.md             # Detailed technical report, accuracy breakdown, etc.

