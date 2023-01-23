# [Linear Regression Using Python](https://en.wikipedia.org/wiki/Linear_regression)

### Prerequisites

The things that you must have a decent knowledge on: 
```
    * Python
    * Linear Algebra
    * Calculus
```

### Installation

* This project is fully based on python. So, the necessary modules needed for computaion are:
```
    * Numpy
    * Sklearn
    * Matplotlib
    * Pandas
```

* The commands needed for installing the above modules on windows platfom are:
```python

    pip install numpy
    pip install sklearn
    pip install matplotlib
 
```

### Explanation 

* Here were performing **linear regression** on the Quicker Car Price Prediction Dataset.
* The details of the dataset are:
  1. Title: Car_Price_Prediction

  2. Sources:
    (a) Origin:  This dataset was taken from the Kaggle [Balaka Biswas](https://www.kaggle.com/balaka18)
    (b) Creator:  BALAKA BISWAS


  3. Relevant Information:

      Car Price details of Used cars around 2000-2017.

  4. Number of Instances: 891

  

  5. Attribute Information:

      1. **name**      Name of the car
      2. **company**   Manufacture Name
      3. **year**      Year of Manufacture
      4. **Price**      Price of car in INR.
      5. **Kms_driven**       Total kms driven by car on its life span
      6. **fuel_type**        Type of fuel used

    6. Dataset are highly prone to missing values, outliers and other noises. Strict Clean up is required.

### Result:

* The model shows the accuracy R2 score of 0.85% 

* Save the model using pickle Serializers.