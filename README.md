## 🧮 Workflow of project

# Dog-Cat-Recognition- 
**Convolutional Neural Network**

A Convolutional Neural Network ( ConvNet /CNN) is a **Deep Learning** algorithm which can take in an input image, assign importance (learnable weights and biases) to various objects in the image and be able to differentiate one from the other. 

The architecture of CNN is similar to what our brain functionality happens .
A convolutional neural network is used to detect and classify objects in an image.

A ConvNet is able to successfully capture the Spatial and Temporal dependencies in an image through the application of relevant filters. The architecture performs a better fitting to the image dataset due to the reduction in the number of parameters involved and reusability of weights.

The role of the ConvNet is to reduce the images into a form which is easier to process, without losing features which are critical for getting a good prediction. This is important when we are to design an architecture which is not only good at learning features but also is scalable to massive datasets.

The convolutional neural network is built on three primary layers, which are:

Convolutional Layer
Pooling Layer
Fully Connected Layer


*Convolutional Layer:*

The convolutional layer is the heart of CNN’s, it does most of the work in identifying the features in the given image. Then in the convolution layer, we consider square blocks of some random size of the input image and apply the dot product with the filter(random filter size). If the two matrices(the patch and the filter) have high values in the same positions, the convolution layer output will be high(which gives the bright side of the image).

*Pooling Layer:*

In Pooling Layer we need one more operation which downsamples the image. Hence to make the learning process easy for the network, the pixel values in the arrays are reduced by using the "pooling" operation. 


*Fully Connected Layer:*

The fully connected layer (FC) operates on a flattened input where each input is connected to all the neurons. These are usually used at the end of the network to connect the hidden layers to the output layer, which help in optimizing the class scores.





Accuracy is above 85%.
The application will output whether the image uploaded is of Cat or Dog.
Application is deployed on various cloud platform

●Heroku

●AWS 

●Azure

Live application on Heroku link-

https://cat-dog-recognition-aj.herokuapp.com/

Training done on 1000 images of cats and same for dog for train and another 1000 images as validation data.
Dashboard Interface -

![Screenshot (86)](https://user-images.githubusercontent.com/90152799/178048515-71057665-9022-4862-9a55-3101dc9f3e05.png)


After Uploading Image it Classified the Image and gave the output as either Cat/Dog.



![Screenshot (87)](https://user-images.githubusercontent.com/90152799/178048637-93fe69e8-9c5d-4746-99ec-17ea1d792951.png)

![Screenshot (88)](https://user-images.githubusercontent.com/90152799/178048862-ec9ecb5f-4ad5-4159-966e-b3158a4e5983.png)



Want to contribute in this ?

Just raise an issue and start working .

If you liked my work on this project, do ⭐ and share this repository.

🎉 🎊 😃 Happy Contributing.Keep Learning 😃 🎊 🎉

