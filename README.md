# FCN-KERAS


What is Semantic Segmentation?

![image OUWDW1](https://user-images.githubusercontent.com/99510125/204311464-aff36e84-6684-417e-b67b-e3cc6f04cf1c.png)


Also known as dense prediction, the goal of a semantic segmentation task is to label each pixel of the input image with the respective class representing a specific object/body. Segmentation is performed when the spatial information of a subject and how it interacts with it is important, like for an Autonomous vehicle.  
Also, one key thing to note is that this task is not interested in distinguishing multiple objects belonging to a certain class. For example, if you have two cars of different make and color, they would still be given a common label of ‘Car’ and considered a single entity. 

What are FCNs?
 
FCNs, or Fully Convolutional Networks, are a form of architecture that is primarily used for semantic segmentation. Convolution, pooling, and upsampling are the only locally linked layers they use. Since dense layers aren’t used, there are fewer parameters (making the networks faster to train). It also means that an FCN can handle a wide range of image sizes since all connections are local. 

![1_5vIoi8Gf7ptJZ94SpeYwqg](https://user-images.githubusercontent.com/99510125/204311624-90eef90d-ec03-4844-97a3-9c36eff52960.png)
