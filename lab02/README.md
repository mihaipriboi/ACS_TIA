# Lab 02 – Linear Regression

Requirements: [Cerinte Laborator TIA 2.pdf](Cerinte%20Laborator%20TIA%202.pdf)

## Tasks

1. **Data processing** – turn `Year_Built` into "years since construction"; apply Min-Max normalization to `Square_Footage`.
2. **Training preparation** – separate the features (X) from the target (`House_Price`); split into train (80%) and test (20%) with a fixed random state.
3. **Training** – train `LinearRegression` and `SGDRegressor`.
4. **Evaluation** – predict on the test set and report MSE and R² for each model.
5. **Visualization** – line plot comparing actual vs. predicted prices for each model.

## Dataset

[houses.csv](houses.csv) – 1000 houses, with an unnamed index column followed by:

| Column | Description |
|--------|-------------|
| `Square_Footage` | Living area (sq ft) |
| `Num_Bedrooms` | Number of bedrooms |
| `Num_Bathrooms` | Number of bathrooms |
| `Year_Built` | Construction year |
| `Lot_Size` | Lot size |
| `Garage_Size` | Garage size |
| `Neighborhood_Quality` | Neighborhood quality score |
| `House_Price` | Sale price (target) |
