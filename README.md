# COVID19 CT Scan Image Classification
#### In this project, we were trying to classify NonCOVID and COVID CT scan images. We built an autoencoder to extract latent space features. Then by using the latent space features, we can classify the images by using K nearest neighbor and Bayesian model.(more details below)

- Data source: https://github.com/UCSD-AI4H/COVID-CT/tree/master/Images-processed
- You can download my autoencoder model and all the code sources [here](https://github.com/shuxg2017/COVID19-CTscan-image-classification/tree/master/model).
- Supervised learning by K nearest neighbor (KNN) and Bayesian (dataset was splitted into training and validation).

### KNN prediction

![Knn](https://github.com/shuxg2017/COVID19-CTscan-image-classification/blob/master/results/Knn_results.png)
![knn point](https://github.com/shuxg2017/COVID19-CTscan-image-classification/blob/master/results/Knn_at_5_confusion.png)

### Bayesian model prediction

![Baye](https://github.com/shuxg2017/COVID19-CTscan-image-classification/blob/master/results/Bayesian_results.png)
![Baye point](https://github.com/shuxg2017/COVID19-CTscan-image-classification/blob/master/results/Bayesian_at_4_confusion.png)
