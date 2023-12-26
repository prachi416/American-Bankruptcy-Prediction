# American-Bankruptcy-Prediction
The motivation behind the U.S. Company Bankruptcy Prediction Dataset revolves around the
critical need to predict the financial distress or bankruptcy of companies. This is an important
aspect for investors, creditors, policymakers, and other stakeholders in the business world for
several reasons:
1. Risk Management and Investment Decisions
2. Early Warning for Companies
3. Financial Market Stability
4. Policy Making and Economic Research
5. Credit Scoring and Financial Services
6. Legal and Compliance Implications
7. Supply Chain Management
8. Employee and Stakeholder Interests
In summary, the U.S. Company Bankruptcy Prediction Dataset serves as a crucial tool for
various stakeholders to anticipate financial distress in companies, enabling proactive measures
in investment, policy-making, risk management, and strategic planning.

In the analysis of the U.S. Bankruptcy dataset, both Random Forest and XGBoost ensemble
models demonstrated comparable levels of accuracy but KNN is not suitable.
1. Notably, the precision for predicting 'failed' status was found to be quite high at
0.79 for Random Forest, indicating its effectiveness in correctly identifying
companies at risk of bankruptcy. This performance is particularly significant given
the imbalanced nature of the dataset, where 94% of the entries are labeled as
'alive'.
2. It was observed that the K-Nearest Neighbors (KNN) algorithm did not yield as
effective results for the 'failed' status as the ensemble methods did. While
XGBoost showed a precision of 0.59 for 'failed' status, Random Forest
outperformed with a precision of 0.79.
3. This disparity underscores the strength of ensemble models like Random Forest
and XGBoost in handling imbalanced data, particularly in contrast to the KNN
algorithm. Ensemble methods, through their construction of multiple decision
trees and aggregation of results are better equipped to distinguish between
minority and majority classes, even in datasets with significant class imbalances
