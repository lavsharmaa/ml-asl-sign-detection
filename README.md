# ML Sign Detection (Digits 0 to 9)

## How to use it
- Download or clone the project using ```git clone https://github.com/lavsharmaa/ml-asl-sign-detection``` or fork the repo.

## Creating your own dataset
- ```collect-data.py``` is used for creating your own dataset.
- Run it using ```python collect-data.py``` it will show you a list of numbers from ```0 to 9```.
- Using the number you can create dataset. For example, if you want to create dataset of number ```0``` press 0 on your keyboard and perform the sign it will start capturing it.
- Similarly, you can do this for other numbers also and even for alphabets ```A to Z```.
- We followed ```80:20``` ratio. That means if there are ```100 images``` for digit ```0``` we placed ```80 images``` for training and ```20 images``` for testing. Higher the number of images in training and testing more accurate your model will be in detecting the sign.
- You can also download the [dataset](https://drive.google.com/drive/folders/1G9kt_aHeLWCddecxyAnRgdkgsOxPB3Hb?usp=sharing) that we have created.

## Training the dataset
- After you have successfully generated your dataset.
- Run ```python train.py``` to generate your model. It will take few mins and you will get your training accuracy.

## Predicting the sign
- Finally run ```python predict.py```, perform your sign into the webcam and see the output.

## Tools and Technologies
Food Corner is the web based project. Developed using 
* Python (3.7.4)
* IDE (Jupyter)
* Numpy (version 1.16.5)
* cv2 (openCV) (version 3.4.2)
* Keras (version 2.3.1)
* Tensorflow (as keras uses tensorflow in backend and for image preprocessing) (version 2.0.0)

## Team
* [Mansi Anantpurkar](https://github.com/mansayyy)
* [Lav Sharma](https://github.com/lavsharmaa)
* [Rutuja Bhate](https://github.com/rutuja1908)
