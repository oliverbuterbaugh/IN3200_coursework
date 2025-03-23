# IN3200 Coursework

This repo contains four Jupyter notebooks for analysing and modeling two datasets:
- California Housing dataset
- Human Activity Recognition (HAR) dataset

## Setup Instructions

1. **Clone the repo**
   ```
   git clone https://github.com/oliverbuterbaugh/IN3200_coursework.git
   cd <repo-folder>
   ```

2. **Create and activate a virtual environment (recommended)**
   ```
   python -m venv .venv
   source .venv/bin/activate  # On Windows: .venv\Scripts\activate
   ```

3. **Install dependencies**
   ```
   pip install -r requirements.txt
   ```

4. **Run Jupyter**
   ```
   jupyter notebook
   ```

5. **Open the notebooks**
   - `housing_model.ipynb` - California Housing price prediction
   - `HAR_model.ipynb` - Human Activity Recognition classification

## Dataset Information

- The California Housing dataset is loaded directly in the notebook using scikit-learn.
- The HAR dataset should be in the `UCI_HAR_Dataset/` directory.

## Requirements

Python 3.8+ with the packages listed in requirements.txt 