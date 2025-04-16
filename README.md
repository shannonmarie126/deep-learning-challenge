# deep-learning-challenge

Overview: This project utilizes deep neural network models to predict the success of applicants if funded by a nonprofit called Alphabet Soup.

Results: 
- Target variable: success of the applicant
- Feature variables: application type, affiliation sector of industry, government organization classification, use case for funding, organization type, active status, income classification, and funding amount requested.

- Model info: in both models, two layers were used (a third did not increase accuracy), the first model had 80/30 nodes and the optimization was 120/40. The first layer is 2-3 times the input features for both models. Both models used a Relu function for the first two layers since all values are scaled 0 to 1 then sigmoid for the output layer in order to classify the results into success and not successful.

- Changes: In optimization, the EIN is included and the status dropped to increase accuracy, but this could be considered overfitting the model. Binning of classification and application type is different in the optimization, increased nodes and more nodes and epochs were utilized in optimization as well. Accuracy increased from 72.9% to 73.3%.
