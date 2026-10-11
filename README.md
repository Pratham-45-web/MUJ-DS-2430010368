# AI-Based Classroom Noise Source Detection and Classification Using Deep Learning

## Student Information
- **Name:** Pratham Varshney
- **Registration Number:** 2430010368
- **Branch:** B.Tech CSE (Data Science)
- **Batch:** F
- **GitHub Username:** Pratham-45-web
- **Training Program:** Batch F – Capstone Project Training

## Project Overview
This project explores classifying environmental sounds relevant to a classroom setting using audio features and deep-learning models. The current experiment uses eight selected categories from the ESC-50 environmental sound dataset.

## Selected Classes
Breathing, clapping, coughing, door wood knock, footsteps, keyboard typing, laughing, and mouse click.

## Technologies
Python, TensorFlow/Keras, Librosa, NumPy, Pandas, Scikit-learn, Matplotlib, Seaborn, and Google Colab.

## Dataset
ESC-50: https://github.com/karolpiczak/ESC-50
Review the dataset licence and terms before redistributing any dataset content. The dataset is not included in this repository.

## Experimental Results
| Metric | CNN baseline | MobileNetV2 |
|---|---:|---:|
| Accuracy | 18.75% | 67.19% |
| Precision (weighted) | 20.44% | 72.25% |
| Recall (weighted) | 18.75% | 67.19% |
| F1 score (weighted) | 12.30% | 67.21% |

These values describe the current 64-example test split and are not a guarantee of performance on real-world classroom recordings.

## Repository Structure
- `assignments/` — Batch F assignments
- `notebooks/` — Colab/Jupyter notebooks
- `code/` — Python source code
- `resources/` — Dataset links and references
- `presentations/` — Project presentation
- `capstone/` — Documentation, screenshots and results

## How to Run
1. Open the notebook in Google Colab.
2. Download ESC-50 from the dataset link above.
3. Follow the notebook's preprocessing, feature extraction and training steps.
4. Train the model or load a compatible saved model.
5. Evaluate the model and test sound classification.

## Limitations
Only eight ESC-50 categories are used; the training set is small; performance on real classroom recordings has not yet been established.

## Future Work
Collect more classroom-specific recordings, test on unseen environments, and explore real-time inference.

## Individual Contribution
Update this section to accurately describe your own work, including dataset preparation, feature extraction, model development, evaluation, documentation and testing.
