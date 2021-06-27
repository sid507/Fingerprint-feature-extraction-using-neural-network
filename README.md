# Fingerprint-feature-extraction-using-neural-network
Minutiae i.e. feature used for fingerprint recognition. In this we are finding features using MLP. Backpropagation training algorithm is used.

The neural network is trained to give the position of Ridge bifurcations in the fingerprint image.

![image](https://github.com/sid507/Fingerprint-feature-extraction-using-neural-network/blob/main/images/bifurcation.PNG?raw=true)

After the image is binarized and thinned, the part of the image where bifurcations are present is as shown below (first two columns are bifurcations).

![image](https://github.com/sid507/Fingerprint-feature-extraction-using-neural-network/blob/main/images/train_data.PNG?raw=true)

We have used the above data for training the network.

The pixels where minutiae were detected are marked with a circle using opencv.
The paper suggests to eliminate the minutiae which are very close to each other.

The output is as shown below.

<img src="https://github.com/sid507/Fingerprint-feature-extraction-using-neural-network/blob/main/images/result.png" />
