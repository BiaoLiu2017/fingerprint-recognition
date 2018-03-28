# fingerprint-recognition
Fingerprint-recognition using deeplearning method
I used siamese network to judge whether two fingerprint pictures are from same finger.

# About siamese network
Reference《Learning a similarity metric discriminatively, with application to face verification》and《 Hamming Distance Metric Learning》

# Use Caffe to build siamese network
This project uses a siamese network that uses weight sharing and a contrastive loss function to learn a model which can judge whether two fingerprint pictures are from same finger.

# procedure
1.Download fingerprint picture
NIST has a lot of fingerprint pictures. https://www.nist.gov/itl/iad/image-group/resources/biometric-special-databases-and-software
For example: Special Database 4 - NIST 8-bit Gray Scale Images of Fingerprint Image Groups. 

2.Fingerprint process(optional)
Reference code: https://github.com/Rubens10010/Fingerprint-Classification-System

3.Data augmentation
The python scripts are in Data_augmentation directory.

4.Caffe install
Reference my another github project: Caffe_Learning

5.Siamese network
The network files are in Siamese_caffe directory

6.Training siamese network

7.Visualize the learned Siamese embedding

8.Test
Test whether two fingerprints are the same.

9.Attach to raspberry pi
Reference my another project:
