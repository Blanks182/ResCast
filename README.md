# ResCast

**Project Title**: ResCast

**Hackathon**: Wave2Web Hack

**Team**: [Aakash Khatter](https://www.linkedin.com/in/aakashkhatter/), [Meghaa Gangahar](https://www.linkedin.com/in/meghaa-gangahar-888b13118/), [Manvika Athwani](https://www.linkedin.com/in/manvika-athwani-a44aa8a1/), [Shreya Bedia](https://www.linkedin.com/in/shreya-bedia/)

### Overview:

ResCast, our hackathon entry for the Wave2Web Hack, addresses the critical challenge of water management in Bengaluru, India. Rapid urbanization and swelling population, coupled with inefficient water management, have heightened the risk of drought and depleted water resources in the region. Recognizing the need for an advanced solution, our project proposes a predictive model to forecast reservoir water levels and storage volumes 1-3 months in advance, enabling better water risk management and decision-making.

### Problem Statement:

The increasing demand for water in Bengaluru, due to urbanization and population growth, has placed significant strain on local water resources. Key reservoirs like Krishnaraja Sagar and Kabini are crucial for the city’s water supply, but their levels have often fallen below minimum drawdown levels during peak summers. An accurate forecasting model is needed to manage these risks effectively.

### Solution:

**Hydrological Model**
Our solution, ResCast, predicts reservoir metrics like water levels and storage volumes. The model incorporates time series data for hydro-meteorological variables to generate short-term predictions.

ResCast features a hydrological hybrid predictive model, combining the strengths of two different approaches: a SARIMAX (Seasonal AutoRegressive Integrated Moving Average with eXogenous factors) model and a Multilayer Perceptron (MLP) neural network. This hybrid model effectively captures both linear and non-linear patterns in the data. The SARIMAX component analyzes seasonal trends and climatic influences, while the MLP adds depth by understanding complex, non-linear relationships. Together, they provide a comprehensive and nuanced forecast of water levels and storage volumes.

**Dashboard**
The ResCast dashboard is an interactive tool designed for ease of use. It visually presents the forecasted data, allowing users to quickly understand and analyze the predicted water levels and volumes. Features include interactive charts and graphs, a user-friendly interface, and real-time data updates. This dashboard serves as a vital tool for policymakers and water management authorities, providing them with actionable insights for strategic decision-making.

### Key Features:

**Predictive Analytics**: Leveraging machine learning techniques to forecast reservoir levels and storage volumes.

**Data-Driven**: Utilizes a comprehensive dataset, including historical reservoir levels, meteorological data, and river flow metrics.

**Visualization and Contextual Elements**: Offers visual representations of forecasted data, aiding in easier interpretation and decision-making.

**Technologies Used**:

-   Python
-   R
-   Keras
-   Numpy
-   Pandas
-   Statsmodels
-   Matplotlib
-   Scikit Learn
-   Jupyter Notebook
-   Tableau
-   Google Colab

### Future Directions:

**Extended Forecast Range**: Aiming to expand the prediction horizon to three months.

**Enhancements in Model Tuning**: Continuous improvement of the SARIMAX and MLP model parameters.
Integration with External Data Sources: To incorporate climatic forecasts and additional hydrological data for improved accuracy.

### Repository Contents:

**Source Code**: Complete Python scripts and Jupyter notebooks used for model development and data analysis.

**Data Files**: Datasets utilized in the project.

**Documentation**: Detailed explanation of the methodology, model architecture, and analysis results.

**Visualization Dashboards**: Interactive Tableau dashboards for data representation.
