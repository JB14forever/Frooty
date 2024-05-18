# Frooty

### Problem Statement 
##### The rise of Deep Learning has been accompanied by a sharp increase in the use of Convolutional Neural Networks and the prevalence of teachable machines to do the work. Convolutional networks were inspired by biological processes CNNs use relatively little pre-processing compared to other image classification algorithm. The correlation between Convolutional Neural Network and Training models is significant in Image recognition. Food image recognition is a unique branch of image recognition that aims to predict the correct name of fruits with images as input. CNN's are a very effective class of neural networks, responsible for image classification and prediction. Teaching a machine to do something like Image recognition seemed very intriguing to us. Moreover, there are countless real-world applications of this concept. It is in light of these reasons that we decided to work on Image Classification and Prediction using different Convolutional Neural Network and testing their accuracy with real-time data on an application named Frooty based on Flutter UI development kit, which predicts the name of Fruits using images. we used a common dataset, Fruits-360 to train our models and the results showed variations in predicting the fruit images. Specifically, the number of epochs and the number of layers in models contributed towards their efficiency, and the analysis favoured the VGG16 model as it predicted the most test cases correctly. The results suggest that the accuracy of Image Recognition can be increased by merging layers from different CNN models and using a more varied and unbiased dataset.

### Methodology Used 
##### Food image recognition is a unique branch of image recognition that aims to predict the correct name of fruits with images as input. CNN's are a very effective class of neural networks, responsible for image classification and prediction. The main objective is to determine how different models of CNN such as VGG16, ResNet50, InceptionV3, MobileNetV2 can be used to increase the efficiency of predictions in Food image recognition. The steps involved in our project are as follow, 
##### A. Input: Fruits Dataset
##### We have considered a common dataset named Fruits-360 for our project which consists of 131 varieties of fruits and vegetables. The images for training and test cases are also included in the dataset.
##### B. Set properties of different models in python code lab
##### With the use of keras imported with tensorflow in python code lab, we generated different model.tflite files by importing various different CNN’s that we are researching in this project and also by setting its training parameters such as the number of epochs, layers, steps, type of optimizer, training rate. 
##### C. Design the Application using Flutter Development Kit
##### We designed a mobile application named Frooty with the help of a Flutter UI development kit using Dart Programming and provided a presentable layout for the application. The coding part is done using Android Studio and necessary files and images were included in the asset folder.
##### D. Merge models with Application and Predict test cases The different model.tflite files generated were merged one by one and provided with test cases to test the prediction accuracy of different models when collaborated with the flutter application. The graphs for accuracy and loss of data were plotted based on the analysis.

### Flow chart for Frooty
![SS4](https://github.com/JB14forever/Frooty/assets/69258864/b43aabfa-23c8-4371-93fc-4dbc50f3cd61)

### Data Flow Diagram
![SS5](https://github.com/JB14forever/Frooty/assets/69258864/31a3817f-507a-4deb-b9ab-3ec427d3e722)

### Application Layout
![SS6](https://github.com/JB14forever/Frooty/assets/69258864/1e954f02-4b39-4257-833f-69fee05ad661)

### Fruit Prediction results
![SS7](https://github.com/JB14forever/Frooty/assets/69258864/c2f923d0-1f58-4aad-98f2-e20776c1fc45)

### Comparative Analaysis
![SS8](https://github.com/JB14forever/Frooty/assets/69258864/95ff1f09-50fb-49cf-975e-076846c51168)

### Conclusion
##### As you can see, CNNs are primarily used for image classification and recognition. The specialty of a CNN is its convolutional ability. The potential for further uses of CNNs is limitless and needs to be explored and pushed to further boundaries to discover all that can be achieved by this complex machinery. The Accuracy of the Image Recognition can also be increased by merging different layers from different CNN models and using more varied and unbiased Dataset. This project presents a method to use the CNN models in Flutter Application so that it will be used by people who are unaware about various fruits.

### Future Scope
##### If we are able to improve the accuracy of the model to nearly 100% we can set up a system in the app which after identifying the fruit will inform the user about the fruit's nutritional values, allergic advice and it will also warn the user if the fruit/vegetable is unfit for human consumption. This feature will be useful for people in day to day life as well as for people who wish to go on forest explorations.
