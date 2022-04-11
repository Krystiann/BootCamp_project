## Detection of emotions on the face with Keras module.


The aim of the project is to teach a deep neural network to recognize 6 basic emotions:
- Angry, Fear, Happy, Neutral, Sad, Surprise

My neural network will learn to detect emotions from pictures of different characters and people's faces. I will use a popular data set for training FER2013.

![Picture error](https://github.com/Krystiann/BootCamp_project/blob/main/pictures_of_emotions/face%20example1.png)

Originally there are 7 emotions in the dataset. Unfortunately, the data containing 'Disgust' is very unbalanced. That's why I decided to combine 'Disgust' with 'Angry'. The images of these two labels are hard to distinguish even for me.

Finally, my neural network is able to detect individual emotions in real time using a webcam.

## Effectiveness

The effectiveness of the learned network is around 52 %. Taking into account the difficult data and the very long learning time of the network caused by low computing power, in my opinion, the network fulfills its task.

![Picture error](https://github.com/Krystiann/BootCamp_project/blob/main/pictures_of_emotions/result1.png)

## Result

Below you can see that my neural network does its job quite well.


![Picture error](https://github.com/Krystiann/BootCamp_project/blob/main/pictures_of_emotions/merge2.png)
![Picture error](https://github.com/Krystiann/BootCamp_project/blob/main/pictures_of_emotions/merge3.png)
![Picture error](https://github.com/Krystiann/BootCamp_project/blob/main/pictures_of_emotions/newmerge1.png)

