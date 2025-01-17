# Player Market Value and Transfer Fee Estimation
![image](https://github.com/user-attachments/assets/d48cbf25-4fd9-4675-9084-dc8cb61ed572)

### Problem Statement
Soccer clubs spent $7.35 billion on player acquisitions in 2019 alone. Accurately predicting player market value and transfer fees is vital for financial planning and preventing overpayment.

### Objectives
- Utilize machine learning models (Random Forest and Lasso Regression) to estimate:
  - Market value
  - Transfer fee
- Provide a user-friendly interface for predictions
  - Used Flask to create an API that connects our Python scripts with Data & Results to the front end.

## Data Sources
Merged player, club, and transfer data from five major European leagues (2015–2021)
- **Sofifa.com**: Player attributes and ratings
- **Transfermarkt.com**: Club and player statistics
- **Kaggle.com**: Historical transfer data (1992–2021)

## Key Results
- **Market Value Model**: High accuracy (~95%), aligning with literature benchmarks
- **Transfer Fee Model**: Moderate performance (~60%-70%), with potential for improvement

## Future Improvements
1. Adress Potential Data Leakage issues in Transfer Fee Model
2. Collect more samples and predictive features (Goal Impact Metric, etc.)
3. Fix UI Background Rendering Issue
4. Clean Repo & Create Streamlined Instructions for future developers
