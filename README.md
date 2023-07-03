# Process of feature exploration

Technology stack: 
- Python
- NumPy
- Pandas
- Keras
- Tensorflow
- scikit-learn

Example of data view before changes

![image](https://user-images.githubusercontent.com/62389300/224985941-4b64b3c0-1678-4dbb-be69-009b62a8b63d.png)


Diagram for considering features for a product

<img width="384" alt="Bez tytułu" src="https://user-images.githubusercontent.com/62389300/224987153-425db8e5-1b77-4cda-bb0e-33dcc8a22cd3.png">

# Building the model
- Wholesale data
- Data from 2010 to 2019
- The product contained 416 records, i.e. 416 weeks of sales
- The algorithm predicted demand for the last 52 weeks
- LSTM parameters: test=52, train=363, bach_size=1, epos=812, nurons=1

# Achieved results
Legent:
Red - prediction
Blue - test
cecha1 - name of first feature
cecha2 - name of second feature
y line - last weeks

![image](https://user-images.githubusercontent.com/62389300/224988230-c4a0df0e-00f6-4bd2-a237-94c6716ded47.png)
![image](https://user-images.githubusercontent.com/62389300/224988276-90e99317-72a2-412c-9203-66cd30865106.png)
![image](https://user-images.githubusercontent.com/62389300/224988306-c5599457-24bb-4c7e-a624-439b35b4c2b2.png)
![image](https://user-images.githubusercontent.com/62389300/224988376-3d940acc-e4dd-4048-84f6-59732c1b6d32.png)
![image](https://user-images.githubusercontent.com/62389300/224988404-09fd43d6-d577-4c77-81cc-2055c0cc3fb2.png)
![image](https://user-images.githubusercontent.com/62389300/224988438-ee6f276a-921c-46a5-8d03-6aca53ee18e3.png)

# RMSE

![image](https://user-images.githubusercontent.com/62389300/224989799-a3c042ed-7dce-49cf-905d-879e7551d529.png)


