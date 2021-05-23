
About the project:

- The goal of this project is to extract the average tempearture from a thermal video. It is useful in the present situation as if the average temperature of a person
is above a certain threshold, then that person may have to be sent for Covid testing.

- We have been given a dataset which contains thermal videos of people. We have to extract the average temperature of the person from the video.

- For this task we have trained various models on the MNIST dataset which will be useful in classifying the digits.

Structure of Code:

We have 5 files in the submission folder. These include:

1. Random Forest.ipynb

About the File: In this file, we have coded a Random Forest Model on the MNIST dataset and also tried to optimize its parameters and
evaluate its performance.

2. Support Vector Machine.ipynb

About the File: In this file, we have coded a Suppport Vector Machine Model on the MNIST dataset and also tried to optimize its parameters and
evaluate its performance.

3. Multi-Layer Perceptron.ipynb

About the File: In this file, we have coded a Multi-Layer Perceptron Model on the MNIST dataset and also tried to optimize its architecture to get
optimal performance and also evaluate its performance on the test data.

4. Convolutional Neural Network.ipynb

About the File: In this file, we have coded a Convolutional Neural Network on the MNIST dataset and also tried to optimize its architecture to get
optimal performance and also evaluate its performance on the test data.

5. Execution.ipynb

About the File: In this file, we have built the pipeline which helps to read the video from its adress and then extract the average temperature from 
the video using the models trained in the above files.

* We have also given an outputFile.csv. It containes the summary of the temperatures predicted by the different models on the videos in the original dataset.
We have also computed the mean squared errors for each model in this csv file.

Process of Execution:

The following process can be followed for execution of the above mentioned files:

1. Train the models using the files 1-4 using the numbering above. This will create trained models on the MNIST dataset
2. Run Execution.ipynb. After the models are trained, use these models to extract the average temperatures in this file.

***