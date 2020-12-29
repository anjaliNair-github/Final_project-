# Natural Disaster Detection using SAR
##
Among many improved convolutional neural network (CNN) architectures in the optical image classification, only a few were applied in synthetic aperture radar
(SAR) automatic target recognition (ATR). One main reason is that direct transfer of these advanced architectures for the optical images to the SAR images easily
yields overfitting due to its limited data set and less features relative to the optical images. Thus, based on the characteristics of the SAR image, we proposed
a novel deep convolutional neural network architecture named umbrella. Its framework consists of two alternate CNN-layer blocks. One block is a fusion of six 3-layer paths,
which is used to extract diverse level features from different convolution layers. The other block is composed of convolution layers and pooling layers are mainly utilized to 
reduce dimensions and extract hierarchical feature information. The combination of the two blocks could extract rich features from different spatial scale and simultaneously 
alleviate overfitting. The performance of the umbrella model was validated by the Moving and Stationary Target Acquisition and Recognition (MSTAR) benchmark data set.
This architecture could achieve higher than 99% accuracy for the classification of 10-class targets and higher than 96% accuracy for the classification of 8 variants of 
the T72 tank, even in the case of diverse positions located by targets. The accuracy of our umbrella is superior to the current networks applied in the classification of MSTAR.
The result shows that the umbrella architecture possesses a very robust generalization capability and will be potential for SAR-ART.

##Group Members: 
1.Anjali Nair
2.Shibana Basheer 
3.Najeeb VK
4.San Jose

##Mentor:
Mr.Aneesh Chandran
