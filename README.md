# Solving MNIST with Pytorch  

## Description 

The “hello world” of object recognition for machine learning and deep learning is the MNIST dataset for handwritten digit recognition. The MNIST problem is a dataset developed by Yann LeCun, Corinna Cortes and Christopher Burges for evaluating machine learning models on the handwritten digit classification problem.

## Files 

- mnist.ipynb: a Logistic Regression solution and a Neural Net solution
- mnist_class.ipynb: has the same Neural Net solution as above but written in a python class 
- minist.py: contains the python from mnist_class.ipynb written regular python - no jupyter/markdown
- mnist.pt: p retrained model
- environment.yml: 

## Environment 

The code was developed in a conda environment and test on an Ubuntu & OSX system. The conda environment can be reproduced using the following: 

```bash
$ conda env create -f environment.yml
$ conda actviate pytorch
``` 

If you already have an environment with the name pytorch you can set a new name with the following.

```bash
$ conda env create -f environment.yml -n new-env-name
```

You may have to run the following for jupyter to see the new environment. Note if you changed the environment name per above
you need to replace 'mnist' with the name you created. 

```bash
$ python -m ipykernel install --user --name=mnist
```
