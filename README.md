# What is MNIST dataset?

The MNIST database (Modified National Institute of Standards and Technology database) is a large database of handwritten digits that is commonly used for training various image processing systems. The database is also widely used for training and testing in the field of machine learning.
It was created by "re-mixing" the samples from NIST's original datasets. The creators felt that since NIST's training dataset was taken from American Census Bureau employees, while the testing dataset was taken from American high school students, it was not well-suited for machine learning experiments. Furthermore, the black and white images from NIST were normalized to fit into a 28x28 pixel bounding box and anti-aliased, which introduced grayscale levels.
The MNIST database contains 60,000 training images and 10,000 testing images. Half of the training set and half of the test set were taken from NIST's training dataset, while the other half of the training set and the other half of the test set were taken from NIST's testing dataset. The original creators of the database keep a list of some of the methods tested on it. 
In their original paper, they use a support-vector machine to get an error rate of 0.8%. An extended dataset similar to MNIST called EMNIST has been published in 2017, which contains 240,000 training mnist dataset images, and 40,000 testing mnist dataset images of MNIST dataset of handwritten digits and characters.

![image](https://user-images.githubusercontent.com/74241208/191429215-78d1dc70-4dd9-45eb-88e2-f0ad409f9b1c.png)


# What is MNIST used for?

MNIST provides a baseline for testing image processing systems. You could consider it as the “hello world” of machine learning. Data scientists will train an algorithm on the MNIST dataset simply to test a new architecture or framework, to ensure that they work.
Because MNIST is a labeled dataset that pairs images of hand-written numerals with the name of the respective numeral, it can be used in supervised learning to train classifiers. It is a good example, alongside Fei Fei Li’s ImageNet, of how a good, labeled dataset can advance the cause of machine learning more broadly. More examples of open datasets are here.
