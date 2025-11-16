# AI Safety classifier
A lightweight machine-learning project designed to classify whether a given prompt is safe or unsafe for AI systems. This repository helps developers integrate basic AI-safety checks into their applications, preventing harmful or unsafe content from being processed.

-> Features

Binary Classification — Classifies text as safe or unsafe.

 ML Model Training — Customizable training pipeline.

 Preprocessing Tools — Tokenization, cleaning, and dataset handling.

 Evaluation Metrics — Accuracy, precision, recall, F1-score plots.

 Modular Codebase — Easy to extend (add more classes, models, datasets).

 AI-Safety-Classifier

├── dataset/              # Training and testing datasets
├── models/               # Saved models
├── src/
│   ├── preprocess.py     # Text preprocessing pipeline
│   ├── train.py          # Model training script
│   ├── evaluate.py       # Evaluation functions and metrics
│   ├── predict.py        # Inference script for new text
│   └── utils.py          # Helper functions
│
├── requirements.txt      # Required Python libraries
└── README.md             # Project documentation
