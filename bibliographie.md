# Analyse des papiers listés dans [cette page](https://github.com/jiachenli94/Awesome-Interaction-aware-Trajectory-Prediction)
## Partie Pedestrians, papiers associés à du code

#### _Mots clés : object tracking, object detection, cv, prediction, trajectory, pedestrian_

[Learning Structured Representations of Spatial and Interactive Dynamics for Trajectory Prediction in Crowded Scenes](https://ieeexplore.ieee.org/abstract/document/9309332)
- **Hypothèse de caméra fixe, donc apprentissage/prédiction lié à un environnement précis.**
- **Méthodes/algos : MDN (Mixed Density Network), LSTM, RNN (Recurrent Neural Network), InfoVAE (Information Maximizing Variational Autoencoders)**

[Social NCE: Contrastive Learning of Socially-aware Motion Representations](https://arxiv.org/abs/2012.11717)
- **Focalisé sur l'étude sociale des mouvements de piétons dans une foule : tendance à éviter d'être trop près les uns des autres, etc.**
- **Méthodes/algos : MLP (Multi-Layer Perceptron), CNN (Convolutional neural network), VAE-based RNN**

[Human Trajectory Forecasting in Crowds: A Deep Learning Perspective](https://arxiv.org/pdf/2007.03639.pdf)
- **Focalisé sur l'étude sociale des mouvements de piétons dans une foule : tendance à éviter d'être trop près les uns des autres, etc.**
- **Méthodes/algos : LSTM, MLP, GAN (Generative Adversarial Network)**

[SimAug: Learning Robust Representations from 3D Simulation for Pedestrian Trajectory Prediction in Unseen Cameras](https://arxiv.org/pdf/2004.02022)
- **Objectif : Entraîner un modèle de manière à ce qu'il fonctionne peu importe la caméra, sa position, son environnement (généralisation extrême)**
- **Méthodes/algos : Multiverse model (ref. 37), ConvRNN**

[DAG-Net: Double Attentive Graph Neural Network for Trajectory Forecasting](https://arxiv.org/abs/2005.12661)
- **Objectif : Prédiction d'objectif, d'interactions sociales et enfin de trajectoires**
- **Méthodes/algos : VAE, GNN (Graph Neural Network)**

[The Trajectron: Probabilistic Multi-Agent Trajectory Modeling With Dynamic Spatiotemporal Graphs](http://openaccess.thecvf.com/content_ICCV_2019/papers/Ivanovic_The_Trajectron_Probabilistic_Multi-Agent_Trajectory_Modeling_With_Dynamic_Spatiotemporal_Graphs_ICCV_2019_paper.pdf)
- **Objectif : Prédiction de trajectoires pouvant prendre en compte plusieurs piétons, ayant chacun des trajectoires possibles hautement différentes**
- **Méthodes/algos : CVAE (Convolutional VAE), LSTM**

[STGAT: Modeling Spatial-Temporal Interactions for Human Trajectory Prediction](http://openaccess.thecvf.com/content_ICCV_2019/papers/Huang_STGAT_Modeling_Spatial-Temporal_Interactions_for_Human_Trajectory_Prediction_ICCV_2019_paper.pdf)
- **Objectif : Prédiction de trajectoires en fonction des autres piétons et des positions passées (du sujet et des autres piétons)**
- **Méthodes/algos : GAT (Graph Attention Network), LTSM**

[Social and Scene-Aware Trajectory Prediction in Crowded Spaces](https://arxiv.org/pdf/1909.08840.pdf)
- **Objectif : Prédiction de trajectoire piétonne en fonction de l'environnement physique en plus des autres piétons**
- **Méthodes/algos : LSTM ainsi qu'un variante Social-LTSM**

[Human Trajectory Prediction using Adversarial Loss](http://www.strc.ch/2019/Kothari_Alahi.pdf)
- **Objectif : Analyser les performances des GAN dans la prédiction de trajectoires multiples de piétons en interaction avec d'autres piétons**
- **Méthodes/algos : GAN, RNN**

[Social Ways: Learning Multi-Modal Distributions of Pedestrian Trajectories with GANs](http://openaccess.thecvf.com/content_CVPRW_2019/papers/Precognition/Amirian_Social_Ways_Learning_Multi-Modal_Distributions_of_Pedestrian_Trajectories_With_GANs_CVPRW_2019_paper.pdf)
- **Objectif : Prédire des trajectoires piétonnes en fonction des trajectoires passées du piéton et des piétons partageant le même espace**
- **Méthodes/algos : GAN, LSTM**

[Peeking into the Future: Predicting Future Person Activities and Locations in Videos](http://openaccess.thecvf.com/content_CVPR_2019/papers/Liang_Peeking_Into_the_Future_Predicting_Future_Person_Activities_and_Locations_CVPR_2019_paper.pdf)
- **Objectif : Traiter les piétons non pas comme des points mais comme des bonhommes avec membres et articulations, et utiliser le langage corporel et les objets/personnes environnantes pour comprendre les activités que ces piétons entreprennent afin de prédire leurs trajectoires**
- **Méthodes/algos : LSTM, CNN**

[Overcoming Limitations of Mixture Density Networks: A Sampling and Fitting Framework for Multimodal Future Prediction](http://openaccess.thecvf.com/content_CVPR_2019/papers/Makansi_Overcoming_Limitations_of_Mixture_Density_Networks_A_Sampling_and_Fitting_CVPR_2019_paper.pdf)
- **Objectif : Prédire de multiples trajectoires possibles, pas forcément que de piétons**
- **Méthodes/algos : CNN, MDN (Mixture Density Networks)**

[Sophie: An attentive gan for predicting paths compliant to social and physical constraints](https://arxiv.org/abs/1806.01482)
- **Objectif : Utiliser les informations de l'environnement ainsi que des piétons présents pour prédire les trajectoires multiples d'un piéton**
- **Méthodes/algos : GAN, LSTM**


# Ancienne bibliographie

### OpenCV
- **Lien :**[ https://opencv.org/multiple-object-tracking-in-realtime/](https://opencv.org/multiple-object-tracking-in-realtime/)
- **Capteur :** Caméra
- **Méthode :** réseaux neuronaux
- **Publications :** [https://research.nvidia.com/publication/realtime-computer-vision-opencv https://www.drdobbs.com/open-source/the-opencv-library/184404319](https://research.nvidia.com/publication/realtime-computer-vision-opencv)
- **Dates :** Depuis 2010, dernières version le mardi 6 juillet

### Tensorflow (plutôt de la recherche qu'un produit fini)
- **Lien :**[ https://github.com/tensorflow/models/tree/master/research/object_detection](https://github.com/tensorflow/models/tree/master/research/object_detection)
- **Capteur :** Caméra
- **Méthode :** réseaux neuronaux 
- **Publications :** [ https://openaccess.thecvf.com/content_cvpr_2017/papers/Huang_SpeedAccuracy_Trade-Offs_for_CVPR_2017_paper.pdf](https://openaccess.thecvf.com/content_cvpr_2017/papers/Huang_SpeedAccuracy_Trade-Offs_for_CVPR_2017_paper.pdf)
- **Dates :** Depuis 2017, commits fréquents encore aujourd'hui

### praveen-palanisamy
- **Lien :**[ https://github.com/praveen-palanisamy/multiple-object-tracking-lidar](https://github.com/praveen-palanisamy/multiple-object-tracking-lidar)
- **Capteur :** Lidar
- **Méthode :** Filtres de Kalman
- **~~Publications :~~**
- **Logiciel :** PCL
- **Dates :** Depuis 2015 à mi-2020

### enginBozkurt
- **Lien :**[ https://github.com/enginBozkurt/LidarObstacleDetection](https://github.com/enginBozkurt/LidarObstacleDetection)
- **Capteur :** Lidar
- **Méthode :** Euclidean Clustering using KDTree
- **~~Publications :~~**
- **Dates :** S2 2019
