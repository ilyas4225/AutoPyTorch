# AutoPyTorch
AutoPyTorch is an open-source library that automates the architecture search process of deep neural networks. It provides a modular pipeline architecture that can be used to construct customized machine learning pipelines for classification, regression, and other tasks.


## Requirments  

 ```
!pip install autoPyTorch
```
## Notebook description
The Cifar10 notebook ['[autoPytorch_examples.ipynb'](https://github.com/ilyas4225/AutoPyTorch/blob/main/autoPytorch_examples.ipynb)] contains the tabular classification task with digits dataset, wine quality dataset , and with cifar10 dataset.

The notebook ['[Iris_Tabular_Classification.ipynb'](https://github.com/ilyas4225/AutoPyTorch/blob/main/Iris_Tabular_Classification.ipynb)] contains the tabular classification task with Iris dataset and visualization of the model performance.



 A Python file in the repository ['[Cifar10.py ](https://github.com/ilyas4225/AutoPyTorch/blob/main/Cifar10.py)] contains the  code for Autopytorch image classification pipline with cifar10 datadset.


To Run this code the command is as

 ```
python.Cifar10.py
```

The purpose of this code is to demonstrate how to create and train an image classification pipeline using the autoPyTorch library. By performing this demonstration on the CIFAR10 dataset.




## Results and Discussion
#### Tabular Classificaton with Cifar10
Here is the obtained statiscs of autoPyTorch tabular classification on cifar10

```
{'accuracy': 0.0955}
autoPyTorch results:
	Dataset name: 48915da4-d2cb-11ed-bb0a-0242ac1c000c
	Optimisation Metric: accuracy
	Number of target algorithm runs: 26
	Number of successful target algorithm runs: 0
	Number of crashed target algorithm runs: 0
	Number of target algorithms that exceeded the time limit: 0
	Number of target algorithms that exceeded the memory limit: 26
```


Here is the Obtain statistics from the tabular Classification task Iris dataset

```
autoPyTorch results:
	Dataset name: 9949b5d2-d448-11ed-82e1-0242ac1c000c
	Optimisation Metric: accuracy
	Best validation score: 0.9459459459459459
	Number of target algorithm runs: 30
	Number of successful target algorithm runs: 13
	Number of crashed target algorithm runs: 16
	Number of target algorithms that exceeded the time limit: 1
	Number of target algorithms that exceeded the memory limit: 0
```
Accuracy 

