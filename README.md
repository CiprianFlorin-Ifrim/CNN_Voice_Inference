## Voice Recognition for Nano 33 BLE Sense/XIAO BLE Sense

This repository includes different versions of Edge Impulse trained Convolutional Neural Network Models, able to recognise between 7 to 12 voice commands (depending on the version). Every folder includes the library files with example code for Arduino, able to be used on 2 devices: Arduino Nano 33 BLE Sense and Seeed Xiao BLE Sense.
Every folder version also includes information about the models, such as architecture, training setting, feature space and confusion matrix.

The code folder contains a sample code that can be flash onto the device once the library version has been installed. It is a universal code, usable with all libraries (some will require #include name changes), where the user can press a 1 in the Serial Monitor to start the recording, and have the label printed in the Serial Monitor, once it has been classified.

In the samples folder, all audio files that were used to train the models to recognise the different commands can be found. The following infographics provides all the details about the dataset:
![Audio Dataset Stats](https://user-images.githubusercontent.com/94687473/167204140-6b41aa3a-a88e-4d13-a5bf-e4ce5f0fe5ee.png)


In the versions folder, all different versions of the trained models can be found. Please check the following table for details:
![CNN Versions Table](https://user-images.githubusercontent.com/94687473/167204046-c1579f78-862c-4ea3-b76c-a8dde7350886.png)

