# Music-Recommender-System-based-on-Emotion

Contributors:

<a href="https://github.com/shreesaraogi/Music-Recommender-System-based-on-Emotion/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=shreesaraogi/Music-Recommender-System-based-on-Emotion" />
</a>

This project aims to recommend music after detecting the emotion on one's face in real time. It detects the face of the user through web-cam, recognizes faces using OpenCV, detects the emotion using CNN. 

This application uses the Jupyter Notebook for the python programming language. The image recognition process used the OpenCV library by plotting the vector points of the faces by the HAAR Cascade method. The region of the image containing the face structure was resized to 48x48 and passed as input to the CNN. The boundaries for the system were the input of any number of playlists according to the user’s liking, then taking seven emotions of facial expressions under consideration. Then, the system will detect only one face at a time for the mood detection, then their facial structure will be recognized by the camera, and the valid expressions will be detected.

The dataset used to train the model is in CSV format and taken from Kaggle, FER2013. The data includes grayscale images of faces at a resolution of 48 by 48 pixels.

A CNN is a deep learning system that takes images as input and assigns significance to various attributes, allowing it to differentiate between them. Figure given below depicts the data flow diagram for the emotion detection model.

![image](https://user-images.githubusercontent.com/83531595/227741388-0494fa67-f17c-412d-b489-ec51f668f144.png)

The features of the user image are evaluated using a multi-layered CNN. The CNN is made up of an input layer, several convolutional layers, ReLU layers, pooling layers, dense layers (fully-connected layers), and an output layer. These layers are preserved in sequential order. Fig 2 represents the architecture of the CNN model of the proposed system.

![image](https://user-images.githubusercontent.com/83531595/227741415-e4aaec4b-e5c2-497a-95e1-8c02facb3ea5.png)

A total of 95,239 photos were used to train the final network, which was then evaluated using 24022 images. In the end, the model had a 95.6% accuracy rate.

We have used the desktop application “Windows Media Player” to play songs from the respective directories of the emotions stored on the local desktop.

Results:

![image](https://user-images.githubusercontent.com/83531595/227741539-c3e51a65-b6c2-4cfd-84e3-46b526229be1.png)

![image](https://user-images.githubusercontent.com/83531595/227741548-ec46d1bb-2a13-4e8e-a6a5-9ba6d80b2e25.png)

![image](https://user-images.githubusercontent.com/83531595/227741556-ea948f3f-3308-4c0f-aadf-a0067c85b91a.png)


In conclusion, we managed to develop a system that recognizes the person’s facial expression and thereby detects the mood/emotion to suggest the appropriate list of songs to uplift the person’s spirit. Throughout this process of creating the system, we learned about different algorithms like TensorFlow, OpenCV, FER, etc. to achieve our main goal and thereby help them to get through their current situation in a better way.
