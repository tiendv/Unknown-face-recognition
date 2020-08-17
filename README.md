# Unknown-face-recognition

Face recognition is a method of identifying or naming individuals/group using the features extracted from face. As an output of face recognition, a bounding box is drawn on the face and the name of the face is displayed. Face recognition is widely used in many applications like biometric, surveillence etc. But one of the main problem in face recognition is the poor performance in recognizing unknown faces. Unknown faces are the faces that are not used either in training or testing. Most cases, the trianed face recognition model, recognizes an unknown person as one of the trained faces. To overcome this issue, Openset classification approach is followed.

## How to use ?

To use the repository either clone or download and run it in local machine or you can set this up in google colab. First lets see how to run in local machine.

### How to run in local machine
To run in local machine please make sure you have all the below packages installed in the your virtual environment
Required packages to run in local machine:
 1) Python 3.7.7
 2) Matplotlib 
 3) Cython>=0.17
 4) Tensorflow
 5) Opencv
 6) MTCNN 
 7) EVM
 8) numpy
 9) sklearn
 
 ```
  pip install matplotlib==3.3.1
  pip install Cython== 0.29.21   
  pip install tensorflow== 2.3.0 
  apt-get install python-opencv
  pip install MTCNN
  pip install EVM
  pip install numpy
  pip install sklearn
  ```
    

  
### How to run in local machine?

Clone/download the repository and extract the folder. Then use "cd ./unknown-face-recognition" to get inside the folder. The repository already has some train and test folders inside Mini_casia.zip file. Unzip the folder. The structure of the train and test folder is shown below,

```
Mini_caisa

Train
|____ tarantino
|
|____ mille
|
|____ hank
|
|____ neve
|

Test
|____ tarantino
|
|____ mille
|
|____ hank
|
|____ neve
|
```


How to run in Colab?


  
  
  
  
  
