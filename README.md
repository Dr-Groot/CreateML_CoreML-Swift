# CreateML-CoreML-DogCat-Swift

## CreateML

Use Create ML with familiar tools like Swift and macOS playgrounds to create and train custom machine learning models on your Mac. You can train models to perform tasks like recognizing images, extracting meaning from text, or finding relationships between numerical values.

![image](https://user-images.githubusercontent.com/63160825/215262377-5fdd3cfb-0ac0-4133-996b-b6551780544c.png)

You train a model to recognize patterns by showing it representative samples. For example, you can train a model to recognize dogs by showing it lots of images of different dogs. After you’ve trained the model, you test it out on data it hasn’t seen before, and evaluate how well it performed the task. When the model is performing well enough, you’re ready to integrate it into your app using Core ML.

![image](https://user-images.githubusercontent.com/63160825/215262392-c720b801-5474-4bfa-bcb4-bcb1bd60824a.png)

Create ML leverages the machine learning infrastructure built in to Apple products like Photos and Siri. This means your image classification and natural language models are smaller and take much less time to train.

Now we will create a ML model using CreateML,

First open CreateMl and select **Image Classification** option and provide a name to your model.
![Screenshot 2023-01-28 at 4 04 32 PM](https://user-images.githubusercontent.com/63160825/215262529-13a75e48-2238-416b-b89f-fda4b9174572.png)

After that we will jump to a screen like this, here we have to provide data for creating a model. We are using data that contains Dogs and Cat images, also you can see in the console that we have to provide two type of data first is **Training Data** and second is **Testing Data**. Training data is used to train a ML model and Testing data is used to test our ML model that we have created. Next we will provide data to respective places.
![Screenshot 2023-01-28 at 4 05 49 PM](https://user-images.githubusercontent.com/63160825/215262556-d737d865-3f87-4733-b9c5-40ab264f157b.png)

Now you can see that we have 2 classes and 24 items in training and for testing we have 2 classes and 8 items. Next is we have to start training the model.
![Screenshot 2023-01-28 at 4 06 37 PM](https://user-images.githubusercontent.com/63160825/215262781-b1c97429-ffae-4978-98d6-4729fce0420d.png)

Model training strated.
![Screenshot 2023-01-28 at 4 07 56 PM](https://user-images.githubusercontent.com/63160825/215262985-088a5c02-c231-4c2e-8986-541883917e51.png)

After completion we have our evaluations which shows we have successfully trained the data and test it with 100% precision in each cases.
![Screenshot 2023-01-28 at 4 11 48 PM](https://user-images.githubusercontent.com/63160825/215263042-ee23c8d2-35ee-4741-b039-57e4b0ba1c82.png)

Now your model is ready to download.
![Screenshot 2023-01-28 at 4 12 08 PM](https://user-images.githubusercontent.com/63160825/215263054-7b910cc4-75c2-4c29-8395-803692108ecc.png)


## Project

In this project we are using same model which we have created and here we can select image via gallery or by camera.
![IMG_1982](https://user-images.githubusercontent.com/63160825/215263340-e11dcae0-17b9-4d3c-a0ae-ecbe1b12531a.PNG)

After selecting the image we get our results in the form of confidence percenetage form
![IMG_1983](https://user-images.githubusercontent.com/63160825/215263395-1c027434-7d5a-46c6-96a2-454b61cc4d17.PNG)

> To know more about CoreML working you can check my CoreML Object Detection project on github.

