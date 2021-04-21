# Human-Activity-Recognition

https://www.notion.so/Support-Vector-Machines-6f50bd8c057d42dc978ef3be8238e6ff


Human Activity Recognition aims to capture and identify the state of the user and the activity the user is participating in. Data is collected using an Andriod OS app 'Androsensor' in which the activity can be recorded along with the readings from the Accelerometer, Linear Acceleration, Gyroscopic and Gravitational inertia sensors commonly built in to a mobile phone. The data recorded is saved in CSV format and is proccesed on using the 'Raw Data Preprocessing' notebook. The preprocessing consists of double integration to transform the data from a virtual plane to the earth's physical plane, and a Fast Fourier Transformation to attenuate any noise that has been collected by the inertia sensors. 
Testing and training datasets were created, whose data was analyzed in the 'Data Analysis' notebook. The analysis is based on supervised learning, in which the training data is labelled. The python file in question consists of creating and viewing the clusters in which the data is partitioned. Afterwards, the data is trained and tested with an adapation of a Support Vector Machine, which was observed to compute a greater accuracy than other machine learning methodologies such as Linear Regression.
