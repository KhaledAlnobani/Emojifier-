# Emojifier

A simple emoji prediction project that maps short text sentences to one of five emoji classes using pre-trained GloVe word embeddings.

This repository includes two modeling approaches:

- **Average embedding + softmax classifier** (fast, low-data friendly)
- **LSTM sequence model** (more expressive, needs more data and tuning)

---

## ✅ What’s Included

- `main.ipynb` – interactive notebook with data exploration, model training, and visualization.
- `emo_utils.py` – utility functions for data loading, feature creation, model training/evaluation, and plotting.
- `data/` – data files used for training and testing (CSV datasets + GloVe embeddings).

---

## � Acknowledgements

This project is based on concepts from th **Deep Learning Specialization**  
> https://learn.deeplearning.ai/specializations
