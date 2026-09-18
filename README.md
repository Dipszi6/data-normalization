# Data Normalization

This notebook contains the implementation and comparison of data normalization methods using Python.

## Steps
1. Load dataset
2. MinMaxScaler
3. RobustScaler
4. Comparison of both methods
5. Conclusion

## Libraries
- Pandas
- Scikit-learn

## Dataset
Sumber: [Kaggle - Car Features and MSRP](https://www.kaggle.com/datasets/CooperUnion/cardataset)

## Conclusion
RobustScaler is more recommended for this dataset because there are extreme outliers in the MSRP and highway MPG columns.
