
## Introduction
Main idea of this project is to successfully classify intel landscape image dataset. This dataset consists of 6 different landscapes namely; **buildings, streets, glaciers, forests, deserts and sea** and I'm going to use **Convolutional Neural Networks (ConvNets)** machine learning method to classify these images **as fast as and as accurate as possible.**

Convolutional Neural Network is **special type of Artificial Neural Network (ANN)** structure.
What separates Convolutional Neural Networks from Artificial Neural Networks is state of art structure of **ConvNets that is specifically created for image classification and related tasks.** Unlike ANN's fully connected network structure, **Cluster of Convolutional Layers is the core of ConvNets.** and it is the main engine to squeeze the images into processable size and structure. Not surprisingly, this unique structure boosts computational capability of ConvNets during image classification tasks when it compared to ANN.


* **Dataset**: Intel image dataset includes 6 different landscape images with 150x150 size.


* **Inspiration**: Accurately classify as much as image possible with robust machine learning.


* **Problem Definition**: Building Convolutional Neural Network model to obtain high accuracy.


* **Link**: https://www.kaggle.com/puneet6060/intel-image-classification


## Approach
* **0.Explanatory Data Analysis**: Understanding the dataset and check class imbalance.


* **Convolutional Neural Network**: Creating **ConvNets model** for the problem.


* **Hyperparameter Tuning**: Optimizing **hyperparameters** of the ConvNets model to achieve better results.

## Models
* **ConvNets**:  **Variants of ConvNets** models.



![Screenshot](../images/m4_acc.png)

![Screenshot](../images/m4_loss.png)



3000/3000 [==============================] - 1s 461us/sample - loss: 0.6773 - acc: 0.8687

![Screenshot](../images/cm_5.png)

## Results

At the end of this project, I tried different approaches to be able to classify intel landscape image dataset as accurate as possible. I used **ConvNets** to tackle this problem. To **avoid overfitting** I utilized **L2 Regularization (Gaussian Prior/Ridge) along with dropout and data augmentation.**

Finally, designed deep learning model is able to **classify landscape images with around %87 success rate.**

As next step, one can change deep learning structure, making model deeper or shallower, including average or sum pooling approaches. In addition, one can also try out different optimizer such as Stochastic Gradient Descent or Adagrad with optimizing learning rate and epochs.




