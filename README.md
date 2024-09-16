# CreditPath - Smart Loan Predictor

## Overview

**CreditPath - Smart Loan Predictor** is a machine learning project aimed at predicting loan approval based on various applicant features. The application leverages a variety of machine learning algorithms to analyze historical loan data and provide predictive insights for new loan applications.
![image](https://github.com/user-attachments/assets/65969728-bf32-45c2-8114-da500841deff)

![image](https://github.com/user-attachments/assets/a4452339-c6bb-432b-8438-bc71692857b8)
![image](https://github.com/user-attachments/assets/318819a1-8c2d-452f-a969-a6ef067f531c)

## Features

- **Data Preprocessing:** Cleans and transforms input data for model training.
- **Model Training:** Utilizes different algorithms to train models on historical loan data.
- **Prediction:** Provides loan approval predictions based on applicant information.
- **Interactive Form:** User-friendly web interface for inputting applicant data.

## Project Structure

```
CreditPath/
│
├── dataset/
│   ├── train_data.csv       # Training dataset
│   └── test_data.csv        # Testing dataset
│
├── Loan_Prediction_Project.ipynb  # Jupyter Notebook for model development and analysis
│
├── app/
│   ├── static/              # Static files such as CSS and JavaScript
│   ├── templates/          # HTML templates for the web interface
│   └── app.py              # Flask application file
│
└── README.md               # This file
```


## Usage

1. **Upload Data:**

   Place your dataset CSV files in the `dataset/` folder.

2. **Access the Web Interface:**
https://creditpath-smart-loan-predictor-gvqf.onrender.com
   You will be able to input applicant details and get loan approval predictions.   

![image](https://github.com/user-attachments/assets/f2ba753d-d85e-47b4-ba59-5c02bd480132)


4. **Model Training and Testing:**

   Open the Jupyter Notebook `Loan_Prediction_Project.ipynb` to see the model training, evaluation, and testing process.

## Dependencies

- Flask
- scikit-learn
- pandas
- numpy
- xgboost
- seaborn
- matplotlib
- (Other dependencies listed in `requirements.txt`)

## Contributing

Contributions are welcome! Please fork the repository, make your changes, and submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [Your references, mentors, or any third-party libraries you used.]

---

Feel free to modify or expand upon this template to suit your specific needs.
