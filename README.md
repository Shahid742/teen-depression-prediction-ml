# Teen Depression Prediction ML

A Machine Learning project using Random Forest to predict adolescent depression risk with 97% recall on high-risk cases.

## 📋 Project Overview

This project implements a machine learning solution to predict the risk of depression in adolescents based on various behavioral, psychological, and social factors. The Random Forest classifier achieves an impressive **97% recall** on high-risk cases, making it highly effective at identifying teenagers who may be at risk of developing depression.

### Key Features

- **High Recall Rate**: 97% recall on identifying high-risk depression cases
- **Random Forest Algorithm**: Robust ensemble learning method for accurate predictions
- **Comprehensive Feature Analysis**: Incorporates multiple factors affecting adolescent mental health
- **Data-Driven Approach**: Built on real-world data patterns
- **Easy to Use**: Jupyter Notebook implementation for transparency and reproducibility

## 🎯 Objectives

1. Predict adolescent depression risk using machine learning
2. Achieve high sensitivity to minimize false negatives (missed high-risk cases)
3. Provide interpretable predictions for mental health professionals
4. Enable early intervention for at-risk teenagers

## 📊 Project Structure

```
teen-depression-prediction-ml/
├── Notebook/
│   └── Teen_depression_predictor.ipynb    # Main ML model and analysis
├── data/                                   # Dataset files
├── report/                                 # Analysis reports and results
├── requirements.txt                        # Python dependencies
├── LICENSE                                 # MIT License
├── .gitignore                             # Git ignore rules
└── README.md                              # Project documentation
```

## 🔧 Requirements

This project requires the following Python packages:

- **scikit-learn**: Machine learning library for building the Random Forest model
- **pandas**: Data manipulation and analysis
- **numpy**: Numerical computing
- **jupyter**: Interactive notebook environment
- **matplotlib**: Data visualization and plotting

### Installation

1. Clone the repository:
```bash
git clone https://github.com/Shahid742/teen-depression-prediction-ml.git
cd teen-depression-prediction-ml
```

2. Install required packages:
```bash
pip install -r requirements.txt
```

## 📖 Usage

1. Navigate to the project directory
2. Start Jupyter Notebook:
```bash
jupyter notebook
```

3. Open `Notebook/Teen_depression_predictor.ipynb`
4. Run all cells to see the complete analysis, model training, and predictions

### Steps in the Notebook

- **Data Loading**: Import and explore the dataset
- **Exploratory Data Analysis**: Understand feature distributions and correlations
- **Data Preprocessing**: Clean and prepare data for modeling
- **Feature Engineering**: Create and select relevant features
- **Model Training**: Train Random Forest classifier
- **Evaluation**: Assess model performance with various metrics
- **Predictions**: Make predictions on new data

## 🚀 Model Details

### Algorithm: Random Forest

- **Type**: Ensemble Learning (Supervised)
- **Task**: Binary Classification (Depression Risk: Yes/No)
- **Performance Metric**: 97% Recall on high-risk cases

### Why Random Forest?

- Handles non-linear relationships well
- Provides feature importance scores
- Robust to outliers and missing values
- Low risk of overfitting due to ensemble approach

## 📈 Results

The model achieves excellent performance in identifying high-risk depression cases:

- **Recall**: 97% (catches 97 out of 100 at-risk cases)
- Minimizes false negatives - crucial for mental health applications
- Suitable for screening and early intervention programs

## 📋 Data Description

The dataset includes features related to:

- Behavioral patterns
- Psychological indicators
- Social interactions
- Lifestyle factors
- Family background
- School/academic performance

*Note: For specific feature details and data sources, refer to the Jupyter Notebook and report folder*

## 💡 Key Insights

- Early identification of at-risk adolescents is crucial
- Multiple factors contribute to depression risk
- Machine learning can effectively assist mental health professionals
- High recall rate prioritizes preventing missed cases

## ⚖️ License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

Contributions are welcome! To contribute:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/improvement`)
3. Make your changes
4. Commit your changes (`git commit -am 'Add improvement'`)
5. Push to the branch (`git push origin feature/improvement`)
6. Open a Pull Request

## 📧 Contact & Support

For questions, suggestions, or issues related to this project:

- Create an [Issue](https://github.com/Shahid742/teen-depression-prediction-ml/issues)
- Feel free to reach out to the project maintainer

## ⚠️ Important Disclaimer

This model is designed as a **screening tool** to assist mental health professionals and is not a substitute for professional medical advice, diagnosis, or treatment. Always consult with qualified mental health professionals for actual clinical decisions.

## 🔍 Future Enhancements

- Incorporate additional data sources
- Explore deep learning approaches
- Deploy as a web application
- Develop mobile application
- Continuous model improvement with new data

## 📚 References & Resources

- Scikit-learn Documentation: https://scikit-learn.org
- Mental Health Resources: Refer to local health organizations
- Depression Information: Consult medical professionals

---

**Last Updated**: 2026-05-03

Made with ❤️ by [Shahid742](https://github.com/Shahid742)