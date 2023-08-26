# Deep learning Exam:
### Answer and Implementation , Giacomo Colosio 509653, 23 June 2023 Session

The following document contains the link to the colab notebook with the
code for the proposed solution in the exam. The link is: https://colab.research.google.com/drive/1UbKpMQPOEYfaXppYh68uubDghe0UIxeq?usp=sharing.

Notably, the jupyter notebook also contains the theoretichal explanation
of the inserted code that was included in my solution. I want to specify
that I applied as few changes as possible except in a few parts where I had
some forgetfulness due to haste. The following document contains only an
index of the project , all explanations are contained in the notebook. The
unique informations contained in this text are the small variations added
with to respect of the exam. All the changements are also commented in the
notebook. In particular the jupyer notebook is organized in the following
way:

## 0. Contents

General Information About the Project
In this section i will have 3 subsection:
1. Input of the problem and Task to solve
2. Type of task
3. Solution architecture draft
    
## 1. Input
In this section i will have 4 subsection:
1. Import the input and libraries
2. Explorative data analysis: analysis of the data to choose the input
3. Preprocessing of the network input
4. Input of the network

## 2. Output
In this section i will have just the information about the output layer. In
particular, I applied a small correction. In fact in the exam I wrote that
the number of neurons in the ouput layer must correspond to the number of
classes present , which is correct but then I miscounted the number of classes
and had indicated 6 instead of 5 so I corrected it. So this section contain:
1. The output layer

## 3.  Activation and loss function
In this section i will have two subsection:
1. Activation function
2. Loss Function

## 4. Regularizers, Initializers, Normalizers, Dropout,
Optimizers, Learning rate, Batch size, Number
of layers, Numbers of neurons for each layers.
In this section, I will have 10 subsections, with a new subsection 4.9 titled
”Batch Size.” This subsection is being added due to an oversight in the exam.
Specifically, I included it because the batch size, particularly in the context
of deep learning, is a fundamental concept that cannot be overlooked. The
batch size refers to the number of training examples used in each iteration or
update of the model during the training process. Instead of processing the
entire dataset at once (batch gradient descent) or just one example at a time
(stochastic gradient descent), the mini-batch approach strikes a balance by
using a subset of the data. I will explicate better this concept in the notebook.
The subsection are:
1. Weight and bias regularizers
2. Weight and bias initializers
3. Batch Normalization
4. Dropout
5. Optimizers
6. Learning Rate
7. Batch Size
8. Number Of layers
9. Number of Neuron for each layer
10. Example of possible Solution in code

### 5. Hyperparameter selection
In this section i will have two subsection:
1. Number of layers selection by hand
2. Model tuning with grid search

## 6. Generalization capability of my model
At this point in review I was at the end of my rope and could not fit in exactly
what I would have liked. Specifically in my draft I extended the response by
dividing it into two sections. The first talks about how I can evaluate the
ability of my model to generalize to data I have never seen. The second (the
added one) instead consists of an evaluation of my model based on the use
of Confusion Matrix and the learning curve.
1. Technique used to test generalization capability
2. Model evalutation
