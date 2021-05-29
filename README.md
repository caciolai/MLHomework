# MLHomework

This is the final homework for the course of Machine Learning (A.Y. 2019/2020).

## Homework

Aim of the homework has been the problem of **classification of weather conditions in images** by means of **Convolutional Neural Networks** (CNNs).
In particular, we had to both define our own CNN for the problem, and then leverage **transfer learning** on a pretrained network, to compare performances.

- My custom-designed CNN draws inspiration from **AlexNet**, one of the most popular CNN architectures.
- Transfer learning has been applied starting from two different pretrained networks: **VGG16** and **ResNet**.
- A third approach has been considered: use the pretrained networks as **feature extractors** for more traditional **linear classifiers**. In particular, I have compared the performances of **SVM** and **Logistic Regression**.

Check out the homework implementation [here](homework.ipynb).

## Documentation

You can find further details in the [report](report.pdf) of the homework.

## Resources used
- [Google Colab](https://colab.research.google.com/)
- [TensorFlow](https://www.tensorflow.org/overview)
- [Keras](https://keras.io/)
- [Scikit-learn](https://scikit-learn.org/stable/about.html)

## Authors

- [Andrea Caciolai](github.com/caciolai)
