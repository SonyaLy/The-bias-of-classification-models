# Analysis  of approaches  to assessing the bias of classification models
## Introduction

The purpose of the study is to improve the performance of a biased model for classifying malicious and benign web pages based on fairness metrics. The subject of the study is the assessment of the bias of a binary classifier based on fairness metrics. Tasks to be solved in the course of the study:

1.	Research of existing mathematical definitions of the concepts of bias and fairness of machine learning models.
2.	Classification of biases that occur in machine learning models and identifying the cause of their occurrence.
3.	Examining of existing approaches to assessing the bias of models.
4.	Training a binary classification model of web pages on a biased sample and applying bias elimination algorithms to it.
5.	Evaluation the values of performance metrics and bias of the trained models and draw conclusions about the quality of their work.

As a result of the work, a tool was implemented that allows assessing changes in equity indicators in the process of developing a classification model and comparing models in terms of equity indicators with each other. The operation of this tool was demonstrated on a model for classifying malicious and safe web pages. The obtained results can be used as a basis for integrating the fairness assessment into the learning process of classification models.


dataset: SINGH, AMIT KUMAR (2020), “Dataset of Malicious and Benign Webpages”, Mendeley Data, V2, doi: 10.17632/gdx3pkwp47.2


## Machine learning workflow and problems that may arise
Understanding the causes of bias is an integral aspect of studying this problem
![Bias](https://github.com/SonyaLy/The-bias-of-classification-models/blob/main/Machine%20Learning%20Workflow.jpg)

## Comparison of models (results)
![Results](https://github.com/SonyaLy/The-bias-of-classification-models/blob/main/Result.png)

## Conclusion
In this final qualifying work, definitions of the concept of model bias were given, metrics used to measure bias in the process of machine learning were considered, the causes of injustice were classified, and also interpreted in the field of information security. The main measures of discrimination in classification are experimentally analyzed.

Based on the results of the work, it was possible to identify the presence of bias in the data set of malicious and secure web pages, and as a result, in the trained models themselves. It was possible to do this with the help of a developed tool, which also helped to make a comparative analysis of all trained models.

In the modern world, the considered problem of discrimination in the process of machine learning is gaining increasing relevance, developers from the field of artificial intelligence are conducting numerous studies of biases of algorithms and training data, developing new ways to exclude discrimination from the developed and already existing models. But it was also revealed that not every approach to eliminating bias can be effective for a specific task, so it is important to analyze changes in metrics.

Therefore, it is recommended to integrate equity assessment into the modeling process as a form of continuous process improvement. By regularly evaluating several equity indicators at once, you can make sure that they continue to meet the expectations of stakeholders. Just such an audit tool was developed, thanks to which it is convenient to see how the indicators change relative to the model change.
