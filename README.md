Sampling Assignment - Credit Card Fraud Detection

This project focuses on applying various sampling techniques to a balanced dataset for credit card fraud detection. The assignment involves evaluating the performance of five different machine learning models using five sampling methods on a balanced dataset.
Steps Followed:

    Dataset Preparation:
        The original dataset is highly imbalanced.
        Oversampling was used to balance the minority class (Class = 1) with the majority class (Class = 0).

    Sample Size Detection:
        The sample size was calculated using the formula:
        n=N⋅Z2⋅p⋅(1−p)e2⋅(N−1)+Z2⋅p⋅(1−p)
        n=e2⋅(N−1)+Z2⋅p⋅(1−p)N⋅Z2⋅p⋅(1−p)​
        Parameters: Z=1.96(95% confidence), p=0.5, e=0.05.

    Sampling Techniques:
        Five different samples were created, each using unique sampling techniques.

    Machine Learning Models:
        Logistic Regression
        Decision Tree
        Random Forest
        Support Vector Machine (SVM)
        K-Nearest Neighbors (KNN)

    Evaluation:
        Accuracy was computed for each sampling technique on each model.
        Results were saved in Sampling_Assignment_Results.csv.

Results:

The accuracy results of the sampling techniques across models are available in the results file.
How to Run:

    Clone this repository:

git clone <repository-link>

Ensure all dependencies are installed:

pip install -r requirements.txt

Run the Python script to reproduce results:

    python sampling_assignment.py

Let me know if you'd like to expand on any section!
