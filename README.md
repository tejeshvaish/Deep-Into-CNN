# Deep Into CNN

This Repo Contains the work done by me in the self project Deep into CNN

## Work done

- First 2 Weeks Learned the basics of Regression , ML, Gradient Descent and completed few exercises on common dataset. 



- in the weeks 3 and 4 , Learned about Neural networks and pytorch framework, made some simple Neural network to classify data. 

## Implemented a simple CNN architecture using pytorch  containing 2 Conv layer and 2 pooling layers + one fully connected layer to classify cifar dataset  achieved an accuracy of 69% on it.

![image](https://user-images.githubusercontent.com/55567070/125914902-37473baa-da02-4539-ab2d-f0866cc24bf4.png)


## Then went on to Vislualize a CNN architecture , that what happens to input layer after maxpooling , convulutional , basically how do CNN are doing the magic

* Filter Visualization:
![image](https://user-images.githubusercontent.com/55567070/125914181-5ef29d49-64a8-4bd6-8102-fac790146867.png)


* CNN layers visuluatlization :
![image](https://user-images.githubusercontent.com/55567070/125913831-aef299c6-5026-423d-9896-5ca5f906f060.png)
![image](https://user-images.githubusercontent.com/55567070/125913882-1c06f13d-cd91-4efc-a0f9-462b99577a03.png)


* Maxpooling visulaization :
![image](https://user-images.githubusercontent.com/55567070/125913992-2e204f47-0687-4cb9-8e56-f377dda86dfd.png)



##  Implemented LeNet architecture
Using pytorch , and used binary cross entropy as loss function and SGD as optimizing algorithm trained it on MNIST dataset and  then hypertuned the parameters.
![image](https://user-images.githubusercontent.com/55567070/125914506-4b14841c-40b9-435e-90ab-6d3bb46e5da1.png)


# In the last two weeks I implemented AlexNet Architecture. 

* imported the CIFAR-10 dataset from the pytorch utilities. 
*  Then loaded it using transform library , augmented it . , splitted it into traning and testing parts. 
*  Implemented the Main architecture of Alexnet 
  ![image](https://user-images.githubusercontent.com/55567070/125919870-b738baf1-4cde-4695-a658-9ac3ba1b60e0.png)
* Then wrote the Dropout and FC layers at the last. Dropout layers helps in reducing the complexity of the features. 
![image](https://user-images.githubusercontent.com/55567070/125919957-7af361d5-67dc-4535-997b-a0a4f40645c8.png)
 * wrote the optimizer (SGD) and used binary cross entropy as the loss function . Then trained the model on Cifar datset and got  the *89%* accuracy on it .
 
 



##  These were the resources used by me while doing the project. 


## Resources

### Week 1 : Regression( Skip if you are confident )

#### Readings
1. Local Setup (Use Conda : recommended)  
https://jupyter.readthedocs.io/en/latest/install/notebook-classic.html
https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html#installation  
2. (Optional: Basic Python and libraries) https://duchesnay.github.io/pystatsml/index.html#scientific-python  
3. ( Optional : For those with very basic ml knowledge: Only 2.1-2.7) https://www.youtube.com/watch?v=PPLop4L2eGk&list=PLLssT5z_DsK-h9vYZkQkYNWcItqhlRJLN
4. Linear Regression:  
 https://medium.com/analytics-vidhya/simple-linear-regression-with-example-using-numpy-e7b984f0d15e  
5. Logistic Regression:
https://towardsdatascience.com/logistic-regression-detailed-overview-46c4da4303bc  

#### Practice Material
Find in [NeuralNetIntro](W2-3/NeuralNetIntro/) : W2-3.

### Week 1-2: Neural Networks

#### Readings
1. This one is highly recommended:  
https://www.youtube.com/playlist?list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi   
Some more material (bit extensive, so be careful):  
https://youtube.com/playlist?list=PLtBw6njQRU-rwp5__7C0oIVt26ZgjG9NI
2. Basic Backprop:  
 https://ml-cheatsheet.readthedocs.io/en/latest/backpropagation.html 
3. Backprop (Mathematical Version):  
https://mattmazur.com/2015/03/17/a-step-by-step-backpropagation-example/
4. Softmax:  
https://ljvmiranda921.github.io/notebook/2017/08/13/softmax-and-the-negative-log-likelihood/
5. Pytorch(Skip the CNN part if you want for now):  
https://pytorch.org/tutorials/beginner/basics/intro.html
6. Optional guide:  
http://neuralnetworksanddeeplearning.com/chap1.html

#### Practice Material
Find in [PyTorch](W2-3/PyTorch) : W2-3.
