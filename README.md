# Hierarchical-Multi-class-classification
This project explores the application of advanced hierarchical multi-class classification techniques using natural language processing models such as BERT and DistilBERT to enhance both the accuracy and efficiency of web scraping in the grocery domain. The hierarchical multi-class classification system was designed to categorize the scraped product data into the appropriate categories, following a structured hierarchy.

## Key Features 
- The system uses a hierarchical approach to multi-class classification, starting from the highest level of classification (TAG1) to the lowest (TAG5). Each level's classification results are used to determine the input data for the subsequent level's model.
- The system was integrated into a Django web server with a scrapy application to test its application in a functional environment. 
- The performance of the system was evaluated using metrics such as training loss, validation loss, F1 Score, and accuracy.

## Prerequisites

To run this project, you will need:
- Python
- Django
- BERT and DistilBERT models

## Results and Analysis (Subject to change)
At peak perfomance
- BERT hierarchical multi-class classification system: Overall Accuracy = 0.91
- DistilBERT hierarchical multi-class classification system: Overall Accuracy = 0.85
- BERT multi-class classification model: F1 Score = 0.805

The BERT hierarchical model demonstrated superior performance, with an overall accuracy of 0.91 compared to the F1 Score of 0.805 for the single BERT multi-class model. This result indicates that hierarchical classification can lead to improved performance in multi-class scenarios.

## Contributing
This project is currently not open for contributions. The sole contributor is Sean McManus.

## Full system models 
Full system models are available on request due to their large file sizes. This project demonstrates the code and methodologies used to achieve the creation and testing of the hierarchical multi-class classification models. 
![](https://hit.yhype.me/github/profile?user_id=59490455)
