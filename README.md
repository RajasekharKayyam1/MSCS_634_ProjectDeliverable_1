## Key Insights

- Highest-revenue month: November 2011, with £1,156,205.61 in sales.
- Top-selling product: PAPER CRAFT, LITTLE BIRDIE, with 80,995 units sold.
- Outlier detection: 31,231 high-value transaction lines were flagged using the IQR method.
- Quantity and Revenue correlation: 0.914451 (strong positive relationship).
- UnitPrice and Revenue correlation: 0.081619 (weak positive relationship).
- Quantity and UnitPrice correlation: -0.004578 (negligible linear relationship).

## Challenges and Decisions

Missing CustomerID values were excluded from customer-level analysis.
Duplicate records were removed, and canceled transactions were excluded
from positive-sales analysis.

High-value outliers were retained because they may represent legitimate
bulk purchases. Additional features were engineered to support future
regression, classification, and clustering models.
