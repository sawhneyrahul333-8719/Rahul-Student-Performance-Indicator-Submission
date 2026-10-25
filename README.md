# Student Exam Performance Predictor

Assignment 1 - Software Engineering and Programming

`Student_Exam_Performance_Predictor.ipynb` uses the 13 study-hour and exam-score records from
the assignment to explore the data with NumPy and Pandas, plot it with Matplotlib, and train a
scikit-learn Linear Regression model that predicts exam scores from study hours.

The notebook already contains the written explanations, the saved outputs, and both plots:
the exploratory scatter plot, and the same plot with the fitted regression line.

## How to run

The notebook works on macOS, Windows and Linux with Python 3.13 or newer.

1. Open a terminal in this folder and install the libraries:
   - macOS / Linux: `python3 -m pip install numpy pandas matplotlib scikit-learn jupyter`
   - Windows: `py -m pip install numpy pandas matplotlib scikit-learn jupyter`
2. Start Jupyter with `jupyter notebook Student_Exam_Performance_Predictor.ipynb`
   (or open the notebook in VS Code or Anaconda).
3. Choose **Kernel → Restart & Run All**.

The data is included in the notebook, so no extra files are needed. If Anaconda is installed,
all of these libraries are already available and step 1 can be skipped.

## Key results

| Result | Value |
|---|---:|
| Observations (training / test) | 13 (10 / 3) |
| Fitted line | score = 37.23 + 6.07 × hours |
| Test MAE | 1.48 points |
| Predicted score for 7.5 hours | 82.77 |
