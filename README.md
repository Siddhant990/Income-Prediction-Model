# Income Prediction Model

## Project Description
This project builds a linear regression model to predict future income using historical data of Canada's per capita income. The model can be used to forecast per capita income (US$) based on the year.

## Dataset
The following dataset is used in this project:
- **canada_per_capita_income.csv**: This file provides annual data of Canada's per capita income (US$) from 1970 to 2016.

## Technical Details
The following technologies and libraries are used in this project:

- **Python**: Programming language
- **pandas**: For data handling and analysis
- **numpy**: For numerical computation
- **matplotlib**: For data visualization
- **scikit-learn**: For machine learning model (Linear Regression)

## Model Description
This project uses a simple linear regression model that studies the relationship between year (input feature) and per capita income (target variable). The model is trained on historical data from 1970-2016 and can be used to estimate per capita income for future years.

## Usage Instructions
1. Ensure that the necessary libraries are installed on your system:
   ```
   pip install pandas numpy matplotlib scikit-learn
   ```

2. Open the `Income_prediction_Model.ipynb` notebook in Jupyter or Google Colab.

3. Upload the dataset file `canada_per_capita_income.csv` or place it in the same directory.

4. Run all the cells in the notebook one by one.

5. To predict income for future years, use the following code:
   ```python
   # To predict per capita income for the year 2031
   reg.predict([[2031]])
   ```

## Results and Conclusion
The model establishes a linear relationship between year and per capita income. This model can be used to estimate per capita income for future years, although it is important to note that this is a simplified model and many other factors that are not included in this model may affect actual income.

## Future Improvements
This model can be improved in the following ways:
- By adding more features (such as GDP, unemployment rate, etc.)
- By using more complex models (such as polynomial regression)
- By updating the model with more recent data

## Contact
For more information, please contact: [Your email or contact details] # Income-Prediction-Model
