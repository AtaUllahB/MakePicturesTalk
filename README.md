The concept is to create an AR based android application using image processing and machine learning techniques, that makes a still image of Pakistani heroes, that were a part of Independence Movement of Pakistan, look like they are talking with audio generation and lip movements synced over that audio.

<strong> Step1: Recognition: </strong>

<img src="https://github.com/AtaUllahB/MakePicturesTalk/blob/master/three_Trim.gif?raw=true">

<strong> Step2: Output</strong>

<img src="https://github.com/AtaUllahB/MakePicturesTalk/blob/master/one_.gif?raw=true">




Augmented reality (AR) takes the objects of the real world and ‘augment’ them i.e., creating a sense of reality out of the computer-generated idea of the world. AR is basically a reality-based interactive environment which takes information of the world like audio, video, effects etc., and processes it to enhance the user world’s experience. AR in learning and education sector has proven to be very efficient as it is being used by teachers to explain the course contents, take quizzes etc. The idea is to develop an AR based android application using image processing and machine learning techniques, that brings images to life which enhances the learning process and provides a better learning experience regarding the Independence Movement of Pakistan. Personalities, telling their history and life’s work along with their sacrifices and achievements, makes the application overall attractive and it’s a fun way to learn the history. The main inspiration behind our project was the mainstream use of different applications by our youth. Research has found that most people spend a very significant part of the day interacting with different applications. It gives them an element of joy and enhances various features. By taking that idea we moved forward with creating something that would help the youth not waste those hours on these applications but also spend it in learning something new. Our project would help people learn about Pakistan's history, our culture and roots and it will help people gain knowledge about the people behind the formation of our country, especially when the famous personalities are themselves telling their tales.

The application begins by detecting a face in a still image and recognizes it by using a neural network. Once recognized, the image is fed to the Generative Adversarial Network(GAN), which is one of its two inputs. The other input is an audio file that is in the database against the ID of the recognized face. Once the second input, the audio, is fed as well, the GAN then creates multiple copies of that image, based on the length of the audio, with slight fluctuations of facial landmarks specifically the lip region to make it look like its moving. In the end, it gives an output of a video in which the images move frame by frame smoothly synced over the given audio file.

https://sites.google.com/u/0/s/1jGNqUe8nj1KCYvE_Bwkbn8G0vly4fCXV/p/1Vc4QUsV-YI--3L6sG2ElRtEEhMpuz4W9/preview

