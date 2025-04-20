# Forecasting-Module
Forecasting plays a critical role in import and distribution businesses, especially in the pharmaceutical sector where time lags in imports can lead to stockouts or overstocking. Maintaining healthy inventory levels is essential to ensure product availability and operational efficiency.

This project is a prototype of a robust forecasting algorithm designed specifically for the pharmaceutical industry. It deals with a diverse product portfolio of over 1,000 SKUs. The system addresses the unique sales behaviors of different products—some are seasonal, some remain unaffected by marketing schemes, and others display irregular patterns.

# Key features of the project include:
Outlier Detection and Correction: Intelligent preprocessing ensures that anomalies in historical data are corrected without distorting the true demand trends.

Model Selection per Product: A hybrid modeling pipeline was developed, combining both classical statistical models and modern machine learning techniques. Each product is analyzed individually to determine the most suitable forecasting method.

# Algorithms Used:
Classical Models: Simple Linear Regression (SLR), Seasonal ARIMA (SARIMA), Moving Averages
Machine Learning Models: LSTM (Long Short-Term Memory), XGBoost

The system dynamically selects the best-performing model per product based on historical patterns and performance metrics, thereby improving forecast accuracy and reliability.
This forecasting solution is a scalable, adaptable framework that empowers pharmaceutical distributors to make data-driven inventory decisions, minimize wastage, and enhance service levels.
