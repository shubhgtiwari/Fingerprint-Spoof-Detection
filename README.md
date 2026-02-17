#  Fingerprint Spoof Detection (LBP + HOG)

A machine learning-based fingerprint liveness detector that distinguishes **live fingers from spoofs** using Local Binary Patterns (LBP) and Histogram of Oriented Gradients (HOG) features.

##  Problem

Fake fingers fabricated from latex, silicone, or gelatin can achieve up to **70% spoof attack success rate** on fingerprint sensors. This project builds a countermeasure classifier.

##  Methodology

1. **Feature Extraction:**
   - **LBP (Local Binary Patterns)** — texture-based descriptor
   - **HOG (Histogram of Oriented Gradients)** — shape-based descriptor
2. **Classification:** ML classifiers to distinguish live vs spoof
3. **Evaluation:** Accuracy, precision, recall on test data

##  Analysis

- **Notebook:** `Main.ipynb` (79KB) with rendered output `Main.html` (358KB)
- **Data:** Local fingerprint image dataset in `data/` directory

## Tech Stack

`Python` · `Scikit-learn` · `OpenCV` · `Matplotlib` · `Jupyter Notebook`

## License

Apache 2.0
