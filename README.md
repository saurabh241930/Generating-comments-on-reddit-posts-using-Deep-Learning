# RoastMe_BOT


In this project I have created the Reddit Roastme data based model that generate roasts given the input image using Deep Learning

We trained reddits posts images along with top 10 comments correspond to it.

For image part we used **`VGG`** CNN-model to extract image features & for text part we used **`LSTM`**  we combined these both neural network with **`Keras Functional Api`**

I've also written a whole [medium post](https://medium.com/@sp241930/creating-reddits-roast-me-ai-roaster-bot-13eabeb93e2f) of making this project

Libraries & packages used here:

* Keras Deep learning Framework
* Reddit Api
* Python

We gone with **keras functional api** because we have to deal with image & text data and added them

## 1st approach

![](https://miro.medium.com/max/700/1*eXHuTqiRc1f6fKjOVKEgxQ.png)

for this approach the neural network we used is this

<img src="https://i.ibb.co/ZcvP0kg/Whats-App-Image-2019-07-17-at-10-59-44-PM.jpg">

### Here are some of the results

![](https://cdn-images-1.medium.com/max/800/0*9MmWcpJSkZ8a-Qb4)
![](https://cdn-images-1.medium.com/max/800/0*iAAcJaAEI9betVeM)
![](https://cdn-images-1.medium.com/max/800/0*JS8ZpriBNa30fkN0)
![](https://cdn-images-1.medium.com/max/800/0*zIh0ANoMt-uetga9)

## 2nd approach

we combined title text and image as a input

<img src="https://i.imgur.com/pjUIFo1.png" border=0>

for that we used this neural network


<img src="https://i.imgur.com/QwFkxHJ.jpg" border=0>


### results for 2nd approach

<img src="https://i.imgur.com/2XJoaFG.jpg" border=0>
