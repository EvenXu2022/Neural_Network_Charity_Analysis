# Neural_Network_Charity_Analysis

## Overview of the analysis
This analysis is to use deep-learning neural networks with TensorFlow to improve the model training accuracy.

## Resources
- Data Source: charity_data.csv
- Tools and Features: Python, sklearn, tensorflow

## Results
- Removing non-related columns "EIN" and "NAME" 
- Make sure all columns's Unique Keys are within 10 to reduce the data confusion. This requires to convert "CLASSIFICATION", "APPLICATION_TYPE".
- To optimize the model performance and accuracy, column "ASK_ATM" also needs to convert to reasonable buckets. In this model, BIN function has been appllied to reduce "ASK_ATM" uniques keys from 8747 to 3 buckets which highly improved the accuracy from 54.45% to 72.9%, and this also improves performance by removing noisy data.
- Adding neurons which can somehow improve the accuracy; however, adding hidden layers doens't seem help to accuracy. As a result, model includes 2 hidden layers, with 48 and 6 nodes.

## Summary:

As a results, this model reaches accuracy with 72.9%. Even though accuracy is not over 75%; however, it's still a big improve comparing with the model without converting the "ASK_ATM" column. To improve the model accuracy, we can add more data attributes and samples.

