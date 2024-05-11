### Project Title: NBA Player Position Classification 🏀

#### Overview:
In this project, we aim to classify NBA players into five positions on the basketball court: SG (shooting guard), PG (point guard), SF (small forward), PF (power forward), and C (center). We will use NBA player statistics from the regular season to train a classification model.

#### Dataset:
The dataset used for this project is sourced from Basketball Reference ([NBA 2023 Regular Season Player Stats](https://www.basketball-reference.com/leagues/NBA_2023_per_game.html)). The data is provided in a CSV file named "nba_stats.csv".

#### Tasks:
1. **Model Training and Evaluation:**
    - Utilize various classification methods, including Decision Tree, Naive Bayes, KNN, SVM, and Neural Networks, on the dataset.
    - Perform data preprocessing and feature engineering as necessary.
    - Split the dataset into 80% training and 20% validation sets (using `random_state=0`).
    - Print out the training and validation set accuracy of each model.
    - Display the confusion matrix for both training and validation sets.

2. **Testing on Dummy Test Set:**
    - Apply the trained models to a dummy test set provided in the file "dummy_test.csv".
    - Print the accuracy and confusion matrix for each model on the dummy test set.

3. **Cross-Validation:**
    - Use 10-fold stratified cross-validation with each classification method.
    - Print out the accuracy of each fold for every model.
    - Calculate and print the average accuracy across all folds for each model.

#### Implementation Details:
- Programming Language: Python
- Libraries: pandas, scikit-learn
- Model Evaluation Metrics: Accuracy, Confusion Matrix
- Classification Methods: Decision Tree, Naive Bayes, KNN, SVM, Neural Networks
- Model Tuning: Hyperparameter tuning (if applicable)

#### Files:
1. `nba_stats.csv`: Contains NBA player statistics for the regular season.
2. `dummy_test.csv`: Example test set for evaluating the trained models.
3. `nba_position_classification.ipynb`: Jupyter Notebook containing the code implementation for the tasks.
4. `README.md`: Markdown file providing an overview of the project, tasks, implementation details, and files used.

#### Usage:
1. Clone the repository: `git clone https://github.com/devarshvora/nba-position-classification.git`
2. Navigate to the project directory: `cd nba-position-classification`
3. Run the Jupyter Notebook `nba_position_classification.ipynb` to execute the code and perform tasks.
4. View the results, including accuracy, confusion matrices, and model evaluation metrics for each classification method.

Feel free to reach out if you have any questions or need further assistance with the project.

This updated README now includes information about the different classification methods used in the project, providing a more comprehensive overview of the techniques employed for NBA player position classification. If you have any other specifications or additions you'd like to make, feel free to let me know!
