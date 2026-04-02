### MIND-News-Recommendation-System
#### Directory Structure

mind-recommender/
├── data/
│   ├── MINDsmall_train/
│   │   ├── behaviors.tsv
│   │   ├── news.tsv
│   │   ├── entity_embedding.vec
│   │   └── relation_embedding.vec
│   ├── MINDsmall_dev/
│   │   └── (same files as train)
│   └── glove/
│       └── glove.6B.300d.txt
├── src/
│   ├── data_loader.py
│   ├── news_encoder.py
│   ├── user_encoder.py
│   ├── model.py
│   ├── train.py
│   └── evaluate.py
├── notebooks/
│   ├── 01_eda.ipynb
│   ├── 02_preprocessing.ipynb
│   └── 03_training.ipynb
├── models/          (saved model checkpoints)
├── results/         (evaluation outputs)
└── README.md
