# Object-Centric Auto-Encoders and Dummy Anomalies for Abnormal Event Detection in Video

### Abstract

Abnormal event detection in video is a challenging vision problem. Most existing approaches formulate abnormal event detection as an outlier detection task, due to the scarcity of anomalous data during training. Because of the lack of prior information regarding abnormal events, these methods are not fully-equipped to differentiate between normal and abnormal events. In this work, we formalize abnormal event detection as a one-versus-rest binary classiﬁcation problem. Our contribution is two-fold. First, we introduce an unsupervised feature learning framework based on object-centric convolutional auto-encoders to encode both motion and appearance information. Second, we propose a supervised classiﬁcation approach based on clustering the training samples into normality clusters. A one-versus-rest abnormal event classiﬁer is then employed to separate each normality cluster from the rest. For the purpose of training the classiﬁer, the other clusters act as dummy anomalies. During inference, an object is labeled as abnormal if the highest classiﬁcation score assigned by the one-versus-rest classiﬁers is negative. Comprehensive experiments are performed on four benchmarks: Avenue, ShanghaiTech, UCSD and UMN. Our approach provides superior results on all four data sets. On the large-scale ShanghaiTech data set, our method provides an absolute gain of 8.4% in terms of frame-level AUC compared to the state-of-the-art method.


### Paper
- https://arxiv.org/abs/1812.04960
