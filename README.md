Marathi Hate Speech Detection using MuRIL and DAPT-MuRIL
Overview
This project focuses on detecting hate speech in Marathi social media content using state-of-the-art Transformer models. The system compares the performance of the baseline MuRIL model with a Domain Adapted MuRIL (DAPT-MuRIL) model to evaluate the impact of domain adaptation on Marathi hate speech classification.

The project aims to support safer online communities by automatically identifying potentially harmful and hateful Marathi-language content posted on social media platforms.

Objectives
Detect hate speech in Marathi text.
Perform domain adaptation using Marathi corpus datasets.
Fine-tune Transformer models for hate speech classification.
Compare MuRIL and DAPT-MuRIL performance.
Evaluate models using standard classification metrics.
Datasets Used
1. MahaHate
Primary dataset used for hate speech classification.

2. MeCorpus
Used for Domain Adaptive Pretraining (DAPT).

3. Dakshina Dataset
Used to enrich Marathi language understanding during domain adaptation.

Project Workflow
Phase 1: Data Collection
MahaHate Dataset
MeCorpus Dataset
Dakshina Dataset
Phase 2: Data Preprocessing
Cleaning text
Removing null values
Label encoding
Dataset balancing
Phase 3: Domain Adaptive Pretraining (DAPT)
Marathi corpus creation
Further pretraining of MuRIL
Generation of DAPT-MuRIL
Phase 4: Fine-Tuning
MuRIL Fine-Tuning
DAPT-MuRIL Fine-Tuning
Phase 5: Evaluation
Accuracy
Precision
Recall
F1 Score
ROC-AUC
Phase 6: Comparative Analysis
MuRIL vs DAPT-MuRIL
Performance Visualization
Models
MuRIL
Multilingual Representation for Indian Languages developed by Google.

DAPT-MuRIL
Domain Adapted MuRIL created by further pretraining MuRIL on Marathi corpora before fine-tuning on the hate speech dataset.

Technologies Used
Python
Pandas
NumPy
Scikit-Learn
PyTorch
Hugging Face Transformers
Matplotlib
Seaborn
Jupyter Notebook / Kaggle Notebook
Evaluation Metrics
The following metrics were used:

Accuracy
Precision
Recall
F1 Score
ROC-AUC Score
Confusion Matrix
Generated Outputs
Training Loss Curve
Validation Accuracy Curve
Validation F1 Curve
ROC Curve
Confusion Matrix
Model Comparison Graph
Sample Predictions
Project Structure
Marathi-Hate-Speech-Detection/
│
├── notebook.ipynb
├── README.md
├── requirements.txt
│
├── data/
│   ├── MahaHate.csv
│   ├── MeCorpus.csv
│   └── Dakshina.csv
│
├── models/
│   ├── MuRIL/
│   └── DAPT-MuRIL/
│
├── outputs/
│   ├── confusion_matrix.png
│   ├── roc_curve.png
│   ├── loss_curve.png
│   ├── accuracy_curve.png
│   ├── f1_curve.png
│   └── comparison_graph.png
│
└── report/
    └── Project_Report.pdf
Sample Results
Model	Accuracy	F1 Score	ROC-AUC
MuRIL	XX.XX%	XX.XX	XX.XX
DAPT-MuRIL	XX.XX%	XX.XX	XX.XX
Replace the above values with your actual experimental results.

Future Work
Real-time hate speech detection.
Social media integration.
Browser extension deployment.
Multi-class offensive language detection.
Support for additional Indian languages.
Author
Rutvik Makarand Gokhale

M.Tech (AI & ML)

Manipal Institute of Technology

License
This project is intended for academic and research purposes.
