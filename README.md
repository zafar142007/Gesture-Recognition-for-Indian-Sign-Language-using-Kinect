# Gesture Recognition for Indian Sign Language using Kinect
Indian Sign Language static gesture depth dataset
-------------------------------------------------
Download the dataset from the following link.

https://drive.google.com/drive/folders/0B6iDOaIw70SceUFWQ0NoREVIUTA?usp=sharing

Please cite the following paper if you use this dataset in your research.

_http://link.springer.com/article/10.1007%2Fs12046-013-0146-0_ (you can read it at _http://www.ias.ac.in/article/fulltext/sadh/041/02/0161-0182_)

This dataset consists of depth and RGB images (taken by Kinect XBox 360) of 140 sign language gestures of the Indian Sign Language taken from 18 subjects. There are a total of 5041 images each of resolution 640x480 in the depth and the RGB subsets. Each depth image has a corresponding RGB image.

Related video: https://www.youtube.com/watch?v=2oqD-_UCHxQ

This work was a part of my Master's thesis at Indian Institute of Technology, Jodhpur (2013).

Files have the name format:
'USER-XY-ABC-VZ.png' or 'USER-XY-ABC-VZ.txt'
XY, ABC, VZ are numbers. 
XY represents volunteer number.
ABC represents symbol number.
VZ represents trial number of the corresponding volunteer.
These numbers may be of 1, 2 or 3 digits.
Trial numbers may be discontinuous.  

  User	Number of Valid images  
  1&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;863  
  2&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;237  
  3&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;251  
  4&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;252  
  5&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;261  
  6&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;246  
  7&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;241  
  8&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;256  
  9&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;240  
  10&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;239  
  11&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;217  
  12&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;258  
  13&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;231  
  14&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;219  
  15&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;230  
  16&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;259  
  17&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;261  
  18&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;280  
  
  Symbols' meanings are provided in the vocabulary folder according to their number.
  
  Each depth image is a matrix of size 640x480 having values in the range [0,2047] which correspond to real world depths according to the Kramer formula [1].  
  
[1] Kramer J, Parker M, Herrera D, Burrus N and Echtler F 2012 Hacking the kinect. Apress  
