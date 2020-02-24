# Anomaly Detection_Hand-crafted features based methods

### 1. Goal-based trajectory analysis for unusual behaviour detection in intelligent surveillance.

### Abstract
In a typical surveillance installation, a human operator has to constantly monitor a large array of video feeds for suspicious behaviour. As the number of cameras increases, information overload makes manual surveillance increasingly difficult, adding to other confounding factors such as human fatigue and boredom. The objective of an intelligent vision-based surveillance system is to automate the monitoring and event detection components of surveillance, alerting the operator only when unusual behaviour or other events of interest are detected. While most traditional methods for trajectory-based unusual behaviour detection rely on low-level trajectory features such as flow vectors or control points, this paper builds upon a recently introduced approach that makes use of higher-level features of intentionality. Individuals in the scene are modelled as intentional agents, and unusual behaviour is detected by evaluating the explicability of the agent's trajectory with respect to known spatial goals. The proposed method extends the original goal-based approach in three ways: first, the spatial scene structure is learned in a training phase; second, a region transition model is learned to describe normal movement patterns between spatial regions; and third, classification of trajectories in progress is performed in a probabilistic framework using particle filtering. Experimental validation on three published third-party datasets demonstrates the validity of the proposed approach.

### Paper
- https://www.sciencedirect.com/science/article/pii/S026288561000154X



### 2. Chaotic invariants of lagrangian particle trajectories for anomaly detection in crowded scenes.

### Abstract
A novel method for crowd flow modeling and anomaly detection is proposed for both coherent and incoherent scenes. The novelty is revealed in three aspects. First, it is a unique utilization of particle trajectories for modeling crowded scenes, in which we propose new and efficient representative trajectories for modeling arbitrarily complicated crowd flows. Second, chaotic dynamics are introduced into the crowd context to characterize complicated crowd motions by regulating a set of chaotic invariant features, which are reliably computed and used for detecting anomalies. Third, a probabilistic framework for anomaly detection and localization is formulated. The overall work-flow begins with particle advection based on optical flow. Then particle trajectories are clustered to obtain representative trajectories for a crowd flow. Next, the chaotic dynamics of all representative trajectories are extracted and quantified using chaotic invariants known as maximal Lyapunov exponent and correlation dimension. Probabilistic model is learned from these chaotic feature set, and finally, a maximum likelihood estimation criterion is adopted to identify a query video of a scene as normal or abnormal. Furthermore, an effective anomaly localization algorithm is designed to locate the position and size of an anomaly. Experiments are conducted on known crowd data set, and results show that our method achieves higher accuracy in anomaly detection and can effectively localize anomalies.

### Paper
 - https://ieeexplore.ieee.org/abstract/document/5539882
 
