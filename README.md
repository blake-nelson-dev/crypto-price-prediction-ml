# Cryptocurrency Price Prediction Using Machine Learning

A comparative analysis of different machine learning models for cryptocurrency price prediction, demonstrating that simpler models can perform comparably to more complex approaches while requiring less computational resources.

## Project Overview

This project implements and compares multiple machine learning models to predict cryptocurrency prices using historical data from Yahoo Finance. Our analysis shows that a simple linear regression model can achieve comparable or better results than more complex models, with predictions accurate within a $15 margin of error.

## Dependencies

```python
scikit-learn
yfinance
pandas
numpy
matplotlib
```

## Models Implemented

1. Linear Regression
   - Best performing model
   - Achieved predictions within $15 margin of error
   - Most computationally efficient

2. Random Forest
   - Good performance but more computationally intensive
   - Effective at capturing non-linear patterns

3. Support Vector Regression (SVR)
   - Lowest performing model in our tests
   - Required careful hyperparameter tuning

4. K-Nearest Neighbors (KNN)
   - Moderate performance
   - Simple implementation

5. Decision Tree
   - Moderate performance
   - More interpretable than complex models

6. Neural Network (MLP)
   - Comparable performance to linear regression
   - More complex implementation
   - Higher computational requirements

## Data

- Source: Yahoo Finance API
- Features: Historical cryptocurrency prices
- Training/Test Split: 86/14
- Time Period: Full available history
- Focused on Bitcoin (BTC-USD) for model comparison

## Project Structure

```
├── crypto_prediction.ipynb     # Main Jupyter notebook with analysis
└── Project  PPT.pptx           # Powerpoint presentation
└── Project Report.pdf          # Project Report
├── README.md                   # Project documentation
└── .gitignore                  # Git ignore file
```

## Usage

1. Clone the repository
```bash
git clone https://github.com/yourusername/crypto-price-prediction-ml.git
```

2. Install required packages
```bash
pip install scikit-learn yfinance pandas numpy matplotlib
```

3. Open and run the Jupyter notebook
```bash
jupyter notebook crypto_prediction.ipynb
```

## Key Findings

- Linear regression achieved the best performance despite its simplicity
- Model predictions were accurate within $15 margin
- More complex models didn't significantly improve prediction accuracy
- Simple models can be effective for cryptocurrency price prediction

## Future Improvements

- Integration of cryptocurrency news data
- Implementation of sentiment analysis
- Enhanced handling of sporadic price changes
- Real-time prediction capabilities

## Authors

- Blake Nelson
- Eric Hedgren
- Gavin Fisher

## License

MIT License
