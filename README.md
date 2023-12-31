# machineLearning_regression linear
Supervised_learning for house_id dan insurance

# guide-start python code 

- Install miniconda
- Install jupyter notebook
- Install Instalasi Environment python env_jcopml.yml
- check_installation.py

# sample dataset preview insurance 

| Age | Sex   | BMI   | Children | Smoker | Region    | Charges     |
|-----|-------|-------|----------|--------|-----------|-------------|
| 19  | female| 27.900| 0        | yes    | southwest | 16884.92400 |
| 18  | male  | 33.770| 1        | no     | southeast | 1725.55230  |
| 28  | male  | 33.000| 3        | no     | southeast | 4449.46200  |
| 33  | male  | 22.705| 0        | no     | northwest | 21984.47061 |
| 32  | male  | 28.880| 0        | no     | northwest | 3866.85520  |

# cleansing dataset insurance

|   age |    bmi |   children | region    |    charges |   sex_female |   sex_male |   smoker_encode |
|-------|--------|------------|-----------|------------|--------------|------------|-----------------|
|    19 |  27.9  |          0 | southwest |   16884.9  |            1 |          0 |               1 |
|    18 |  33.77 |          1 | southeast |    1725.55 |            0 |          1 |               0 |
|    28 |  33    |          3 | southeast |    4449.46 |            0 |          1 |               0 |
|    33 |  22.705|          0 | northwest |   21984.5  |            0 |          1 |               0 |
|    32 |  28.88 |          0 | northwest |    3866.86 |            0 |          1 |               0 |

1 = no
0 = yes

# result 
Model Evaluation
- Accuracy: 0.7417
- Precision: 0.7350
- Recall: 0.7836

# visualiasai Linear insurance

![image](https://github.com/kmnvz-mayvez/Regression_linear_machine-learning/assets/55338832/0d4f559b-eae0-43ce-b250-dbd2d75748e9)

with ploymorphic degree = 2
Model Evaluation

- Akurasi: 0.8387
- Presisi: 0.8319
- Recall: 0.8689

# sample dataset preview house_id 

| id  | price   | bedrooms | sqft_lot | waterfront | view | condition | sqft_above | sqft_basement | bathrooms | floors | sqft_living |
| --- | ------- | -------- | -------- | ---------- | ---- | --------- | ---------- | ------------- | --------- | ------ | ----------- |
| 1   | 315000  | 3        | 7912     | 0          | 0    | 3         | 1340       | 0.0           | 1.5       | 1.5    | 1340        |
| 2   | 1394000 | 5        | 9050     | 0          | 4    | 5         | 3370       | NaN           | 2.5       | 2      | 3650        |
| 3   | 520000  | 3        | 11947    | 0          | 0    | 4         | 1930       | NaN           | 2         | 1      | 1930        |
| 4   | 485000  | 3        | 8030     | 0          | 0    | 4         | 1000       | NaN           | 2.3       | 1      | 2000        |
| 5   | 478000  | 4        | 10500    | 0          | 0    | 4         | 1140       | NaN           | 2.5       | 1      | 1940        |

# cleansing dataset

|   id |    price |   bedrooms |   sqft_lot |   waterfront |   view |   condition |   sqft_above |   sqft_basement |   bathrooms |   floors |   sqft_living |
|-----:|---------:|-----------:|-----------:|-------------:|-------:|------------:|------------:|----------------:|------------:|---------:|--------------:|
|    1 |   315000 |          3 |       7912 |            0 |      0 |           3 |         1340 |               0 |           0 |       15 |          1340 |
|    2 |  1394000 |          5 |       9050 |            0 |      4 |           5 |         3370 |               1 |          25 |        2 |          3650 |
|    3 |   520000 |          3 |      11947 |            0 |      0 |           4 |         1930 |               1 |           2 |        1 |          1930 |
|    4 |   485000 |          3 |       8030 |            0 |      0 |           4 |         1000 |               1 |          23 |        1 |          2000 |
|    5 |   478000 |          4 |      10500 |            0 |      0 |           4 |         1140 |               1 |          25 |        1 |          1940 |

# result 
Model Evaluation
- Akurasi: 0.9271
- Presisi: 0.9240
- Recall: 0.9145

# visualisasi Liner house_id 

![image](https://github.com/kmnvz-mayvez/Regression_linear_machine-learning/assets/55338832/44421322-5dd8-43a3-ae06-5939915d5345)



