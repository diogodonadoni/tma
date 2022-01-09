# Network traffic monitoring and analysis (TMA) project
This is the shared repository for the Network traffic monitoring and analysis (TMA) project
We used the dataset CSE-CIC-IDS2018
https://www.unb.ca/cic/datasets/ids-2018.html
We generated consolidate files with different attacks in order to build a model using Weka.
![image](https://user-images.githubusercontent.com/57611549/148313854-75312f25-919f-4eb0-bc50-3d4576957b33.png)
Consolidate1 has a subset of instance (avg 10.000) from the beggining of the dataset
Consolidate2 has a subset of instance (avg 10.000) from the middle of the dataset
Consolidate3 has a subset of instance (avg 10.000 )from the end of the dataset
Consolidate4 has a subset of instance (avg 30.000 )from different parts of the dataset

We identified the best precision with Random Forest with all 80 features

![image](https://user-images.githubusercontent.com/57611549/148694203-204bc9da-61bd-4cc8-831c-04fb7ce20d91.png)

Performance with feature selection for specific attacks

![image](https://user-images.githubusercontent.com/57611549/148694277-05f86b6c-17e4-4dab-adbe-6627db334774.png)

Performance with feature selection for all attacks

![image](https://user-images.githubusercontent.com/57611549/148694316-9fcdf228-23d6-42e0-85f0-bfd152f73431.png)

![image](https://user-images.githubusercontent.com/57611549/148694332-f4ee0c32-7619-4f31-8d67-512308ab755e.png)
