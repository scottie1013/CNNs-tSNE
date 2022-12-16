# CNNs-tSNE
In HW3 we applied tSNE to the cifar(100) dataset. The resulting embedding did not really reflect the correct labels. We concluded that comparing the images using the Euclidean distance was not suffiecint to capture more intricate structures present in these images.

Now, we will apply tSNE to the feature vectors output by a Convolutional Neural Network (CNN). This should give us a much better embedding. 

The purpose of this assignment is to make sure you get some familiarity with keras. Also this is **not a typical scenario** for using neural networks -- but it makes a lot of sense to mix and match various tools. After all CNN returns a vector for each input image -- and we know many tools that take vectors.

We will use cifar10 dataset since it has fewer labels.

![Unknown-1](https://user-images.githubusercontent.com/114832226/208184178-46bf585b-2e7f-428b-949e-7ffd6746e933.png)

