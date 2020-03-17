# Optimization of Neural Network
>Comparison of 4 different optimization algorithm for Neural Network implemented in Tensorflow. 

***
Training a Very deep neural network is very time consuming. So, we use different technique to improve its speed. 
One of the technique is to use optimized Gradient descent algorithm. I used four algorithm for comparision, Simple gradient desent, Gradient desent with momentum, RMSprop and Adam Optimiser.
***
- Dataset - MNIST Fashion
- Running on Google Colab 
***
| Algorithm | Hyperparameters| Traning Time(sec)| Accuracy|
| ------------- | ------------- | ------------- |------------- |
| Simple gradient desent | *`learning_rate = 0.0001`* | 33.710| 0.857|
| Gradient desent with momentum |*`learning_rate = 0.0001`* <br>  *`momentum=0.9`* | 28.741| 0.955|
| RMSprop |*`learning_rate = 0.0001`* <br>  *`momentum=0.9`* | 30.405| 0.989|
| Adam Optimiser |*`learning_rate = 0.0001`* | 31.671| 0.987|

`Other Hyperparameters are default `
>Note - Training time and accuracy may vary on differnt hardware.
***
# Reference
[Gradient desent with momentum](http://proceedings.mlr.press/v28/sutskever13.pdf) <br>
[RMSprop](http://www.cs.toronto.edu/~tijmen/csc321/slides/lecture_slides_lec6.pdf) <br>
[Adam Optimiser](https://arxiv.org/pdf/1412.6980.pdf)  
[MNIST Dataset](https://www.kaggle.com/zalando-research/fashionmnist)
