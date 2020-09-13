# EfficientNetStyleTransfer

# Examples
<p align="center">
  <img src="images/atılım.jpg" width="512" height="512">
  <img src="images/starry_night_full.jpg" width="512" height="512">
  <img src="images/results/atılım%20van%20gogh.png" width="512" height="512">
</p>





# Credits
This is my first work on Neural Style Transfer. Since I have wanted to try doing this, I have checked several sources for examples. One of them  was: https://github.com/tensorflow/docs/blob/master/site/en/tutorials/generative/style_transfer.ipynb. As you can see, most of the functions are same since I did not know how to replace them YET. So they have to take most of the credit since I am still learning on this topic. As soon as I have the capacity to change those functions, I will replace them with my own code. Until then, all credits belongs to them.

# So, what did I do different than the examples, I have been looking for?
I have used a different model, I have preferred more complex model which is called "EffiencientNetB7". My main reason of doing this to see if I can get better and clear style transfer on process. In this project, Model has 10 times more layers than original example that I have checked and learned from. So as expected, The process takes more time when you use same steps and epochs. For 512px result, it takes like 5 mins or so. But i have changed resolution to 1024px (which is maximum depending on the specs of my colab account) to get better and clearer results. So with this change, it takes 15-30 mins to complete the process according to resolution of given images.

# So, what do you need to try this program?
Since I have used pre-trained EffiencientNetB7 from tensorflow library. You will have to use "tensorflow v2.3.0" or higher. Since anaconda is not supporting it YET. You have to use "pip" to install it on your environment.

# What I am going to do next with this project?
Since I want to learn more on this, I want to try:
* Style transfer with a mask 
* Multiple style transfer
* Style transfer on videos
but as I wrote before, I want to change the functions that I have taken from the example. So I am going to work on that before starting on this list.
