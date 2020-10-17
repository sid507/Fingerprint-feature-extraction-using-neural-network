# Fingerprint-feature-extraction-using-neural-network
Minutiae i.e. feature used for fingerprint recognition. In this we are finding features using MLP. Backpropagation training algorithm is used.

The neural network is trained to give the position of Ridge bifurcations in the fingerprint image.

![image](https://github.com/sid507/Fingerprint-feature-extraction-using-neural-network/blob/main/images/bifurcation.PNG?raw=true)

After the image is binarized and thinned, the part of the image where bifurcations are present is as shown below.

![image](https://github.com/sid507/Fingerprint-feature-extraction-using-neural-network/blob/main/images/train_data.PNG?raw=true)

We have used the above data for training the network.

The architecture is as shown below

![image](https://github.com/sid507/Fingerprint-feature-extraction-using-neural-network/blob/master/images/nn.PNG?raw=true)
