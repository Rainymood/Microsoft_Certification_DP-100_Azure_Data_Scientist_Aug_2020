![](./badges2.png)

# Azure Data Scientist

This repository contains my notes for preparing the exam [DP-100: Designing and Implementing a Data Science Solution on Azure](https://www.microsoft.com/en-us/learning/exam-dp-100.aspx). If you pass this course you become a **Microsoft Certified Azure Data Scientist Associate**.

The exam consists of roughly 60 questions, 45 of which are Q&A and 15 represent a usecase. You have 3 hours (180 minutes) to answer all the questions. 

Most of the questions in the exam can be broken down into four separate categories:
* Azure ML studio (modules, autoML, designer, etc.)
* Azure Products (Databricks, Data Factory, Virtual machine, etc.)
* Machine learning (PCA, Correlation, metrics, cross-validation, etc.)
* Python (scikit-learn, pandas, etc.)

Here is an overview of the study material I used and recommend.

## Azure ML Studio

Almost every question regarding Azure ML Studio / Azure ML Designer (preview) is about its modules and how to use them. I highly suggest going through the list of modules which can be found [here](https://docs.microsoft.com/en-us/azure/machine-learning/algorithm-module-reference/module-reference) in the Algorithm & Module reference page. 

First thing to do is to explore Azure ML Studio and some of its modules. I recommend following this tutorial on [automobile pricing](https://docs.microsoft.com/en-us/azure/machine-learning/tutorial-designer-automobile-price-deploy), which provides an overview of all the modules and explains how to build and deploy your first machine learning pipeline. 

Note that some modules are **far more important for this exam than others**. In the file `Machine Learning Studio/Relevant_modules.md`you will find a list of modules you **must** be familiar with, as there will be a very high probability that these will be asked in the exam.

For the exam, most of the time you just need to know the module and what it is used for, but for some modules you will get questions on how to configure them and specify its parameters. 

In an ideal world, you should go through the [list](https://docs.microsoft.com/en-us/azure/machine-learning/algorithm-module-reference/module-reference) of modules and understand each and every module's purpose and how to use it, but you do not need all of them for the exam. A solid strategy to move forward is to study dumps of exam questions and to experiment with the modules that you find there. 

## Azure Products

## Machine Learning & Python

## Other resources

* [Alex Nogue's learning repository](https://github.com/alex-nogue/Microsoft_Certification_DP-100_Azure_Data_Scientist)