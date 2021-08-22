# Autonomous-self-driving-car
Built an end to end pipeline from raw pixel camera images as input to predicting the steering angle as output to autonomously steer a vechile on road. 
Video presentation link: https://youtu.be/P_mOMtgttw0
<img src="https://github.com/jkenavdekar/Autonomous-self-driving-car/blob/main/Let's%20Start!.png" width="400" height="200">

The model architure used was: Nvidia CNN architecture. The network has about 27 million connections and 250 thousand parameters.

<img src="https://github.com/jkenavdekar/Autonomous-self-driving-car/blob/main/cnn-architecture-624x890.png" width="300" height="400">

Simukator env: Carla open source simulator: https://carla.org/ to simulate realistic driving conditions

Data augmentation was used to drastically improve the performance of self drive car on previously unseen tracks.

