# Binary-Classification-with-Logistic-Regression-and-Sampling-Techniques
This project demonstrates how to perform binary classification using logistic regression and different sampling techniques to address class imbalance. It includes preprocessing steps, model training, evaluation metrics, and visualization of ROC curves.

## Table of Contents
- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction
In many real-world scenarios, binary classification tasks suffer from class imbalance, where one class is significantly underrepresented compared to the other. This project addresses this issue by applying sampling techniques, specifically Random Undersampling, Random Oversampling, and SMOTE, to balance the class distribution before training logistic regression models.

## Installation
1. Clone the repository:
   ```shell
   git clone https://github.com/your-username/your-repo.git
   ```
2. 
Certainly! Here's an example of a README file for your project on GitHub:

markdown
Copy code
# Binary Classification with Logistic Regression and Sampling Techniques

This project demonstrates how to perform binary classification using logistic regression and different sampling techniques to address class imbalance. It includes preprocessing steps, model training, evaluation metrics, and visualization of ROC curves.

## Table of Contents
- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction
In many real-world scenarios, binary classification tasks suffer from class imbalance, where one class is significantly underrepresented compared to the other. This project addresses this issue by applying sampling techniques, specifically Random Undersampling, Random Oversampling, and SMOTE, to balance the class distribution before training logistic regression models.

## Installation
1. Clone the repository:
   ```shell
   git clone https://github.com/your-username/your-repo.git
   ```
2. Change to the project directory:
cd your-repo

3. Install the required dependencies:

## Usage
Place your dataset file (datacreditos.csv) in the project directory.
Run the script:

python classification.py

The script will perform preprocessing, train logistic regression models with different sampling techniques, calculate evaluation metrics, and plot ROC curves.

Dataset
The dataset (datacreditos.csv) should be in CSV format and contain the following columns:
```
Loan_Type: Type of loan

Gender: Gender of the borrower

Degree: Educational degree of the borrower

Citizenship: Citizenship of the borrower

Age: Age of the borrower

Income: Income of the borrower

Credit_Score: Credit score of the borrower

Loan_Length: Length of the loan

Signers: Number of signers

Default: Binary target variable indicating loan default (0 = non-default, 1 = default)

Note: Make sure the dataset is correctly formatted and placed in the project directory before running the script.
```

## Results
The script will display the following results:

Brier Score and ROC AUC before and after each sampling technique.
ROC curves for each model.

## Contributing

Contributions are welcome! If you have any suggestions, bug reports, or feature requests, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License.

## Contact Information
For any questions or suggestions, please feel free to reach out :

Name: Anas Sohail Zafar

Email: anassohailzafar@gmail.com

GitHub: github.com/AnasSohailZafar

Linkedin: www.linkedin.com/in/anas-sohail-zafar123
