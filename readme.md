# Hybrid Neural Network Models for Predicting Limit Order Executions in High-Frequency Trading

## Abstract
In this research, we investigate various hybrid neural network models, including logistic regression, weighted logistic regression, and XGBoost combined with artificial neural networks (ANNs), to classify executed versus non-executed orders in high-frequency trading (HFT). Our study highlights the complexity of limit order books (LOBs) and the severe class imbalance present, showcasing the efficiency of using class weights, regularization penalties, and other optimizations to address these challenges. The best model combines XGBoost and ANN, achieving perfect prediction in simulations, though with limitations in real-world applications.

## Introduction
High-frequency trading (HFT) is characterized by low-latency and high-frequency data analytics, where success depends on microseconds. Our study contributes to this field by developing a robust hybrid neural network classification model to predict the execution of limit orders, focusing on both technical and practical insights into order execution factors influenced by market conditions.

### Problem Relevance
The growth of AI and electronic trading has drastically increased the amount of data available, making the ability to utilize this data for predictive insights a significant advantage. Our research tackles the challenge of predicting the likelihood of limit order execution, considering various market factors that influence order fulfillment.

### Proposed Approach
Our proposed model integrates logistic regression and ANNs to handle both linear and non-linear relationships within LOB data. This approach aims to optimize prediction accuracy while considering the computational complexity and data characteristics.

## Data Exploration
We analyze high-frequency limit order book data from LOBSTER, focusing on Microsoft (MSFT) and Apple (AAPL) stocks. The data consists of detailed order flow information, allowing us to explore the dynamics of order submission, cancellation, and execution.

### MSFT and AAPL LOB Data
Exploratory analysis reveals patterns like high frequency of small-sized orders and relative price stability. We further examine order types and their implications on trading strategies, highlighting the complexities in predicting order executions based on LOB data.

## Literature Review
Our review covers key areas including:
- **LOB Mechanics and Challenges**: Understanding the foundational mechanics of LOBs and the inherent challenges posed by their high dimensionality and complex dynamics.
- **Machine Learning Applications in LOBs**: The use of advanced machine learning techniques to model and simulate LOB dynamics for improved prediction and trading strategies.
- **Hybrid Modeling Approaches**: Combining logistic regression with neural networks and XGBoost to enhance predictive accuracy and handle imbalanced datasets effectively.

## Methodology
Detailed methodology sections cover logistic regression, XGBoost, and ANNs, providing insights into model architectures, training processes, and feature importance in the context of LOB data.

## Results
Performance metrics for various models on MSFT and AAPL datasets are discussed, highlighting the effectiveness of hybrid approaches in enhancing prediction accuracy and managing class imbalance.

## Discussion and Future Work
We delve into the implications of our findings, discussing the computational considerations and practical implications for real-time trading systems. Future research directions include improving model interpretability and incorporating real-time data updates to enhance model responsiveness to market dynamics.

## Figures and Supplemental Work
The research paper includes detailed figures and tables presenting exploratory data analysis, model performance metrics, and feature importance insights.
