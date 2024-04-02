# neural-network-challenge-2
Module 19 Challenge


**Name:** Module 19 Challenge: neural-network-challenge-2

**Description:**

According to the module notes, the HR department needs a neural network prediction tool to be able to predict wheather employees are likely to leave the company.   Additionally, HR believe that there are certain departments that employees are best suited for, thus this model should also predict the department that best fits each employee.  

**Support:**

The bulk of the supoort was provided through class lessons and copilot.

**Libraries imported:**

- pandas
- tensorflow
    - from tensorflow.keras import layers
    - from tensorflow.keras.models import Model
    - from tensorflow.keras.layers import Dense, Input
    - from sklearn.model_selection import train_test_split
    - from sklearn.preprocessing import StandardScaler, OneHotEncoder


**Data analysis process and results:**

The data was explored, trained, scaled and tested.  Deep neural networks were used to create a multiple hidden layer model to assess both departmental fit and attrition of employees.  The departmental model accuracy was fairly low at .56 and the model would need to be improved through the inclusion of different data or a different model such as RNN.  The attrition model fared slightly better with an accuracy score of .82.  
