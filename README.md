# Transfer-Learning-with-VGG16-for-Face-Mask-Classification for Three Classes of Mask, No Mask and occluded Maskf

!!Face Mask Detection Model!!

Overview:

This repository contains a model based on the VGG16 pretrained model designed for face mask detection. The model is trained using our proprietary image dataset.

Datasets

We used our in-house dataset for training, comprising of thousands of images to be used for training and testing purposes. It contains many mixed images of people with and without masks on so that the AI can reliably identify whether someone is wearing a mask or not. To improve on this, we also inserted a few images that contained people wearing a mask, albeit incorrectly; these images serve as more useful training for the AI to more accurately identify whether or not someone is wearing a mask, not wearing a mask, or wearing a mask incorrectly. The datasets are available in the shared file named 'Datasets' on GitHub.
[You need to mention the numbers of images and talk about the distrubution of the images for different classes, for emample are these datasets balanced or imbalanced]

Model Architecture

The Convolutional Neural Network (CNN) is implemented using the pretrained VGG16 model (on ImageNet), but using a different combination of layers to achieve the correct outcome. The architecture incorporates various layers such as Dropout, Flatten, and Dense layers. Additionally, there were many different optimizers used to help with the assessment of images [name the exact optimizer that you used for the optimization]. This combination allows the model to effectively process images and make accurate predictions. 

Training and Test Results
[update the training and test results and the plots if applicable]
 
To Be Added

Model Performance

Upon completion of training and testing, the model achieved an accuracy of approximately 80% and a loss of 0.60. Continuous efforts are being made to enhance the model's performance.

Feel free to explore the code and contribute to the improvement of the face mask detection model!


