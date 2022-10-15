# Neural_Network_Charity_Analysis
## Overview of the analysis
using the features in the provided dataset that help Beks create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup. From Alphabet Soup’s business team, Beks received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization.

## Results

### Data Preprocessing
![image](https://user-images.githubusercontent.com/105985796/195970698-e1920907-d67b-4eae-9c74-cfb30b8bfa1a.png)

![image](https://user-images.githubusercontent.com/105985796/195970758-7ef2824e-14d8-41e7-a5a8-1bda3991e297.png)

### Compiling, Training, and Evaluating the Model
![image](https://user-images.githubusercontent.com/105985796/195970887-37a5bba2-75bc-4b58-b9d5-39cca5cb02dd.png)

![image](https://user-images.githubusercontent.com/105985796/195971243-43a3074a-8874-4c1e-89c4-4b412312c727.png)

For the first model, I used 2 hidden layers with "relu" activation function for training because its simple a first approach. Secondly, I used "sigmoid" to activate function.
80 neurons in the first layer and 30 neurons in the second because a "sigmoid" as a output activate function. This model had an accuracy of 72.45%, not ba, but not the 75% requested, and a lost of 55.94%.

![image](https://user-images.githubusercontent.com/105985796/195972273-f9a8ba2c-cd29-44d5-af16-bdd132ab6c0f.png)
![image](https://user-images.githubusercontent.com/105985796/195972328-ceff311c-dd12-49c5-b915-fc02aaa132db.png)

![image](https://user-images.githubusercontent.com/105985796/195972626-f2517b2a-1a7c-4858-9210-a0028736ad08.png)


Unlike first model, I used 3 hiden layers. 1st and 2nd layers were same as first model, but I added 3rd layer with 10 neurons. As we expected, the accuracy was improved and the loss was down. The rate of aaccuracy 78.95% and the rate of loss 44.02%

In the first model, I dropped "EIN","NAME". Unlike the first modelI dropped "EIN", "SPECIAL_CONSIDERATIONS" for the second model.

## Summary
Optimizing the model we exceeded the accuracy of 75%! So, this model has an accuracy of 78.95% to determine if an applicant orgaization will be successful.
