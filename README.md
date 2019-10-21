# Review Triage with NLP and ML 

## Business scenario 
This work is inspired by a kaggle data set, ['Women's eCommerce Clothing Reviews'](https://www.kaggle.com/nicapotato/womens-ecommerce-clothing-reviews). 

### Iteration 1 - Rapid Prototyping 
Some customers claimed that the actual color of products are different from what is displayed in a commerce app. We wanted to see if we can quickly make a ML service to classify such products, and hand over to photo retouching team to validate the work 

#### Data Preparation 
* [Annotation data prep with sampling](/annotation_prep.ipynb)  
* Color mismatch case tagging with Doccano 

#### ML Training 
* Logistic regression with bag-of-words 

#### ML Deployment 
* ML Classifier as service with Flask 

### Iteration 2 - Topic Classification
There are needs to classify other cases from product reviews such as quality issue or sizing/fit. We will create a triage system with NLP methodologies whie estabilishing ML pipeline with DevOps 

#### Feature Engineering  
* Probablistic models  

#### ML Deployment 
* Azure webapp with Azure DevOps  