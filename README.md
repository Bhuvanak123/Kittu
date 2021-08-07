# CKD
# Download the dataset
There are many features that are responsible for Chronic Kidney Disease, e.g. age, blood pressure, sugar etc. For better prediction the Chronic kidney Disease, we should consider as many relevant features as possible. You can collect datasets from different open sources like kaggle.com, data.gov, UCI machine learning repository etc. 
	Sample data looks like this and can viewed through dataset tab:
	![image](https://user-images.githubusercontent.com/87941366/128593172-3cba70be-2dc0-4343-952a-ba09d491ce97.png)

# Preprocess or clean the data
1. Import the libraries
2. Read the dataset
3. Analyze the dataset
4. Drop unnecessary columns
5. Change the column names
6. Remove the randomness in the columns
7. Find the missing values
8. Handle the missing values
9. Split the data into independent and dependent variables
10. Split the data to train and test

Above mentioned steps are preformed in Chronic Kidney Disease.ipynb under Traning tab.


#  Few visualizations from the data analysis are shown here:

![image](https://user-images.githubusercontent.com/87941366/128593445-5b0701b0-13dc-4856-980b-1cadc90f1e40.png)
![image](https://user-images.githubusercontent.com/87941366/128593509-030a1de1-930a-4686-964d-c8fd86204840.png)

# Analyze the pre-processed data
Heat Map shows the correlation of the dataset:
![image](https://user-images.githubusercontent.com/87941366/128593603-ff364a6b-da05-4b6d-a044-bb1fdbd66558.png)

# Train  the machine with preprocessed data with an Appropriate Machine learning algorithm to build a model
Trained the Machine Learning model with Logistic Regression algorithm. Code for the model training is available under Training tab.
# Save the model and its dependencies
All the files should be saved along with there dependencies.
CKD
	DATASET--CKD.csv
	Training--CKD.ipynb
	
# Build a Web application using flask that integrates with Model built.
Using html and css scripts desinged a web page.

Home Page:
![image](https://user-images.githubusercontent.com/87941366/128593794-f56b478a-ee1f-4e8f-ac85-560bc348a5ec.png)

Prediciton Page:
![image](https://user-images.githubusercontent.com/87941366/128593815-5184117e-b2f8-4a81-ad67-52560447c54c.png)


Result Page:
![image](https://user-images.githubusercontent.com/87941366/128593841-cf445731-b6c1-41a6-a415-b4247d426664.png)

Results for this model are showed in the code, which is available in this repository.

