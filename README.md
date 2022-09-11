# Face-Mask-Detection

The input image is taken from the dataset. It consists of two major stages, the first stage of our architecture includes a face detector which localizes multiple image of varying sizes and detects faces in overlapping scenarios.
The detected faces from the region of interest is extracted from this stage and then branched together and passed to the second stage.
In second stage of our architecture, which is a convolutional neural network based Face mask classifier. The results from the second stage are decoded and the final output is the image with all the faces in the image is correctly detected and classified as either masked or unmasked faces.
There are some several methods used here:
1. Data Visualization : Data visualisation is the process of translating abstract or raw data into meaningful representations through knowledge exchange and insight finding through encoding. This is a very useful technique to investigate a certain pattern in a dataset.
The dataset is divided into two categories: photographs with face masks are labelled 'with mask,' and images without masks are labelled 'without mask.' The list of directories in the supplied path is then returned using the os.listdir method. ['with mask', 'without mask'] will be the variable names for the categories.
We need to differentiate such categories for labelling the photographs by looping through them using any looping expression. The labels will then be set to [0,1], and the photos will be reshaped and converted.
2. Training Of Model : The training of the model will be done by using CNN and it has also became the most ascendant in miscellaneous computer vision tasks.
This model will be built by using CNN architecture and training, testing and splitting the data will also be done by using convolutional neural network method(CNN).



![image](https://user-images.githubusercontent.com/91552411/180310119-a9f3706c-73f4-4737-9aeb-7864a41a0776.png)



STEPS TO RUN THE PROJECT

STEP 1 : Install python 3.7 or later version to run this application.

STEP 2 : Open cmd and clone the repository in your desired directory using the command " git clone (link of the repo)"

STEP 3 : Open cmd and change the directory to that folder in which the project is cloned and run the following commands to intall the dependencies "pip install -r              requirements.txt" after that run "python mask.py" to run the application.

STEP 4 : A diaglog box will open and the application will be ready to use

STEP 5 : Press ctrl+c in cmd to exit.





RESULTS 


The current proposed model provides greater individual accuracy face with mask on and off. For many faces and offers very good accuracy. 
Works easily on just about any mobile device by turning on video streaming, without external computer hardware requirement. 
In addition I will work to improve accuracy in order to get the most face mask, to divide the face into three categories namely, With Masks, Without Masks


![image](https://user-images.githubusercontent.com/91552411/180310602-6793dd43-32e6-47e1-b4b1-a5881d98613f.png)


![image](https://user-images.githubusercontent.com/91552411/180310737-143b9ba8-734c-4c4c-9d1b-37a0e33ebb22.png)

![image](https://user-images.githubusercontent.com/91552411/180310779-afd97697-41a4-4fd3-a0b3-9a3583b74e30.png)






To reduce the spread of the COVID-19 epidemic, steps must be taken. Show us a facemask detector using Convolutional Neural Network(CNN) and convey learning strategies to neural organizations. 
To train, validate and test model, using database featuring 993 and 1918 concealed facial images photos of exposed faces. These photos were taken different assets such as Kaggle database and RMFD. 
The model is made in photos and live video transfers. To choose a basic model, we checked the ratings such as accuracy, precision, and memory and selection MobileNetV2 architecture with the best display we have 99% accuracy and 99% memory. 
It is more than that using MobileNetV2 makes it easy to present the model to be installed structures. 
This face mask finder can be set at many regions such as shopping malls, air terminals and other large traffic areas for general population testing and to prevent 
the spread of the virus by looking at who is following important rules and who does not follow.


