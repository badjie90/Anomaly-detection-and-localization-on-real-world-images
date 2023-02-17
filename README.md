#### Anomaly-detection-on-real-world-images


The repository represents a comprehensive framework that leverages advanced autoencoder techniques to perform precise anomaly detection on real-world images. Not only does it detect any anomalies in the input images, but it also performs efficient image reconstruction to return the images to their original form. The [python](https://www.python.org/) code developed in this repository is an exceptionally powerful tool because of its remarkable adaptability, which enables it to handle any image type with ease. I have employed a sophisticated loss metric, namely [mean squared error (MSE)](https://www.statisticshowto.com/probability-and-statistics/statistics-definitions/mean-squared-error/), to effectively measure the reconstruction quality and provide a precise measure of the deviation from the ground truth. This approach ensures that the anomaly detection mechanism is accurate and provides a robust solution for a wide range of real-world applications.  


Our approach for anomaly detection utilizes both the reconstruction error and the [kernel density estimation](https://deepai.org/machine-learning-glossary-and-terms/kernel-density-estimation) based on the vectors in the latent space. The latent space is defined as the bottleneck layer output from our autoencoder. The method is demonstrated on the malarial data set, and it can be seamlessly applied to various other applications. The versatility of this approach is attributed to its robustness and its potential to accurately identify anomalous events, regardless of the context or the data set. Therefore, this method can be applied to a diverse range of data sets, opening up opportunities for anomaly detection in a variety of fields.


MSE are common metric used to measure the quality of a predictive model's output. It is calculated as the average of the squared differences between the predicted values and the actual values. In general, a lower MSE indicates that the model's predictions are closer to the actual values. This means that the model is performing better and is more accurate. Conversely, a higher MSE indicates that the model's predictions are further away from the actual values, which means that the model is less accurate. A lower MSE is generally considered to be a desirable outcome, as it indicates that the model is performing better. However, it is important to keep in mind that a low MSE does not necessarily mean that the model is the best one for a particular problem. Other metrics and factors should be considered as well, such as interpretability, robustness, complexity, and computational efficiency, among others.


Here, we use both the reconstruction error and also the kernel density estimation based on the vectors in the latent space. We consider the bottleneck layer output from our autoencoder as the latent space. This code uses the malarial data set but it can be easily applied to any application.



The dataset used in this project can be found here. [Link](https://www.kaggle.com/code/chiranjeevbit/detecting-malaria-val-accuracy-97/data)

Please use [tensorflow](https://pypi.org/project/tensorflow/) version 2.0 above
