# Dataset
This dataset information health information of a around 800 patients and whether they are diabetic or not

Each patient is described using the following attributes:

1. Number of pregnancies
2. Glucose level
3. Blood pressure level
4. Skin thickness
5. BMI
6. Age
7. Diabetic Pedigree
8. Insulin level
9. Outcome

Here outcome is the class label or the target variable. Outcome equal to 1 denotes that the person has diabetes and outcome equal to 0 means the patient does not have diabetes.


Dataset overview

```diabetes_df.head()```

![Alt text](image.png)

```diabetes_df.describe()```
![Alt text](describe.png)


The dataset has a high variance so we need to perform data scaling or data normalization.

Original dataset:
![Alt text](images\before_norm.png)


Original dataset:
![Alt text](images\before_norm.png)


Once the dataset is normalized and contains no null values, we can perform multiple ML models and determine the best one based on the accuracy.