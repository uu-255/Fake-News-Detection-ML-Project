# Fake News Detection ML Project

We followed your suggestions and tested different regularization strengths for SVM and different maximum tree depths for Random Forest.

Changing the C parameter did not significantly improve SVM validation accuracy. However, limiting the number of TF-IDF features to 500 increased its accuracy to about 61%.

For Random Forest, setting the maximum depth to 10 improved validation accuracy from about 57% to 61%.

We think both feature representation and model complexity may be contributing to the performance differences.
