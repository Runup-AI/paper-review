
## Towards Real-Time Multi-Object Tracking


### Abstract

Modern multiple object tracking (MOT) systems usually follow the tracking-by-detection paradigm. It has 1) a detection model for target localization and 2) an appearance embedding model for data association. Having the two models separately executed might lead to efficiency problems, as the running time is simply a sum of the two steps without investigating potential structures that can be shared between them. Existing research efforts on real-time MOT usually focus on the association step, so they are essentially real-time association methods but not real-time MOT system. In this paper, we propose an MOT system that allows target detection and appearance embedding to be learned in a shared model. Specifically, we incorporate the appearance embedding model into a single-shot detector, such that the model can simultaneously output detections and the corresponding embeddings. As such, the system is formulated as a multi-task learning problem: there are multiple objectives, i.e., anchor classification, bounding box regression, and embedding learning; and the individual losses are automatically weighted. To our knowledge, this work reports the first (near) real-time MOT system, with a running speed of 18.8 to 24.1 FPS depending on the input resolution. Meanwhile, its tracking accuracy is comparable to the state-ofthe-art trackers embodying separate detection and embedding (SDE) learning (64.4% MOTA v.s. 66.1% MOTA on MOT-16 challenge). The code and models are available at https://github.com/Zhongdao/Towards-Realtime-MOT. 

### Home
- https://arxiv.org/pdf/1909.12605v1.pdf

### Code
- https://github.com/Zhongdao/Towards-Realtime-MOT
