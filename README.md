# SC1015 Mini Project - _Binary Prediction of Singaporeans/PR Birth Rate_

Our Mini-Project for SC1015 (Introduction to Data Science and Artificial Intelligence) aims to identify whether the birth rate for Singaporeans/PR in Singapore will increase or decrease given several factors, using binary classification.

To make our work more efficient and encounter less conflict, we decided follow the ensemble learning approach. We will research and analyze our variables individually, from which we will decide the best model and features for our variables. This will then be used to combine the models trained to form a single model. By training multiple models on different datasets, and then combining their predictions, we hope to reduce the risk of overfitting and improve the generalization performance of our models. 

![image](Images/Project%20Title.png)

### Problem Definition

- Can we use machine learning to predict if the birth rate for Singaporeans/PR in Singapore will increase or decrease in the next month given several factors?
- What is the best way to achieve our prediction?

### Models/Libraries Used

* ![Pandas]
* ![Matplotlib]
* ![scikit-learn]
- Binary Classification
    - Random Forest Tree
    - Logistic Regression
    - Bagging Classifier
    - Voting Classifier
- Performance Evaluation
    - K-Fold

### Conclusion
- The Random Forest Classifier has constantly been the best model when compared the models trained (Logistic Regression & Bagging Classifier)
- The performances of the individual models ranged from ~0.6 to ~0.8
- The resulting final model is able to achieve a decent performance 
    - Accuracy: 0.79
    - Precision: 0.83
    - Recall: 0.83
    - F1 Score: 0.83
- Binary Classification techniques allow for a decent model for prediction of birth rate increase/decrease in the next month, although other non-tangible factors may play a strong role as well

### Presentation Slides
https://docs.google.com/presentation/d/1MegqOAMAS4XsAv9m_hg364R441f3cxWtTKmo7IXK4wA/edit?usp=sharing

### Skills and knowledge gained

- Creating proper projects using Github with multiple collaborators
- Data sourcing techniques and resources
- Dataset cleaning and preparation
- Model performance evaluation techniques
- Combining multiple weak models to train a stronger one
- Concepts about Precision, Recall, F1 Score

### Contributors

- Ooi Chee Han 
    - Variables: Housing Resale Prices, Marriage
    - Voting Classifier
- Joseph Teo 
    - Variables: Groceries, Income, Female Labour Force
- Phua Zai Qin 
    - Variables: Food Costs, Cost of Education, Marriage Age

### Datasets
- [Live-Births By Sex And Ethnic Group](https://tablebuilder.singstat.gov.sg/table/TS/M810051)
- [Consumer Price Index](https://tablebuilder.singstat.gov.sg/table/TS/M212882)
- [Resale Flat Prices](https://data.gov.sg/dataset/resale-flat-prices?resource_id=adbbddd3-30e2-445f-a123-29bee150a6fe)
- [F&B Services Index](https://tablebuilder.singstat.gov.sg/table/TS/M601661)
- [Income by Household](https://tablebuilder.singstat.gov.sg/table/CT/17797)
- [Median Marriage Age](https://tablebuilder.singstat.gov.sg/table/TS/M830182)
- [Female Labour Force](https://tablebuilder.singstat.gov.sg/table/TS/M182111)

### References
- https://www.singstat.gov.sg/-/media/files/publications/population/ssnmar09-pg18-19.ashx
- https://www.mynicehome.gov.sg/hdb-how-to/buy-your-flat/a-guide-to-hdb-bto-flat-types/
- https://towardsdatascience.com/what-is-cross-validation-622d5a962231
- https://www.baeldung.com/cs/cross-validation-k-fold-loo
- https://medium.com/@arch.mo2men/what-is-bagging-classifier-45df6ce9e2a1
- https://towardsdatascience.com/use-voting-classifier-to-improve-the-performance-of-your-ml-model-805345f9de0e
- https://medium.com/analytics-vidhya/confusion-matrix-accuracy-precision-recall-f1-score-ade299cf63cd
- ChatGPT

[Pandas]: https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white
[Matplotlib]: https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black
[scikit-learn]: https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white
