
- [2D object detection](#2d-object-detection)
- [2D semantic segmentation](#2d-semantic-segmentation)
- [BEV perception](#bev-perception)
- [data augmentation \& synthesis](#data-augmentation--synthesis)
- [data clean \& corner cases](#data-clean--corner-cases)
- [data set \& automated annotation](#data-set--automated-annotation)
- [Depth Estimation](#depth-estimation)
- [end-to-end perception](#end-to-end-perception)
- [ensemble](#ensemble)
- [forcasting](#forcasting)
- [generative model](#generative-model)
- [lane detection](#lane-detection)
  - [2D lane detection](#2d-lane-detection)
    - [2018 lanenet reference](#2018-lanenet-reference)
  - [3D lane detection](#3d-lane-detection)
  - [automated lane annotation](#automated-lane-annotation)
  - [lane tracking \& video lane detection](#lane-tracking--video-lane-detection)
  - [others](#others)
- [learning theory](#learning-theory)
- [lidar](#lidar)
  - [detection](#detection)
  - [segmentation](#segmentation)
  - [tracking](#tracking)
  - [others](#others-1)
- [Light model \& deploy](#light-model--deploy)
- [multi-modal](#multi-modal)
- [noisy labels](#noisy-labels)
- [prediction](#prediction)
- [radar](#radar)
- [robotics](#robotics)
- [scene understanding](#scene-understanding)
- [simulation](#simulation)
- [SSL \& WSL](#ssl--wsl)
- [SLAM \& HDMap](#slam--hdmap)
- [survey \& system design](#survey--system-design)

# 2D object detection
- 2014 Girshick, Rich feature hierarchies for accurate object detection and semantic segmentation
- 2015 Girshick, Fast R-CNN
- 2016 Liu, SSD_Single Shot MultiBox Detector
- 2016 Redmon, You Only Look Once_ Unified, Real-Time Object Detection
- 2016 Ren, Faster R-CNN_Towards Real-Time Object Detection with Region Proposal Networks
- 2020 Carion, End-to-End Object Detection with Transformers
- 2021 Zhu, Deformable DETR_Deformable Transformers for End-to-End Object Detection
- 2022 Arani, A Comprehensive Study of Real-Time Object Detection Networks Across Multiple Domains_A Survey
- 2022 Wang, YOLOv7_Trainable bag-of-freebies sets new state-of-the-art for real-time object detectors
# 2D semantic segmentation
- 2015 Long, Fully Convolutional Networks for Semantic Segmentation
- 2017 Romera, ERFNet_Efficient Residual Factorized ConvNet for Real-Time Semantic Segmentation
- 2018 Yu, BiSeNet_ Bilateral Segmentation Network for Real-time Semantic Segmentation
# BEV perception
- [2019 Kim, Deep Learning based Vehicle Position and Orientation Estimation via Inverse Perspective Mapping Image](https://ieeexplore.ieee.org/abstract/document/8814050)
- 2020 Ng, BEV-Seg_Bird???s Eye View Semantic Segmentation Using Geometry and Semantic Point Cloud
- 2020 Pan, Cross-view Semantic Segmentation for Sensing Surroundings
- 2020 Philion, Lift, Splat, Shoot_Encoding Images from Arbitrary Camera Rigs by Implicitly Unprojecting to 3D
- 2020 Reiher, A Sim2Real Deep Learning Approach for the Transformation of Images from Multiple Vehicle-Mounted Cameras to a Semantically Segmented Image in Bird???s Eye View
- 2020 Roddick, Predicting Semantic Map Representations from Images using Pyramid Occupancy Networks
- 2021 Can, Structured Bird???s-Eye-View Traffic Scene Understanding from Onboard Images
- [2021 Hou, Multiview Detection with Feature Perspective Transformation](https://arxiv.org/abs/2007.07247)
- 2021 Reading, Categorical Depth Distribution Network for Monocular 3D Object Detection
- [2021 Wang, DETR3D_3D Object Detection from Multi-view Images via 3D-to-2D Queries](https://arxiv.org/abs/2110.06922)
- [2022 Huang, BEVDet4D_Exploit Temporal Cues in Multi-camera 3D Object Detection](https://arxiv.org/abs/2203.17054)
- [2022 Huang, BEVDet_High-performance Multi-camera 3D Object Detection in Bird-Eye-View](https://arxiv.org/abs/2112.11790?context=cs)
- [2022 Jiang, PolarFormer_Multi-camera 3D Object Detection with Polar Transformers](https://arxiv.org/abs/2206.15398)
- [2022 Li, BEVDepth_Acquisition of Reliable Depth for Multi-view 3D Object Detection](https://arxiv.org/abs/2206.10092)
- [2022 Li, BEVFormer_Learning Bird's-Eye-View Representation from Multi-Camera Images via Spatiotemporal Transformers](https://arxiv.org/abs/2203.17270)
- [2022 Li, Delving into the Devils of Bird???s-eye-view Perception_A Review, Evaluation and Recipe](https://github.com/OpenPerceptionX/BEVPerception-Survey-Recipe)
- [2022 Liu, Monocular BEV Perception of Road Scenes via Front-to-Top View Projection](https://arxiv.org/pdf/2211.08144.pdf)
- [2022 Liu, PETR_Position Embedding Transformation for Multi-View 3D Object Detection](https://arxiv.org/abs/2203.05625)
- 2022 Lu, Learning Ego 3D Representation as Ray Tracing
- [2022 Ma, Vision-Centric BEV Perception-A Survey](https://arxiv.org/abs/2208.02797)
- [2022 Park, Time Will Tell_New Outlooks and A Baseline for Temporal Multi-View 3D Object Detection](https://arxiv.org/abs/2210.02443)
- [2022 Peng, BEVSegFormer_Bird???s Eye View Semantic Segmentation From Arbitrary Camera Rigs](https://arxiv.org/abs/2203.04050)
- [2022 Qin, UniFormer_Unified Multi-view Fusion Transformer for Spatial-Temporal Representation in Bird's-Eye-View](https://arxiv.org/abs/2207.08536)
- [2022 Xu, CoBEVT_Cooperative Bird's Eye View Semantic Segmentation with Sparse Transformers](https://arxiv.org/abs/2207.02202)
- [2022 Zhao, Cross-view Transformers for real-time Map-view Semantic Segmentation](https://arxiv.org/abs/2205.02833)
- [2022 Zhao, JPerceiver: Joint Perception Network for Depth, Pose and Layout Estimation in Driving Scenes](https://arxiv.org/abs/2207.07895)
# data augmentation & synthesis
- [2020 Yang, SurfelGAN_Synthesizing Realistic Sensor Data for Autonomous Driving](https://arxiv.org/pdf/2005.03844.pdf)
- 2021 Fang, LiDAR-Aug_A General Rendering-based Augmentation Framework for 3D Object Detection
- 2021 Kapoor, Point Cloud Data Augmentation for Safe 3D Object Detection using Geometric Techniques
- [2021 Wang, PointAugmenting_Cross-Modal Augmentation for 3D Object Detection](https://github.com/VISION-SJTU/PointAugmenting)
- [2022 Guillard, Learning to Simulate Realistic LiDARs](https://arxiv.org/abs/2209.10986)
- 2022 Jansen, Physical LiDAR Simulation in Real-Time Engine
- [2022 Leng, LidarAugment_Searching for Scalable 3D LiDAR Data Augmentations](https://arxiv.org/abs/2210.13488)
- [2022 Lin, TauLiM: Test Data Augmentation of LiDAR Point Cloud by Metamorphic Relation](https://ieeexplore.ieee.org/document/9793740)
- 2022 Triess, A Realism Metric for Generated LiDAR Point Clouds
- 2022 Zyrianov, Learning to Generate Realistic LiDAR Point Clouds
- [2022 Xiao, PolarMix_A General Data Augmentation Technique for LiDAR Point Clouds](https://arxiv.org/abs/2208.00223)
# data clean & corner cases
- 2009 Chandola, Anomaly Detection_ A Survey
- 2014 Wickham, Tidy data
- 2020 Breitenstein, Systematization of Corner Cases for Visual Perception in Automated Driving
- 2020 Li, ?????????????????????????????????????????????????????????
- 2021 Bogdoll, Description of Corner Cases in Automated Driving_Goals and Challenges
- 2021 Breitenstein, Corner Cases for Visual Perception in Automated Driving Some Guidance on Detection Approaches
- 2022 Bogdoll, Anomaly Detection in Autonomous Driving_A Survey
# data set & automated annotation
- 2012 Geiger, Are we ready for autonomous driving_the kitti vision benchmark suite
- 2018 Huang, The ApolloScape Dataset for Autonomous Driving
- 2018 Krajewski, The highD Dataset_A Drone Dataset of Naturalistic Vehicle Trajectories on German Highways for Validation of Highly  Automated Driving Systems
- 2018 Yu, BDD100K_A Diverse Driving Video Database with Scalable Annotation Tooling
- 2019 Behley, SemanticKITTI_A Dataset for Semantic Scene Understanding of LiDAR Sequences
- 2019 Manikandan, Deep Learning Based Automatic Video Annotation Tool for Self-Driving Car
- 2019 Zheng, Exploring OpenStreetMap Availability for Driving Environment Understanding
- 2019 Zimmer, 3D BAT_A Semi-Automatic, Web-based 3D Annotation Toolbox for Full-Surround, Multi-Modal Data Streams
- 2020 Caesar, nuScenes_A multimodal dataset for autonomous driving
- 2020 Carballido, Semi-Automatic Cloud-Native Video Annotation for Autonomous Driving
- 2020 Sun, Proximity Based Automatic Data Annotation for Autonomous Driving
- 2020 Sun, Scalability in Perception for Autonomous Driving_Waymo Open Dataset
- 2021 Ilin, DeepScanner_a Robotic System for Automated 2D Object Dataset Collection with Annotations
- 2022 Kloukiniotis, CarlaScenes_A synthetic dataset for odometry in autonomous driving
- 2022 Paek, K-Lane_Lidar Lane Dataset and Benchmark for Urban Roads and Highways
- [2022 Shi, You Only Label Once_3D Box Adaptation from Point Cloud to Image via Semi-Supervised Learning](https://arxiv.org/pdf/2211.09302.pdf)
- 2022 Sun, SHIFT_A Synthetic Driving Dataset for Continuous Multi-Task Domain Adaptation
# Depth Estimation
- 2021 Guizilini, Full Surround Monodepth from Multiple Cameras
- 2022 Li, OmniFusion_360 Monocular Depth Estimation via Geometry-Aware Fusion
# end-to-end perception
- 2019 Zhang, End-to-end Learning for Autonomous Driving
- 2020 Chen, End-to-end Autonomous Driving Perception with Sequential Latent Representation Learning
- 2020 Liang, Learning lane graph representations for motion forecasting
- 2020 Liang, PnPNet_End-to-End Perception and Prediction with Tracking in the Loop
- 2021 Ishihara, Multi-task Learning with Attention for End-to-end Autonomous Driving
- 2021 Phillips, Deep Multi-Task Learning for Joint Localization, Perception, and Prediction
- 2021 Tampuu, A Survey of End-to-End Driving_Architectures and Training Methods
- 2022 Dat, HybridNets_End-to-End Perception Network
- 2022 Fadadu, Multi-View Fusion of Sensor Data for Improved Perception and Prediction in Autonomous Driving
- 2022 Hu, ST-P3_End-to-end Vision-based Autonomous Driving via Spatial-Temporal Feature Learning
- 2022 Wu, YOLOP_You Only Look Once for Panoptic Driving Perception
- 2022 Zhang, BEVerse_Unified Perception and Prediction in Birds-Eye-View for Vision-Centric Autonomous Driving
- 2022 Zhang, MMFN_Multi-Modal-Fusion-Net for End-to-End Driving
# ensemble
- [2020 Ding, 1 st Place Solution for Waymo Open Dataset Challenge-3D Detection and Domain Adaptation]()
- [2021 Solovyev, Weighted boxes fusion_Ensembling boxes from different object detection models](https://arxiv.org/abs/1910.13302)
# forcasting
- 2021 Zhou, Informer_Beyond efficient transformer for long sequence time-series forecasting
# generative model
- [2014 Goodfellow, Generative Adversarial Nets](https://arxiv.org/abs/1406.2661)
# lane detection
## 2D lane detection
- 2018 Neven, Towards End-to-End Lane Detection-an Instance Segmentation Approach
- 2018 Pan, Spatial As Deep_Spatial CNN for Traffic Scene Understanding
- 2018 Wang, LaneNet_Real-Time Lane Detection Networks for Autonomous Driving
- 2019 Gansbeke, End-to-end Lane Detection through Differentiable Least-Squares Fitting (ICCV Workshop 2019)
- 2019 Li, Line-CNN_End-to-end traffic line detection with line proposal unit
- 2019 Pizzati, Lane detection and classification using cascaded cnns
- 2020 Qin, Ultra Fast Structure-aware Deep Lane Detection
- 2020 Tabelini, PolyLaneNet_Lane Estimation via Deep Polynomial Regression(ICPR2020)
- 2020 Wang, Polynomial Regression Network for Variable-Number Lane Detection(ECCV2020)
- 2020 Xu, CurveLane-NAS_Unifying lane-sensitive architecture search and adaptive point blending
- 2021 Liu, CondLaneNet_A Top-To-Down Lane Detection Framework Based on Conditional Convolution(Alibaba, ICCV2021)
- 2021 Liu, End-to-End Lane Shape Prediction With Transformers(LSTR, WACV2021)
- 2021 Peng, Active Learning for Lane Detection_A Knowledge Distillation Approach(Noah's Ark, ICCV2021)
- 2021 Qu, Focus on Local_Detecting Lane Marker From Bottom Up via Key Point(Noah's Ark, CVPR2021)
- 2021 Su, Structure Guided Lane Detection(Meituan, IJCAI2021)
- 2021 Tabelini, Keep Your Eyes on the Lane_Real-Time Attention-Guided Lane Detection(LaneATT, CVPR2021)
- 2021 Zheng, RESA_Recurrent Feature-Shift Aggregator for Lane Detection
- 2022 Feng, Rethinking Efficient Lane Detection via Curve Modeling
- 2022 Han, Laneformer_Object-aware Row-Column Transformers for Lane Detection
- 2022 Jin, Eigenlanes_Data-Driven Lane Descriptors for Structurally Diverse Lanes
- 2022 Lee, Robust Lane Detection via Expanded Self Attention
- 2022 Sun, Adaptive Multi-Lane Detection based on Robust Instance Segmentation for Intelligent Vehicles
- 2022 Wang, A Keypoint-based Global Association Network for Lane Detection
- 2022 Xu, RCLane_Relay Chain Prediction for Lane Detection
- 2022 Zheng, CLRNet_Cross Layer Refinement Network for Lane Detection
### 2018 lanenet reference
- 1996 Bertozzi, Real-time lane and obstacle detection on the GOLD system
- 2005 Chiu, Lane detection using color-based segmentation
- 2006 Smuda, Multiple cue data fusion with particle filters for road course detection in vision systems
- 2008 Aly, Real time Detection of Lane Markers in Urban Streets
- 2008 Kim, Robust Lane Detection and Tracking in Challenging Scenarios
- 2009 Danescu, Probabilistic Lane Tracking in Difficult Road Scenarios Using Stereovision
- 2009 Loose, Kalman particle filter for lane recognition on rural roads
- 2010 Gackstatter, Stable Road Lane Model Based on Clothoids
- 2010 Liu, Combining Statistical Hough Transform and Particle Filter for robust lane detection and tracking
- 2010 L??pez, Robust_lane_markings_detection_and_road_geometry
- 2010 Zhou, A novel lane detection based on geometrical model and Gabor filter
- 2010 Zhu, Real-time Lane detection by using multiple cues
- 2012 Borkar, A Novel Lane Detection System With Efficient Ground Truth Generation
- 2012 Deusch, A Random Finite Set Approach to Multiple Lane Detection
- 2012 Gopalan, A Learning Approach Towards Detection and Tracking of Lane Markings
- 2012 Hillel, Recent progress in road and lane detection_ a survey
- 2013 Hur, Multi-lane detection in urban driving environments using conditional random fields
- 2013 Jung, An efficient lane detection algorithm for lane departure detection
- 2014 Kim, Robust Lane Detection Based On Convolutional Neural Network and Random Sample Consensus
- 2014 Tan, A novel curve lane detection based on Improved River Flow and RANSAC
- 2014 Wu, Lane-mark extraction for automobiles under complex conditions
- 2015 Huval, An Empirical Evaluation of Deep Learning on Highway Driving
- 2015 Noh, Learning Deconvolution Network for Semantic Segmentation
- 2015 Ronneberger, U-Net_ Convolutional Networks for Biomedical Image Segmentation
- 2015 Zhang, Monocular object instance segmentation and depth ordering with CNNs
- 2016 Dai, Instance-aware semantic segmentation via multi-task network cascades
- 2016 Gurghian, DeepLanes_ End-To-End Lane Position Estimation Using Deep Neural Networks.
- 2016 He, Accurate and robust lane detection based on Dual-View Convolutional Neutral Network
- 2016 Li, Deep Neural Network for Structural Prediction and Lane Detection in Traffic Scene
- 2016 Paszke, ENet_ A Deep Neural Network Architecture for Real-Time Semantic Segmentation
- 2016 Romera-Paredes, Recurrent Instance Segmentation
- 2017 Bai, Deep watershed transform for instance segmentation
- 2017 Brabandere, Semantic Instance Segmentation with a Discriminative Loss Function
- 2017 Chen, DeepLab_Semantic Image Segmentation with Deep Convolutional Nets, Atrous Convolution, and Fully Connected CRFs
- 2017 He, Mask R-CNN
- 2017 Kim, End-To-End Ego Lane Estimation Based on Sequential Transfer Learning for Self-Driving Cars
- 2017 Lee, VPGNet_ Vanishing Point Guided Network for Lane and Road Marking Detection and Recognition
- 2017 Neven, Fast Scene Understanding for Autonomous Driving
- 2017 Xuan, Robust Lane-Mark Extraction for Autonomous Driving Under Complex Real Conditions
## 3D lane detection
- 2004 Nedevschi, 3D Lane Detection System Based on Stereovision
- 2019 Garnett, 3D-LaneNet_End-to-End 3D Multiple Lane Detection(ICCV2019)
- 2020 Efrat, 3D-LaneNet+_Anchor Free Lane Detection using a Semi-Local Representation(GM, NIPSW2020)
- 2020 Guo, Gen-LaneNet_A Generalized and Scalable Approach for 3D Lane Detection
- 2021 Brorsson, Semi-supervised 3d lane detection through spatio-temporal consistency learned from videos
- [2022 Bai, CurveFormer_3D Lane Detection by Curve Propagation with Curve Queries and Attention](https://arxiv.org/abs/2209.07989)
- 2022 Chen, PersFormer_3D Lane Detection via Perspective Transformer and the OpenLane Benchmark
- [2022 Li, Reconstruct From Top View_A 3D Lane Detection Approach Based on Geometry Structure Prior](https://arxiv.org/abs/2206.10098)
- [2022 Liu, Learning to Predict 3D Lane Shape and Camera Pose from a Single Image via Geometry Constraints](https://arxiv.org/abs/2112.15351)
- [2022 Luo, M2-3DLaneNet_Multi-Modal 3D Lane Detection](https://arxiv.org/abs/2209.05996)
- 2022 Yan, ONCE-3DLanes_Building Monocular 3D Lane Detection
## automated lane annotation
- 2012 Borkar, A Novel Lane Detection System With Efficient Ground Truth Generation
- 2018 Roberts, A Dataset for Lane Instance Segmentation in Urban Environments (ECCV 2018)
- 2019 Behrendt, Unsupervised Labeled Lane Markers Using Maps(LLAMAS, Bosch, ICCVW2019)
- 2020 Cheng, LiDAR-based Lane Marking Extraction through Intensity Thresholding and Deep Learning Approaches-A Pavement-based Assessment
- 2020 Martirena, Automated Annotation of Lane Markings Using LIDAR and Odometry
- 2021 Martirena, Visual computing techniques for automated LIDAR annotation with application to intelligent transport systems
- 2021 Paek, Mixer-Based Lidar Lane Detection Network and Dataset for Urban Roads
- 2021 Zurn, Lane Graph Estimation for Scene Understanding in Urban Driving
## lane tracking & video lane detection
- 2021 Dong, A Hybrid Spatial-temporal Deep Learning Architecture for Lane Detection(2021)
- 2021 Zhang, VIL-100_A New Dataset and a Baseline Model for Video Instance Lane Detection(????????????, ICCV2021)
- 2022 Chng, RONELDv2_A faster, improved lane tracking
## others
- 2021 Honda, End-to-End Monocular Vanishing Point Detection Exploiting Lane Annotations
- 2021 Lin, Semi-supervised lane detection with Deep Hough Transform(ICIP2021)
- 2021 Shyam, Weakly Supervised Approach for Joint Object and Lane Marking Detection
- 2022 Han, Clean-Annotation Backdoor Attack against Lane Detection Systems in the Wild
- 2022 Hu, Sim-to-Real Domain Adaptation for Lane Detection and Classification in Autonomous Driving
- 2022 Le, Bayesian Gabor Network with Uncertainty Estimation for Pedestrian Lane Detection in Assistive Navigation
- 2022 Li, Multi-Level Domain Adaptation for Lane Detection
- 2022 Sato, Towards Driving-Oriented Metric for Lane Detection Models
- 2022 Zhou, Illumination-Resilient Lane Detection by Threshold Self-Adjustment Using Newton-Based Extremum Seeking
- [2019 ???????????????????????????????????????????????????????????????](http://150.138.141.12/Kcms/detail/detail.aspx?filename=1019906864.nh&dbcode=CDFD&dbname=CDFD2021)
# learning theory
- 2016 Li, GATED GRAPH SEQUENCE NEURAL NETWORKS
- 2017 Loshchilov, SGDR_STOCHASTIC GRADIENT DESCENT WITH WARM RESTARTS
- 2017 Vaswani, Attention Is All You Need
- 2020 Wu, A Comprehensive Survey on Graph Neural Networks
- 2021 Tolstikhin, MLP-Mixer_An all-MLP Architecture for Vision
- 2022 Hruby, Learning to Solve Hard Minimal Problems
# lidar
## detection
- [2018 Yan, SECOND: Sparsely Embedded Convolutional Detection](https://www.mdpi.com/1424-8220/18/10/3337)
- 2019 Lang, PointPillars_Fast Encoders for Object Detection from Point Cloud
- [2019 Shi, PointRCNN_3D Object Proposal Generation and Detection from Point Cloud](https://arxiv.org/abs/1812.04244)
- 2021 Fan, Embracing Single Stride 3D Object Detector with Sparse Transformer
- 2021 Fang, MapFusion_A General Framework for 3D Object Detection with HDMap
- [2021 Ge, Real-Time Anchor-Free Single-Stage 3D Detection with IoU-Awareness](https://arxiv.org/abs/2107.14342)
- 2021 Wang, PV-RCNN_Point-Voxel Feature Set Abstraction for 3D Object Detection
- [2022 Cai, 3D Cascade RCNN_High Quality Object Detection in Point Clouds](https://arxiv.org/pdf/2211.08248.pdf)
- [2022 Chen, MPPNet_Multi-Frame Feature Intertwining with Proxy Points for 3D Temporal Object Detection](https://arxiv.org/abs/2205.05979)
- [2022 Deng, VISTA_Boosting 3D Object Detection via Dual Cross-VIew SpaTial Attention](https://arxiv.org/abs/2203.09704)
- [2022 Erabati, Li3DeTr_A LiDAR based 3D Detection Transformer](https://arxiv.org/pdf/2210.15365.pdf)
- 2022 Fan, Fully Sparse 3D Object Detection
- 2022 Feng, SEFormer_Structure Embedding Transformer for 3D Object Detection
- 2022 Hu, AFDetV2_Rethinking the Necessity of the Second Stage for Object Dectection from Point Clouds
- [2022 Huang, Rethinking Dimensionality Reduction in Grid-based 3D Object Detection](https://arxiv.org/abs/2209.09464)
- [2022 Jiang, Improving the Intra-class Long-tail in 3D Detection via Rare Example Mining](https://arxiv.org/abs/2210.08375)
- [2022 Liu, LidarNAS_Unifying and Searching Neural Architectures for 3D Point Clouds](https://arxiv.org/abs/2210.05018)
- [2022 Ruppel, Transformers for Object Detection in Large Point Clouds](https://arxiv.org/pdf/2209.15258.pdf)
- [2022 Shi, PillarNet_Real-Time and High-Performance Pillar-based 3D Object Detection](https://arxiv.org/abs/2205.07403)
- [2022 Shi, PV-RCNN++_Point-Voxel Feature Set Abstraction With Local Vector Representation for 3D Object Detection](https://arxiv.org/abs/2102.00463)
- [2022 Tong, Hyperbolic Cosine Transformer for LiDAR 3D Object Detection](https://arxiv.org/ftp/arxiv/papers/2211/2211.05580.pdf)
- 2022 Xue, Point2Seq_Detecting 3D Objects as Sequences
- [2022 Ye, LidarMultiNet_Towards a Unified Multi-task Network for LiDAR Perception](https://arxiv.org/abs/2209.09385)
- 2022 Zhou, CenterFormer_Center-based Transformer for 3D Object Detection
- 2022 Zimmer, A Survey of Robust LiDAR-based 3D Object Detection Methods for Autonomous Driving
## segmentation
- 2015 Zhang, Ground Segmentation based on Loopy Belief Propagation for Sparse 3D Point Clouds
- 2017 Liu, Detecting Drivable Area for Self-driving Cars_An Unsupervised Approach
- 2017 Qi, PointNet++_Deep Hierarchical Feature Learning on Point Sets in a Metric Space
- 2017 Qi, PointNet_Deep Learning on Point Sets for 3D Classification and Segmentation
- 2020 Tao, 3D LiDAR based Drivable Road  Region Detection for Autonomous  Vehicles
- 2021 Xue, LiDAR-based Drivable Region Detection for Autonomous Driving
- 2022 Su, SVNet_Where SO(3) Equivariance Meets Binarization on Point Cloud Representation
- [2022 Uecker, Analyzing Deep Learning Representations of Point Clouds for Real-Time In-Vehicle LiDAR Perception](https://arxiv.org/pdf/2210.14612.pdf)
- 2022 Zhong, No Pain, Big Gain_Classify Dynamic Point Cloud Sequences with Static Models by Fitting Feature-level Space-time Surfaces
## tracking
- [2020 Chiu, Probabilistic 3D Multi-Object Tracking for Autonomous Driving](https://arxiv.org/abs/2001.05673)
- 2020 Poschmann, Factor Graph based 3D Multi-Object Tracking in Point Clouds
- [2020 Weng, 3D Multi-Object Tracking_A Baseline and New Evaluation Metrics](https://arxiv.org/abs/1907.03961)
- 2020 Weng, GNN3DMOT_Graph neural network for 3D multiobject tracking with 2D-3D multi-feature learning
- [2021 Benbarka, Score refinement for confidence-based 3D multi-object tracking](https://arxiv.org/abs/2107.04327)
- [2021 Pang, SimpleTrack_Understanding and Rethinking 3D Multi-object Tracking](https://arxiv.org/abs/2111.09621)
- [2021 Qi, Offboard 3D Object Detection from Point Cloud Sequences](https://arxiv.org/abs/2103.05073)
- [2021 Yang, Auto4D_Learning to Label 4D Objects from Sequential Point Clouds](https://arxiv.org/abs/2101.06586)
- [2021 Yin, Center-based 3D Object Detection and Tracking](https://arxiv.org/abs/2006.11275)
- [2021 Zaech, Learnable Online Graph Representations for 3D Multi-Object Tracking](https://arxiv.org/abs/2104.11747)
- [2022 Kini, 3DMODT_Attention-Guided Affinities for Joint Detection & Tracking in 3D Point Clouds](https://arxiv.org/pdf/2211.00746.pdf)
- 2022 Ruppel, Transformers for Multi-Object Tracking on Point Clouds
- 2022 Shan, Real-time 3D Single Object Tracking with Transformer
## others
- 2021 Hong, Garment4D_Garment Reconstruction from Point Cloud Sequences
- 2022 Gebrehiwot, Teachers in concordance for pseudo-labeling of 3D sequential data
- 2022 He, Learning Scene Dynamics from Point Cloud Sequences
- [2022 Wang, Sequential Point Clouds_A Survey](https://arxiv.org/abs/2204.09337)

# Light model & deploy
- 2020 Zhang, VarGNet_Variable Group Convolutional Neural Network for Efficient Embedded Computing
# multi-modal
- 2021 Xu, FusionPainting_Multimodal Fusion with Adaptive Attention for 3D Object Detection
- 2022 Bai, TransFusion_Robust LiDAR-Camera Fusion for 3D Object Detection with Transformers
- [2022 Chen, BEVDistill_Cross-Modal BEV Distillation for Multi-View 3D Object Detection](https://arxiv.org/abs/2211.09386)
- 2022 Chen, Focal Sparse Convolutional Networks for 3D Object Detection
- 2022 Chen, FUTR3D_A Unified Sensor Fusion Framework for 3D Detection
- [2022 Gong, Multi-modal Fusion Technology based on Vehicle Information_A Survey](https://arxiv.org/abs/2211.06080)
- [2022 Hong, Cross-Modality Knowledge Distillation Network for Monocular 3D Object Detection](https://arxiv.org/pdf/2211.07171.pdf)
- 2022 Huang, Multi-modal Sensor Fusion for Auto Driving Perception_A Survey
- 2022 Li, DeepFusion_Lidar-Camera Deep Fusion for Multi-Modal 3D Object Detection
- [2022 Li, Homogeneous Multi-modal Feature Fusion and Interaction for 3D Object Detection](https://arxiv.org/abs/2210.09615)
- 2022 Li, Unifying Voxel-based Representation with Transformer for 3D Object Detection
- 2022 Liang, BEVFusion_A Simple and Robust LiDAR-Camera Fusion Framework
- 2022 Liu, BEVFusion_Multi-Task Multi-Sensor Fusion with Unified Bird's-Eye View Representation
- 2022 Liu, Multimodal Transformer for Automatic 3D Annotation and Object Detection
- 2022 Mao, 3D Object Detection for Autonomous Driving_A Review and New Outlooks
- [2022 Peri, Towards Long-Tailed 3D Detection](https://arxiv.org/pdf/2211.08691.pdf)
- 2022 Schieber, Deep Sensor Fusion with Pyramid Fusion Networks for 3D Semantic Segmentation
- 2022 Wan, From One to Many_Dynamic Cross Attention Networks for LiDAR and Camera Fusion
- 2022 Wang, Temporal and Spatial Online Integrated Calibration for Camera and LiDAR
- 2022 Yu, Benchmarking the Robustness of LiDAR-Camera Fusion for 3D Object Detection
- 2022 Zeng, LIFT_Learning 4D LiDAR Image Fusion Transformer for 3D Object Detection
# noisy labels
- 2015 Sukhbaatar, Training convolutional networks with noisy labels
- 2017 Wang, Multiclass Learning With Partially Corrupted Labels
- 2018 Jiang, Mentornet_Learning data-driven curriculum for very deep neural networks on corrupted labels
- 2018 Zhang, Mixup_Beyond empirical risk minimization
- 2019 Arazo, Unsupervised Label Noise Modeling and Loss Correction
- 2019 Huang, O2U-Net_A simple noisy label??detection approach for deep neural networks
- 2019 Lee, Robust Inference via Generative Classifiers for Handling Noisy Labels
- 2020 Cordeiro, A Survey on Deep Learning with Noisy Labels
- 2020 Huang, Self-adaptive training_beyond??empirical risk minimization
- 2020 Jiang, Beyond Synthetic Noise_Deep Learning on Controlled Noisy Labels
- 2020 Li, DivideMix_Learning with noisy labels as semi-supervised learning
- 2020 Ma, Normalized Loss Functions for Deep Learning with Noisy Labels
- 2020 Zheng, Error-bounded correction of noisy labels
- 2021 Algan, Image Classification with Deep Learning in the Presence of Noisy Labels_A Survey
- 2021 Kim, FINE Samples for Learning with Noisy Labels
- 2021 Wei, Open-set label noise can improve??robustness against inherent label noise
- 2022 Liu, Towards Robust Adaptive Object Detection under Noisy Annotations
- 2022 Song, Learning from Noisy Labels with Deep Neural Networks_A Survey
- 2022 Wang, Scalable Penalized Regression for Noise Detection in Learning with Noisy Labels
# prediction
- 2020 Zhao, TNT_Target-driven Trajectory Prediction
- 2021 Deo, Multimodal Trajectory Prediction Conditioned on Lane-Graph Traversals
- 2021 Hu, FIERY_Future Instance Prediction in Bird???s-Eye View from Surround Monocular Cameras
- 2022 Bhattacharyya, SSL-Lanes_Self-Supervised Learning for Motion Forecasting in Autonomous Driving
- 2022 Nayakanti, Wayformer_Motion Forecasting via Simple & Efficient Attention Networks
- 2022 Wang, LTP_Lane-based Trajectory Prediction for Autonomous Driving
# radar
- 2022 Paek, K-Radar_4D Radar Object Detection Dataset and Benchmark for Autonomous Driving in Various Weather Conditions
# robotics
- [2021 Roy, From Machine Learning to Robotics_Challenges and Opportunities for Embodied Intelligence](https://arxiv.org/abs/2110.15245)
# scene understanding
- [2020 Gemez, Lidar-based scene understanding for autonomous driving using deep learning](https://www.tesisenred.net/handle/10803/671062#page=1)
# simulation
- [2021 Acuna, Towards Optimal Strategies for Training Self-Driving Perception Models in Simulation](https://arxiv.org/abs/2111.07971)
# SSL & WSL
- 2013 Lee, Pseudo-Label_The Simple and Efficient Semi-Supervised Learning Method for Deep Neural Networks
- [2017 Ratner, Snorkel-rapid training data creation with weak supervision](https://arxiv.org/abs/1711.10160)
- 2020 Ouali, An Overview of Deep Semi-Supervised Learning
- 2021 Zhang, FlexMatch_Boosting Semi-Supervised Learning with Curriculum Pseudo Labeling
- [2022 Park, DetMatch_Two Teachers are Better Than One for Joint 2D and 3D Semi-Supervised Object Detection](https://arxiv.org/abs/2203.09510)
# SLAM & HDMap
- [2016 Guo, A Low-Cost Solution for Automatic Lane-Level Map Generation Using Conventional In-Car Sensors](https://ieeexplore.ieee.org/document/7422083)
- 2018 Liang, LineNet_a Zoomable CNN for Crowdsourced High Definition Maps Modeling in Urban Environments
- 2019 Homayounfar, DAGMapper_Learning to Map by Discovering Lane Topology
- 2019 Li, Topological Map Extraction From Overhead Images
- 2020 Gao, VectorNet_Encoding HD Maps and Agent Dynamics from Vectorized Representation
- [2020 Qin, AVP-SLAM: Semantic Visual Mapping and Localization for Autonomous Vehicles in the Parking Lot](https://arxiv.org/pdf/2007.01813.pdf)
- 2020 Shan, LIO-SAM_Tightly-coupled Lidar Inertial Odometry via Smoothing and Mapping
- 2021 Shan, LVI-SAM_Tightly-coupled Lidar-Visual-Inertial Odometry via Smoothing and Mapping
- 2021 Xia, High-definition map creation and update for autonomous driving
- 2022 Li, HDMapNet_An Online HD Map Construction and Evaluation Framework
- 2022 Saha, Translating Images into Maps
- 2022 Teed, DROID-SLAM_Deep Visual SLAM for Monocular, Stereo, and RGB-D Cameras
# survey & system design
- 2019 Self-driving cars_ A survey
- 2020 A survey of autonomous driving_Common practices and emerging technologies
- 2020 Liang, Lane Detection_ A Survey with New Results
- 2021 A review of lane detection methods based on deep learning(PR2021)
- 2021 Waykole, Review on Lane Detection and Tracking Algorithms of Advanced Driver Assistance System
- 2021 Zhang, Deep Learning in Lane Marking Detection_ A Survey

**End**

**test**
