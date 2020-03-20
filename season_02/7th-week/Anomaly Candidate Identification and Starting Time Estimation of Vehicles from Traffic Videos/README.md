# Anomaly Candidate Identification and Starting Time Estimation of Vehicles from Traffic Videos

### Abstract
Anomaly event detection on road trafﬁc has been a challenging ﬁeld mainly due to lack of training data and a wide variety of anomaly cases. In this paper, we propose a novel two-stage framework for anomaly event detection in road trafﬁc based on anomaly candidate identiﬁcation and starting time estimation of vehicles. First, we use Gaussian mixture models (GMMs) to generate the foreground mask and background image to identify the anomaly candidates. Foreground mask is used to produce the region of interest (ROI) to ﬁlter out the noise from the object detector, YOLOv3, in the background image. Then, we apply the TrackletNet Tracker (TNT) to extract the trajectory of anomaly candidate to estimate the anomaly starting time. Experimental results, with achieved S3 score performance of 93.62%, on the Track 3 testing set of CVPR AI City Challenge 2019 City Flow dataset, show the effectiveness of the proposed framework and its robustness in different real scenes.

### Paper
- http://openaccess.thecvf.com/content_CVPRW_2019/html/AI_City/Wang_Anomaly_Candidate_Identification_and_Starting_Time_Estimation_of_Vehicles_from_CVPRW_2019_paper.html
