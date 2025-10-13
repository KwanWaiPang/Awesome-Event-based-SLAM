<p align="center">
  <h1 align="center">
  Awesome Event-based SLAM
  </h1>
</p>

This repository contains a curated list of resources addressing SLAM using *Event Camera*.

If you find some ignored papers, **feel free to [*create pull requests*](https://github.com/KwanWaiPang/Awesome-Transformer-based-SLAM/blob/pdf/How-to-PR.md), or [*open issues*](https://github.com/KwanWaiPang/Awesome-Event-based-SLAM/issues/new)**.

Contributions in any form to make this list more comprehensive are welcome.

If you find this repository useful, a simple star should be the best affirmation. 😊

For academic use, please consider citing the following:

```bibtex
@article{GuanPhDThesis,
      title={Event-based Vision for 6-DOF Pose Tracking and 3D Mapping},
      author={Guan, Weipeng},
      journal={HKU Theses Online (HKUTO)},
      year={2025},
      publisher={The University of Hong Kong (Pokfulam, Hong Kong)}
}      
```

Feel free to share this list with others!

# Overview
- [Event-based Pose Estimation](#Event-based-Pose-Estimation)
- [Event-based Depth Estimation](#Event-based-Depth-Estimation)
- [Event-based Feature Detection and Tracking](#Event-based-Feature-Detection-and-Tracking)
- [Event-based 3DGS or NeRF](#Event-based-3DGS-or-NeRF)
- [Event Dataset for SLAM Benchmarking](#Event-Dataset-for-SLAM-Benchmarking)
- [Other Resources](#Other-Resources)


## Event-based Pose Estimation
<!-- |---|`arXiv`|---|---|---| -->
<!-- [![Github stars](https://img.shields.io/github/stars/***.svg)]() -->

| Year | Venue | Paper Title | Repository | Note |
|:----:|:-----:| ----------- |:----------:|:----:|
|2025|`RAL`|[Deep Visual Odometry for Stereo Event Cameras](https://arxiv.org/pdf/2509.08235)|[![Github stars](https://img.shields.io/github/stars/NAIL-HNU/SDEVO.svg)](https://github.com/NAIL-HNU/SDEVO)|---|
|2025|`arXiv`|[Hybrid-EVIO: Event-Based Visual-Inertial Odometry with Hybrid Visual Front-End](https://d197for5662m48.cloudfront.net/documents/publicationstatus/271140/preprint_pdf/0df0618f5884765d05a9f463bf47191f.pdf)|[![Github stars](https://img.shields.io/github/stars/sssxxxkkkk/hybrid_EVIO.svg)](https://github.com/sssxxxkkkk/hybrid_EVIO)|---| 
|2025|`Frontiers in Robotics and AI`|[VIO-GO: Optimizing Event-Based SLAM Parameters for Robust Performance in High Dynamic Range Scenarios](https://www.frontiersin.org/journals/robotics-and-ai/articles/10.3389/frobt.2025.1541017/abstract)|---|---|
|2025|`arXiv`|[Event-based Stereo Visual-Inertial Odometry with Voxel Map](https://arxiv.org/pdf/2506.23078)|---|---|
|2025|`International Conference on Multimedia Retrieval`|[GRE-SLAM: 6-DoF Pure Event-Based SLAM with Semi-Dense Depth Recovery Assisted Bundle Adjustment](https://dl.acm.org/doi/abs/10.1145/3731715.3733352)|---|---|
|2025|`arXiv`|[Radar and Event Camera Fusion for Agile Robot Ego-Motion Estimation](https://arxiv.org/pdf/2506.18443)|[![Github stars](https://img.shields.io/github/stars/ZzhYgwh/TwistEstimator.svg)](https://github.com/ZzhYgwh/TwistEstimator)|---|
|2025|`arXiv`|[SuperEvent: Cross-Modal Learning of Event-based Keypoint Detection](https://arxiv.org/pdf/2504.00139)|[![Github stars](https://img.shields.io/github/stars/smartroboticslab/SuperEvent.svg)](https://github.com/smartroboticslab/SuperEvent)|[website](https://smartroboticslab.github.io/SuperEvent/)| 
|2025|`arXiv`|[SuperEIO: Self-Supervised Event Feature Learning for Event Inertial Odometry](https://arxiv.org/pdf/2503.22963)|[![Github stars](https://img.shields.io/github/stars/arclab-hku/SuperEIO.svg)](https://github.com/arclab-hku/SuperEIO)|[website](https://arclab-hku.github.io/SuperEIO/)|
|2025|`RAL`|[Event-Frame-Inertial Odometry Using Point and Line Features Based on Coarse-to-Fine Motion Compensation](https://ieeexplore.ieee.org/abstract/document/10855459)|[![Github stars](https://img.shields.io/github/stars/choibottle/C2F-EFIO.svg)](https://github.com/choibottle/C2F-EFIO)|-|
|2025|`arXiv`|[EVLoc: Event-based Visual Localization in LiDAR Maps via Event-Depth Registration](https://arxiv.org/pdf/2503.00167?)|---|---| 
|2025|`TRO`|[Esvo2: Direct visual-inertial odometry with stereo event cameras](https://arxiv.org/pdf/2410.09374?)| [![Github stars](https://img.shields.io/github/stars/NAIL-HNU/ESVO2.svg)](https://github.com/NAIL-HNU/ESVO2)|---| 
|2025|`IJCV`|[METS: Motion-Encoded Time-Surface for Event-Based High-Speed Pose Tracking](https://link.springer.com/article/10.1007/s11263-025-02379-6)|---|---| 
|2025|`Sensor`|[Stereo Event-Based Visual--Inertial Odometry](https://pmc.ncbi.nlm.nih.gov/articles/PMC11819757/)|---|---| 
|2025|`ICCV`|[DEIO: Deep Event Inertial Odometry](https://arxiv.org/pdf/2411.03928)|[![Github stars](https://img.shields.io/github/stars/arclab-hku/DEIO.svg)](https://github.com/arclab-hku/DEIO)|[website](https://kwanwaipang.github.io/DEIO/)|
|2024|`IROS`|[Deep Visual Odometry with Events and Frames](https://arxiv.org/pdf/2309.09947)|[![Github stars](https://img.shields.io/github/stars/uzh-rpg/rampvo.svg)](https://github.com/uzh-rpg/rampvo)|RAMP-VO| 
|2024|`arXiv`|[EROAM: Event-based Camera Rotational Odometry and Mapping in Real-time](https://arxiv.org/pdf/2411.11004)|[![Github stars](https://img.shields.io/github/stars/wlxing1901/eroam.svg)](https://github.com/wlxing1901/eroam)|-|
|2024|`3DV`|[Deep event visual odometry](https://arxiv.org/pdf/2312.09800)|[![Github stars](https://img.shields.io/github/stars/tum-vision/DEVO.svg)](https://github.com/tum-vision/DEVO)|---|
|2024|`TIV`|[Dh-ptam: a deep hybrid stereo events-frames parallel tracking and mapping system](https://arxiv.org/pdf/2306.01891)|[![Github stars](https://img.shields.io/github/stars/AbanobSoliman/DH-PTAM.svg)](https://github.com/AbanobSoliman/DH-PTAM)|Superpoint+[stereo ptam](https://github.com/uoip/stereo_ptam)|
|2024|`ICRA`|[Imu-aided event-based stereo visual odometry](https://arxiv.org/pdf/2405.04071)| [![Github stars](https://img.shields.io/github/stars/NAIL-HNU/ESVIO_AA.svg)](https://github.com/NAIL-HNU/ESVIO_AA)|---| 
|2024|`RAL`|[FAST-LIEO: Fast and Real-Time LiDAR-Inertial-Event-Visual Odometry](https://ieeexplore.ieee.org/abstract/document/10816457/)|---|---| 
|2024|`arXiv`|[Continuous Gaussian Process Pre-Optimization for Asynchronous Event-Inertial Odometry](https://arxiv.org/pdf/2412.08909)|---|---| 
|2024|`IROS`|[EVIT: Event-based visual-inertial tracking in semi-dense maps using windowed nonlinear optimization](https://arxiv.org/pdf/2408.01370)|[![Github stars](https://img.shields.io/github/stars/MobilePerceptionLab/Canny-EVT.svg)](https://github.com/MobilePerceptionLab/Canny-EVT)|---| 
|2024|`TRO`|[Cross-modal semi-dense 6-dof tracking of an event camera in challenging conditions](https://arxiv.org/pdf/2401.08043)|[![Github stars](https://img.shields.io/github/stars/MobilePerceptionLab/Canny-EVT.svg)](https://github.com/MobilePerceptionLab/Canny-EVT)|---| 
|2024|`IROS`|[Asynchronous Event-Inertial Odometry using a Unified Gaussian Process Regression Framework](https://arxiv.org/pdf/2412.03136)|---|---| 
|2025|`TRO`|[AsynEIO: Asynchronous Monocular Event-Inertial Odometry Using Gaussian Process Regression](https://arxiv.org/pdf/2411.12175)|---|---| 
|2024|`arXiv`|[Efficient Continuous-Time Ego-Motion Estimation for Asynchronous Event-based Data Associations](https://ui.adsabs.harvard.edu/abs/2024arXiv240216398W/abstract)|---|---| 
|2024|`ECCV`|[ES-PTAM: Event-based stereo parallel tracking and mapping](https://arxiv.org/pdf/2408.15605)|[![Github stars](https://img.shields.io/github/stars/tub-rip/ES-PTAM.svg)](https://github.com/tub-rip/ES-PTAM) |---| 
|2024|`ECCV`|[Event-based mosaicing bundle adjustment](https://link.springer.com/chapter/10.1007/978-3-031-72624-8_27)|[![Github stars](https://img.shields.io/github/stars/tub-rip/emba.svg)](https://github.com/tub-rip/emba) |---| 
|2024|`arXiv`|[Event-based Photometric Bundle Adjustment](https://arxiv.org/pdf/2412.14111?)|[![Github stars](https://img.shields.io/github/stars/tub-rip/epba.svg)](https://github.com/tub-rip/epba)|---| 
|2024|`TRO`|[CMax-SLAM: Event-based Rotational-Motion Bundle Adjustment and SLAM System using Contrast Maximization](https://arxiv.org/pdf/2403.08119)|[![Github stars](https://img.shields.io/github/stars/tub-rip/cmax_slam.svg)](https://github.com/tub-rip/cmax_slam)|-|
|2024|`Advanced Intelligent Systems`|[EVI-SAM: Robust, Real-Time, Tightly-Coupled Event--Visual--Inertial State Estimation and 3D Dense Mapping](https://advanced.onlinelibrary.wiley.com/doi/pdf/10.1002/aisy.202400243)|---|[website](https://kwanwaipang.github.io/EVI-SAM/)| 
|2024|`IROS`|[Monocular Event-Inertial Odometry with Adaptive decay-based Time Surface and Polarity-aware Tracking](https://arxiv.org/pdf/2409.13971)|---|---| 
|2023|`Advanced Intelligent Systems`|[T-ESVO: Improved Event-Based Stereo Visual Odometry via Adaptive Time-Surface and Truncated Signed Distance Function](https://advanced.onlinelibrary.wiley.com/doi/abs/10.1002/aisy.202300027)|---|---|
|2023|`CVPR`|[Progressive spatio-temporal alignment for efficient event-based motion estimation](http://openaccess.thecvf.com/content/CVPR2023/papers/Huang_Progressive_Spatio-Temporal_Alignment_for_Efficient_Event-Based_Motion_Estimation_CVPR_2023_paper.pdf)|---|---| 
|2023|`ICRA`|[Fusing event-based camera and radar for slam using spiking neural networks with continual stdp learning](https://arxiv.org/pdf/2210.04236)|---|---| 
|2023|`RAL`|[Event-and Frame-based Visual-Inertial Odometry with Adaptive Filtering based on 8-DOF Warping Uncertainty](https://ieeexplore.ieee.org/abstract/document/10342794/)|---|---| 
|2023|`ITSC`|[An Event-based Stereo 3D Mapping and Tracking Pipeline for Autonomous Vehicles](https://hal.science/hal-04211637/file/ITSC2023.pdf)|---|---| 
|2023|`TIV`|[MC-VEO: A visual-event odometry with accurate 6-DoF motion compensation](https://ieeexplore.ieee.org/abstract/document/10275026)|[![Github stars](https://img.shields.io/github/stars/huangfeng95/mc-veo-buildconf.svg)](https://github.com/huangfeng95/mc-veo-buildconf)|-|
|2023|`RAL`|[Event-based stereo visual odometry with native temporal resolution via continuous-time gaussian process regression](https://arxiv.org/pdf/2306.01188)|---|---| 
|2023|`sensor`|[Esvio: Event-based stereo visual-inertial odometry](https://www.mdpi.com/1424-8220/23/4/1998/pdf)|---|---| 
|2023|`RAL`|[ESVIO: Event-based Stereo Visual Inertial Odometry](https://arxiv.org/pdf/2212.13184)|[![Github stars](https://img.shields.io/github/stars/arclab-hku/ESVIO.svg)](https://github.com/arclab-hku/ESVIO)|[website](https://kwanwaipang.github.io/ESVIO/)| 
|2023|`TASE`|[PL-EVIO: Robust Monocular Event-based Visual Inertial Odometry with Point and Line Features](https://arxiv.org/pdf/2209.12160)|---|[website](https://kwanwaipang.github.io/PL-EVIO/)| 
|2023|`TIM`|[Cubic B-Spline-Based Feature Tracking for Visual--Inertial Odometry With Event Camera](https://ieeexplore.ieee.org/abstract/document/10296514/)|---|---| 
|2023|`CVPR`|[Event-IMU Fusion Strategies for Faster-Than-IMU Estimation Throughput](https://openaccess.thecvf.com/content/CVPR2023W/EventVision/papers/Chamorro_Event-IMU_Fusion_Strategies_for_Faster-Than-IMU_Estimation_Throughput_CVPRW_2023_paper.pdf)|---|---| 
|2022|`RAL`|[Event-based line SLAM in real-time](https://upcommons.upc.edu/bitstream/handle/2117/371576/2608-Event-based-line-%7BSLAM%7D-in-real-time.pdf?sequence=1)|---|---| 
|2022|`ICRA`|[DEVO: Depth-Event Camera Visual Odometry in Challenging Conditions](https://arxiv.org/pdf/2202.02556)|---|---| 
|2022|`CVPR`|[Event-aided Direct Sparse Odometry](https://openaccess.thecvf.com/content/CVPR2022/papers/Hidalgo-Carrio_Event-Aided_Direct_Sparse_Odometry_CVPR_2022_paper.pdf)|[![Github stars](https://img.shields.io/github/stars/uzh-rpg/eds-buildconf.svg)](https://github.com/uzh-rpg/eds-buildconf)|[website](https://rpg.ifi.uzh.ch/eds.html)| 
|2022|`RAL`|[Exploring Event Camera-based Odometry for Planetary Robots](https://arxiv.org/pdf/2204.05880)|---|---| 
|2022|`IROS`|[A tightly-coupled event-inertial odometry using exponential decay and linear preintegrated measurements](https://opus.lib.uts.edu.au/rest/bitstreams/b787a193-9a4b-4680-8f0b-139a21634f3c/retrieve)|---|---| 
|2022|`IROS`|[Monocular Event Visual Inertial Odometry based on Event-corner using Sliding Windows Graph-based Optimization](https://kwanwaipang.github.io/Poster_files/papers/Monocular%20Event%20Visual%20Inertial%20Odometry%20Based%20on%20Event-Corner%20Using%20Sliding%20Windows%20Graph-Based%20Optimization.pdf)|---|[website](https://kwanwaipang.github.io/Mono-EIO/)| 
|2022|`Processes`|[Contrast maximization-based feature tracking for visual odometry with an event camera](https://www.mdpi.com/2227-9717/10/10/2081)|-|-|
|2022|`Sensor`|[Visual Odometry with an Event Camera Using Continuous Ray Warping and Volumetric Contrast Maximization](https://arxiv.org/pdf/2107.03011)|-|-| 
|2022|`ICRA`|[Asynchronous optimisation for event-based visual odometry](https://arxiv.org/pdf/2203.01037)|---|---| 
|2021|`CVPR`|[Spatiotemporal registration for event-based visual odometry](http://openaccess.thecvf.com/content/CVPR2021/papers/Liu_Spatiotemporal_Registration_for_Event-Based_Visual_Odometry_CVPR_2021_paper.pdf)|---|---| 
|2021|`RAL`|[Real-time rotational motion estimation with contrast maximization over globally aligned events](https://ieeexplore.ieee.org/abstract/document/9454404/)|---|---| 
|2021|`European Conference on Mobile Robots`|[Feature-based Event Stereo Visual Odometry](https://arxiv.org/pdf/2107.04921)|---|---| 
|2021|`TRO`|[Event-based stereo visual odometry](https://arxiv.org/pdf/2007.15548)| [![Github stars](https://img.shields.io/github/stars/HKUST-Aerial-Robotics/ESVO.svg)](https://github.com/HKUST-Aerial-Robotics/ESVO)|---| 
|2020|`TPAMI`|[Globally-optimal contrast maximisation for event cameras](https://arxiv.org/pdf/2206.05127)|---|---| 
|2020|`ECCV`|[Globally-optimal event camera motion estimation](https://arxiv.org/pdf/2203.03914)|---|---| 
|2020|`CVPR`|[Globally optimal contrast maximisation for event-based motion estimation](http://openaccess.thecvf.com/content_CVPR_2020/papers/Liu_Globally_Optimal_Contrast_Maximisation_for_Event-Based_Motion_Estimation_CVPR_2020_paper.pdf)|---|---| 
|2020|`IROS`|[IDOL: A framework for IMU-DVS odometry using lines](https://arxiv.org/pdf/2008.05749)|---|---| 
|2020|`IROS`|[Unsupervised learning of dense optical flow, depth and egomotion with event-based sensors](http://ras.papercept.net/images/temp/IROS/files/1193.pdf)|---|---| 
|2019|`CVPR`|[Unsupervised event-based learning of optical flow, depth, and egomotion](http://openaccess.thecvf.com/content_CVPR_2019/papers/Zhu_Unsupervised_Event-Based_Learning_of_Optical_Flow_Depth_and_Egomotion_CVPR_2019_paper.pdf)|---|---| 
|2019|`IEEE International Conference on Robotics and Biomimetics`|[Neuromorphic visual odometry system for intelligent vehicle application with bio-inspired vision sensor](https://arxiv.org/pdf/1909.02490)|---|---| 
|2019|`ICRA`|[Event-based, direct camera tracking from a photometric 3d map using nonlinear optimization](https://www.zora.uzh.ch/id/eprint/197737/1/ICRA19_Bryner.pdf)|[![Github stars](https://img.shields.io/github/stars/uzh-rpg/direct_event_camera_tracker.svg)](https://github.com/uzh-rpg/direct_event_camera_tracker)|---| 
|2018|`RAL`|[Ultimate SLAM? Combining events, images, and IMU for robust visual SLAM in HDR and high-speed scenarios](https://arxiv.org/pdf/1709.06310)|[![Github stars](https://img.shields.io/github/stars/uzh-rpg/rpg_ultimate_slam_open.svg)](https://github.com/uzh-rpg/rpg_ultimate_slam_open)|---| 
|2018|`TRO`|[Continuous-time visual-inertial odometry for event cameras](https://arxiv.org/pdf/1702.07389)|---|---| 
|2017|`TPAMI`|[Event-based, 6-DOF camera tracking from photometric depth maps](https://arxiv.org/pdf/1607.03468)|---|---| 
|2017|`IEEE International Conference on Computational Photography`|[Real-time panoramic tracking for event cameras](https://arxiv.org/pdf/1703.05161)|---|---| 
|2017|`BMVC`|[Real-time Visual-Inertial Odometry for Event Cameras using Keyframe-based Nonlinear Optimization](https://www.zora.uzh.ch/id/eprint/139471/1/BMVC17_Rebecq.pdf)|---|---| 
|2017|`CVPR`|[Event-based visual inertial odometry](https://openaccess.thecvf.com/content_cvpr_2017/papers/Zhu_Event-Based_Visual_Inertial_CVPR_2017_paper.pdf)|[![Github stars](https://img.shields.io/github/stars/daniilidis-group/event_feature_tracking.svg)](https://github.com/daniilidis-group/event_feature_tracking)|---| 
|2017|`RAL`|[Accurate angular velocity estimation with an event camera](https://www.zora.uzh.ch/id/eprint/138896/1/RAL16_Gallego.pdf)|---|---| 
|2016|`RAL`|[Evo: A geometric approach to event-based 6-dof parallel tracking and mapping in real time](https://ieeexplore.ieee.org/ielaam/7083369/7797562/7797445-aam.pdf)|[![Github stars](https://img.shields.io/github/stars/uzh-rpg/rpg_dvs_evo_open.svg)](https://github.com/uzh-rpg/rpg_dvs_evo_open) |---| 
|2016|`ICRA`|[Fast localization and tracking using event sensors](https://merl.com/publications/docs/TR2016-033.pdf)|---|---| 
|2016|`ECCV`|[Real-time 3D reconstruction and 6-DoF tracking with an event camera](https://core.ac.uk/download/pdf/77017474.pdf)|---|---| 
|2016|`IROS`|[Low-latency visual odometry using event-based feature tracks](https://infoscience.epfl.ch/bitstreams/8b6efd05-e55b-45ad-9932-89c939c5c6d8/download)|---|---| 
|2015|`arXiv`|[Event-based camera pose tracking using a generative event model](https://arxiv.org/pdf/1510.01972)|---|---| 
|2014|`IEEE/RSJ International Conference on Intelligent Robots and Systems`|[Event-based, 6-DOF pose tracking for high-speed maneuvers](https://www.zora.uzh.ch/id/eprint/125447/1/IROS14_Mueggler.pdf)|---|---| 
|2014|`ICRA`|[Event-based 3D SLAM with a depth-augmented dynamic vision sensor](https://citeseerx.ist.psu.edu/document?repid=rep1&type=pdf&doi=d7e293687b47f24943ced291a01cb08b60588189)|---|---| 
|2014|`ICRA`|[Low-latency event-based visual odometry](https://infoscience.epfl.ch/record/199738/files/ICRA14_Censi.pdf)|---|---| 
|2013|`International Conference on Computer Vision Systems`|[Simultaneous localization and mapping for event-based vision systems](https://www.academia.edu/download/46707309/Simultaneous_Localization_and_Mapping_fo20160622-16469-sz3iui.pdf)|---|---| 
|2012|`IEEE International Conference on Robotics and Biomimetics`|[Event-based particle filtering for robot self-localization](https://www.academia.edu/download/46707382/Event-based_particle_filtering_for_robot20160622-4108-1dk2qxl.pdf)|---|---| 
|2008|`J. Solid State Circ`|[Simultaneous mosaicing and tracking with an event camera](https://bmva-archive.org.uk/bmvc/2014/files/abstract066.pdf)|---|---| 
<!-- |---|`arXiv`|---|---|---| -->
<!-- [![Github stars](https://img.shields.io/github/stars/***.svg)]() -->


## Event-based Depth Estimation
<!-- |---|`arXiv`|---|---|---| -->
<!-- [![Github stars](https://img.shields.io/github/stars/***.svg)]() -->
| Year | Venue | Paper Title | Repository | Note |
|:----:|:-----:| ----------- |:----------:|:----:|
|2025|`IJCV`|[High-Rate Monocular Depth Estimation via Cross Frame-Rate Collaboration of Frames and Events](https://link.springer.com/article/10.1007/s11263-025-02488-2)|[![Github stars](https://img.shields.io/github/stars/liuxu0303/CFRNet.svg)](https://github.com/liuxu0303/CFRNet)|---|
|2025|`CVPR`|[Active Event-based Stereo Vision](https://openaccess.thecvf.com/content/CVPR2025/papers/Li_Active_Event-based_Stereo_Vision_CVPR_2025_paper.pdf)|[![Github stars](https://img.shields.io/github/stars/jianing-li/active_event_based_stereo.svg)](https://github.com/jianing-li/active_event_based_stereo)|---|
|2025|`arXiv`|[DERD-Net: Learning Depth from Event-based Ray Densities](https://arxiv.org/pdf/2504.15863)| [![Github stars](https://img.shields.io/github/stars/tub-rip/DERD-Net.svg)](https://github.com/tub-rip/DERD-Net)|---| 
|2024|`CVPR`|[Multi-Modal Fusion of Event and RGB for Monocular Depth Estimation Using a Unified Transformer-based Architecture](https://openaccess.thecvf.com/content/CVPR2024W/MULA/papers/Devulapally_Multi-Modal_Fusion_of_Event_and_RGB_for_Monocular_Depth_Estimation_CVPRW_2024_paper.pdf)|---|---|
|2024|`IEEE Transactions on Circuits and Systems for Video Technology`|[Event-based Monocular Depth Estimation with Recurrent Transformers](https://ieeexplore.ieee.org/abstract/document/10474340/)|---|---|
|2024|`Proceedings of the IEEE/CVF Winter Conference on Applications of Computer Vision`|[Depth From Asymmetric Frame-Event Stereo: A Divide-and-Conquer Approach](https://openaccess.thecvf.com/content/WACV2024/papers/Chen_Depth_From_Asymmetric_Frame-Event_Stereo_A_Divide-and-Conquer_Approach_WACV_2024_paper.pdf)|---|---|
|2024|`TPAMI`|[Secrets of Event-based Optical Flow, Depth and Ego-motion Estimation by Contrast Maximization](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10517639)|[![Github stars](https://img.shields.io/github/stars/tub-rip/event_based_optical_flow.svg)](https://github.com/tub-rip/event_based_optical_flow)|-|
|2023|`CVPR`|[Low-latency monocular depth estimation using event timing on neuromorphic hardware](https://openaccess.thecvf.com/content/CVPR2023W/EventVision/papers/Chiavazza_Low-Latency_Monocular_Depth_Estimation_Using_Event_Timing_on_Neuromorphic_Hardware_CVPRW_2023_paper.pdf)|---|---|
|2022|`CVPR`|[Stereo Depth from Events Cameras: Concentrate and Focus on the Future](https://openaccess.thecvf.com/content/CVPR2022/papers/Nam_Stereo_Depth_From_Events_Cameras_Concentrate_and_Focus_on_the_CVPR_2022_paper.pdf)|---|---| 
|2022|`Advanced Intelligent Systems`|[Multi-Event-Camera Depth Estimation and Outlier Rejection by Refocused Events Fusion](https://onlinelibrary.wiley.com/doi/pdf/10.1002/aisy.202200221)| [![Github stars](https://img.shields.io/github/stars/tub-rip/dvs_mcemvs.svg)](https://github.com/tub-rip/dvs_mcemvs)|---|
|2022|`arXiv`|[Event-based Stereo Depth Estimation from Ego-motion using Ray Density Fusion](https://arxiv.org/pdf/2210.08927)|---|---|
|2021|`RAL`|[EOMVS: Event-Based Omnidirectional Multi-View Stereo](https://ieeexplore.ieee.org/abstract/document/9479757/)|---|---|
|2021|`RAL`|[Combining Events and Frames using Recurrent Asynchronous Multimodal Networks for Monocular Depth Prediction](https://ieeexplore.ieee.org/ielaam/7083369/9285111/9359329-aam.pdf)|[![Github stars](https://img.shields.io/github/stars/uzh-rpg/rpg_ramnet.svg)](https://github.com/uzh-rpg/rpg_ramnet)|---| 
|2021|`AAAI`|[Deep Event Stereo Leveraged by Event-to-Image Translation](https://ojs.aaai.org/index.php/AAAI/article/download/16171/15978)|---|---| 
|2020|`3DV`|[Learning Monocular Dense Depth from Events](https://arxiv.org/pdf/2010.08350)|[![Github stars](https://img.shields.io/github/stars/uzh-rpg/rpg_e2depth.svg)](https://github.com/uzh-rpg/rpg_e2depth)|---|
|2019|`ICCV`|[Learning an event sequence embedding for dense event-based deep stereo](https://openaccess.thecvf.com/content_ICCV_2019/papers/Tulyakov_Learning_an_Event_Sequence_Embedding_for_Dense_Event-Based_Deep_Stereo_ICCV_2019_paper.pdf)|---|---|
|2019|`CVPR`|[Learning event-based height from plane and parallax](http://openaccess.thecvf.com/content_CVPRW_2019/papers/EventVision/Chaney_Learning_Event-Based_Height_From_Plane_and_Parallax_CVPRW_2019_paper.pdf)|---|---| 
|2019|`CVPR`|[Unsupervised event-based learning of optical flow, depth, and egomotion](https://openaccess.thecvf.com/content_CVPR_2019/papers/Zhu_Unsupervised_Event-Based_Learning_of_Optical_Flow_Depth_and_Egomotion_CVPR_2019_paper.pdf)|-|-| 
|2018|`CVPR`|[A Unifying Contrast Maximization Framework for Event Cameras, with Applications to Motion, Depth and Optical Flow Estimation](https://openaccess.thecvf.com/content_cvpr_2018/papers/Gallego_A_Unifying_Contrast_CVPR_2018_paper.pdf)|-|[supplementary material](https://www.ifi.uzh.ch/dam/jcr:a22071c9-b284-43c6-8f71-6433627b2db2/CVPR18_Gallego.pdf)| 
|2018|`ECCV`|[Semi-dense 3D reconstruction with a stereo event camera](http://openaccess.thecvf.com/content_ECCV_2018/papers/Yi_Zhou_Semi-Dense_3D_Reconstruction_ECCV_2018_paper.pdf)|---|[dataset](https://rpg.ifi.uzh.ch/ECCV18_stereo_davis.html)| 
|2018|`IJCV`|[EMVS: Event-based multi-view stereo—3D reconstruction with an event camera in real-time](https://www.research-collection.ethz.ch/bitstream/handle/20.500.11850/211919/2/s11263-017-1050-6.pdf)|[![Github stars](https://img.shields.io/github/stars/uzh-rpg/rpg_emvs.svg)](https://github.com/uzh-rpg/rpg_emvs)|---|
|2018|`Frontiers in Neuroscience`|[Neuromorphic event-based generalized time-based stereovision](https://www.frontiersin.org/articles/10.3389/fnins.2018.00442/pdf)|---|---|
<!-- |---|`arXiv`|---|---|---| -->
<!-- [![Github stars](https://img.shields.io/github/stars/***.svg)]() -->


## Event-based Feature Detection and Tracking
<!-- |---|`arXiv`|---|---|---| -->
<!-- [![Github stars](https://img.shields.io/github/stars/***.svg)]() -->
| Year | Venue | Paper Title | Repository | Note |
|:----:|:-----:| ----------- |:----------:|:----:|
|2025|`TPAMI`|[Data-driven Feature Tracking for Event Cameras with and without Frames](https://drive.google.com/file/d/1WfHx8tD2xw3quaIe6xoZZTRG4Nv1xe_u/view)|[![Github stars](https://img.shields.io/github/stars/uzh-rpg/deep_ev_tracker.svg)](https://github.com/uzh-rpg/deep_ev_tracker)|---|
|2023|`CVPR`|[Data-driven feature tracking for event cameras](https://openaccess.thecvf.com/content/CVPR2023/papers/Messikommer_Data-Driven_Feature_Tracking_for_Event_Cameras_CVPR_2023_paper.pdf)|[![Github stars](https://img.shields.io/github/stars/uzh-rpg/deep_ev_tracker.svg)](https://github.com/uzh-rpg/deep_ev_tracker)|---|
|2020|`BMVC`|[Haste: multi-hypothesis asynchronous speeded-up tracking of events](https://www.research-collection.ethz.ch/bitstream/handle/20.500.11850/439297/1/BMVC2020_HASTE_0744.pdf)|[![Github stars](https://img.shields.io/github/stars/ialzugaray/haste.svg)](https://github.com/ialzugaray/haste)|---| 
|2019|`IJCV`|[EKLT: Asynchronous photometric feature tracking using events and frames](https://www.zora.uzh.ch/id/eprint/197701/1/eklt_ijcv19.pdf)|[![Github stars](https://img.shields.io/github/stars/uzh-rpg/rpg_eklt.svg)](https://github.com/uzh-rpg/rpg_eklt)|[Feature Tracking Analysis](https://github.com/uzh-rpg/rpg_feature_tracking_analysis)|
|2018|`RAL`|[Asynchronous corner detection and tracking for event cameras in real time](https://www.research-collection.ethz.ch/bitstream/handle/20.500.11850/277131/RAL2018-camera-ready.pdf)|[![Github stars](https://img.shields.io/github/stars/ialzugaray/arc_star_ros.svg)](https://github.com/ialzugaray/arc_star_ros)|---|
|2017|`BMVC`|[Fast event-based corner detection](https://www.zora.uzh.ch/id/eprint/138925/1/BMVC17_Mueggler%20(3).pdf)|[![Github stars](https://img.shields.io/github/stars/uzh-rpg/rpg_corner_events.svg)](https://github.com/uzh-rpg/rpg_corner_events) |---|
<!-- |---|`arXiv`|---|---|---| -->
<!-- [![Github stars](https://img.shields.io/github/stars/***.svg)]() -->

## Event-based 3DGS or NeRF
* Paper survey in 3DGS-SLAM includes the event camera, please refer to [Link](https://github.com/KwanWaiPang/Awesome-3DGS-SLAM#Event-based-3DGS)
* NeRF:

<!-- |---|`arXiv`|---|---|---| -->
<!-- [![Github stars](https://img.shields.io/github/stars/***.svg)]() -->
| Year | Venue | Paper Title | Repository | Note |
|:----:|:-----:| ----------- |:----------:|:----:|
|2024|`arXiv`|[Evdnerf: Reconstructing event data with dynamic neural radiance fields](https://openaccess.thecvf.com/content/WACV2024/papers/Bhattacharya_EvDNeRF_Reconstructing_Event_Data_With_Dynamic_Neural_Radiance_Fields_WACV_2024_paper.pdf)|[![Github stars](https://img.shields.io/github/stars/anish-bhattacharya/EvDNeRF.svg)](https://github.com/anish-bhattacharya/EvDNeRF)|---|
|2023|`RAL`|[E-nerf: Neural radiance fields from a moving event camera](https://arxiv.org/pdf/2208.11300)|[![Github stars](https://img.shields.io/github/stars/knelk/enerf.svg)](https://github.com/knelk/enerf)|---| 
|2023|`Proceedings of the IEEE/CVF Winter Conference on Applications of Computer Vision`|[Ev-NeRF: Event based neural radiance field](https://openaccess.thecvf.com/content/WACV2023/papers/Hwang_Ev-NeRF_Event_Based_Neural_Radiance_Field_WACV_2023_paper.pdf)|---|---| 
|2023|`NIPS`|[Multimodal Neural Surface Reconstruction: Recovering the Geometry and Appearance of 3D Scenes from Events and Grayscale Images](https://openreview.net/pdf?id=8hz6X2GGnD)|---|---| 
|2023|`CVPR`|[EventNeRF: Neural radiance fields from a single colour event camera](http://openaccess.thecvf.com/content/CVPR2023/papers/Rudnev_EventNeRF_Neural_Radiance_Fields_From_a_Single_Colour_Event_Camera_CVPR_2023_paper.pdf)|[![Github stars](https://img.shields.io/github/stars/r00tman/EventNeRF.svg)](https://github.com/r00tman/EventNeRF)|[website](https://4dqv.mpi-inf.mpg.de/EventNeRF/)| 


## Event Dataset for SLAM Benchmarking
* Most of the data sequence can be downloaded from *website* or *github*, while the marked as `*Not-release` is not publicly available

<!-- |---|`arXiv`|---|---|---| -->
<!-- [![Github stars](https://img.shields.io/github/stars/***.svg)]() -->
| Year | Venue | Paper Title | Repository | Note |
|:----:|:-----:| ----------- |:----------:|:----:|
|2025|`arXiv`|[MTevent: A Multi-Task Event Camera Dataset for 6D Pose Estimation and Moving Object Detection](https://arxiv.org/pdf/2505.11282)|[![Github stars](https://img.shields.io/github/stars/shrutarv/MTevent_toolkit.svg)](https://github.com/shrutarv/MTevent_toolkit) |[website](https://huggingface.co/datasets/anas-gouda/MTevent)| 
|2024|`RAL`|[CEAR: Comprehensive Event Camera Dataset for Rapid Perception of Agile Quadruped Robots](https://arxiv.org/pdf/2404.04698)|---|[website](https://daroslab.github.io/cear/)| 
|2023|`TIV`|[ECMD: An Event-Centric Multisensory Driving Dataset for SLAM](https://arxiv.org/pdf/2311.02327)|---|[website](https://arclab-hku.github.io/ecmd/)| 
|2023|`European Conference on Mobile Robots`|[Stereo visual localization dataset featuring event cameras](https://ieeexplore.ieee.org/abstract/document/10256407/)|---|*Not-release<br>[website](https://bitbucket.org/unizg-fer-lamor/event-dataset/)| 
|2023|`TITS`|[MA-VIED: A Multisensor Automotive Visual Inertial Event Dataset](https://ieeexplore.ieee.org/abstract/document/10254473/)| [![Github stars](https://img.shields.io/github/stars/isarlab-department-engineering/MA-VIED.svg)](https://github.com/isarlab-department-engineering/MA-VIED)|---| 
|2023|`CVPR`|[M3ED: Multi-Robot, Multi-Sensor, Multi-Environment Event Dataset](https://openaccess.thecvf.com/content/CVPR2023W/EventVision/papers/Chaney_M3ED_Multi-Robot_Multi-Sensor_Multi-Environment_Event_Dataset_CVPRW_2023_paper.pdf)|[![Github stars](https://img.shields.io/github/stars/daniilidis-group/m3ed.svg)](https://github.com/daniilidis-group/m3ed)|[website](https://m3ed.io/)| 
|2022|`Github`|[HKU-Dataset for Event-based VO/VIO/SLAM](https://github.com/arclab-hku/Event_based_VO-VIO-SLAM)|[![Github stars](https://img.shields.io/github/stars/arclab-hku/Event_based_VO-VIO-SLAM.svg)](https://github.com/arclab-hku/Event_based_VO-VIO-SLAM)|HKU-Dataset|
|2022|`RAL`|[ViViD++: Vision for Visibility Dataset](https://arxiv.org/pdf/2204.06183)|---|[website](https://visibilitydataset.github.io/)| 
|2022|`IROS`|[FusionPortable: A Multi-Sensor Campus-Scene Dataset for Evaluation of Localization and Mapping Accuracy on Diverse Platforms](https://arxiv.org/pdf/2208.11865)|---|*Not-release| 
|2022|`CVPR`|[Event-aided Direct Sparse Odometry](https://openaccess.thecvf.com/content/CVPR2022/papers/Hidalgo-Carrio_Event-Aided_Direct_Sparse_Odometry_CVPR_2022_paper.pdf)|---|[https://rpg.ifi.uzh.ch/eds.html](website)| 
|2022|`RAL`|[VECtor: A Versatile Event-Centric Benchmark for Multi-Sensor SLAM](https://arxiv.org/pdf/2207.01404)|---|[website](https://star-datasets.github.io/vector/)<br>[rosbag format](https://github.com/arclab-hku/Event_based_VO-VIO-SLAM#Modified-vector-dataset)| 
|2021|`RAL`|[M2dgr: A multi-sensor and multi-scenario slam dataset for ground robots](https://arxiv.org/pdf/2112.13659)|[![Github stars](https://img.shields.io/github/stars/SJTU-ViSYS/M2DGR.svg)](https://github.com/SJTU-ViSYS/M2DGR)|*The Event Data is just Noise| 
|2021|`IROS`|[TUM-VIE: The TUM stereo visual-inertial event dataset](https://arxiv.org/pdf/2108.07329)|---|[website](https://go.vision.in.tum.de/tumvie)| 
|2021|`ICRA`|[An Event-based vision dataset for visual navigation tasks in agricultural environments](https://ieeexplore.ieee.org/abstract/document/9561741/)|---|AGRI-EBV-AUTUMN<br>[website](https://ieee-dataport.org/open-access/agri-ebv-autumn)| 
|2021|`RAL`|[The GRIFFIN perception dataset: Bridging the gap between flapping-wing flight and robotic perception](https://arxiv.org/pdf/2101.10371)|---|[website](http://grvc.us.es/eye-bird-dataset)| 
|2021|`RAL`|[Dsec: A stereo event camera dataset for driving scenarios](https://ieeexplore.ieee.org/ielaam/7083369/9399748/9387069-aam.pdf)|---|[website](https://dsec.ifi.uzh.ch/)<br>[rosbag format](https://github.com/arclab-hku/Event_based_VO-VIO-SLAM#Modified-dsec-dataset)| 
|2020|`arXiv`|[A large scale event-based detection dataset for automotive](https://arxiv.org/pdf/2001.08499)|---|*Not-release<br>[website](https://www.prophesee.ai/2020/01/24/prophesee-gen1-automotive-detection-dataset/)| 
|2020|`RAL`|[Event-based visual place recognition with ensembles of temporal windows](https://arxiv.org/pdf/2006.02826)|[![Github stars](https://img.shields.io/github/stars/Tobias-Fischer/ensemble-event-vpr.svg)](https://github.com/Tobias-Fischer/ensemble-event-vpr) |Brisbane-Event-VPR<br>[website](https://zenodo.org/records/4302805)| 
|2020|`ITSC`|[Ddd20 end-to-end event camera driving dataset: Fusing frames and events with deep learning for improved steering prediction](https://arxiv.org/pdf/2005.08605)|---|[website](https://sites.google.com/view/davis-driving-dataset-2020/home)| 
|2019|`TPAMI`|[High speed and high dynamic range video with an event camera](https://arxiv.org/pdf/1906.07165)|---|E2VID<br>[website](https://rpg.ifi.uzh.ch/E2VID.html)| 
|2019|`CVPR`|[CED: Color event camera dataset](http://openaccess.thecvf.com/content_CVPRW_2019/papers/EventVision/Scheerlinck_CED_Color_Event_Camera_Dataset_CVPRW_2019_paper.pdf)|---|[website](https://rpg.ifi.uzh.ch/CED.html)| 
|2019|`ICRA`|[Are we ready for autonomous drone racing? the UZH-FPV drone racing dataset](https://www.zora.uzh.ch/id/eprint/197739/1/ICRA19_Delmerico.pdf)|[![Github stars](https://img.shields.io/github/stars/uzh-rpg/uzh_fpv_open.svg)](https://github.com/uzh-rpg/uzh_fpv_open)|UZH-FPV<br>[website](https://fpv.ifi.uzh.ch/)| 
|2018|`RAL`|[The multivehicle stereo event camera dataset: An event camera dataset for 3D perception](https://arxiv.org/pdf/1801.10202)|---|MVSEC<br>[website](https://daniilidis-group.github.io/mvsec/)| 
|2017|`arXiv`|[DDD17: End-to-end DAVIS driving dataset](https://arxiv.org/pdf/1711.01458)|---|[website](https://docs.google.com/document/d/1HM0CSmjO8nOpUeTvmPjopcBcVCk7KXvLUuiZFS6TWSg/pub)| 
|2017|`IJRR`|[The event-camera dataset and simulator: Event-based data for pose estimation, visual odometry, and SLAM](https://journals.sagepub.com/doi/pdf/10.1177/0278364917691115)|---|davis240c<br>[website](https://rpg.ifi.uzh.ch/davis_data.html)|
<!-- |---|`arXiv`|---|---|---| -->
<!-- [![Github stars](https://img.shields.io/github/stars/***.svg)]() -->


## Other Resources
* [Course: Event-based Robot Vision](https://www.youtube.com/playlist?list=PL03Gm3nZjVgUFYUh3v5x8jVonjrGfcal8)
* [HKU-Dataset for Event-based VO/VIO/SLAM](https://github.com/arclab-hku/Event_based_VO-VIO-SLAM)
* Paper Survey for Event-based Contrast Maximization: [Paper list](https://github.com/KwanWaiPang/Awesome-Event-based-Contrast-Maximization) and [blog](https://kwanwaipang.github.io/Awesome-Event-based-Contrast-Maximization/)
* SLAM Handbook: [Chapter10: Event-based SLAM](https://github.com/SLAM-Handbook-contributors/slam-handbook-public-release)
* More related papers:

| Year | Venue | Paper Title | Repository | Note |
|:----:|:-----:| ----------- |:----------:|:----:|
|2025|`arXiv`|[Temporal and Rotational Calibration for Event-Centric Multi-Sensor Systems](https://arxiv.org/pdf/2508.12564)|[![Github stars](https://img.shields.io/github/stars/NAIL-HNU/EvMultiCalib.svg)](https://github.com/NAIL-HNU/EvMultiCalib)|---|
|2023|`arXiv`|[Event-based simultaneous localization and mapping: A comprehensive survey](https://arxiv.org/pdf/2304.09793)|---|---|
|2021|`CVPR`|[How to Calibrate Your Event Camera](https://openaccess.thecvf.com/content/CVPR2021W/EventVision/papers/Muglikar_How_To_Calibrate_Your_Event_Camera_CVPRW_2021_paper.pdf)| [![Github stars](https://img.shields.io/github/stars/uzh-rpg/e2calib.svg)](https://github.com/uzh-rpg/e2calib)|---|
|2020|`CVPR`|[Video to Events: Recycling Video Datasets for Event Cameras](https://openaccess.thecvf.com/content_CVPR_2020/papers/Gehrig_Video_to_Events_Recycling_Video_Datasets_for_Event_Cameras_CVPR_2020_paper.pdf)|[![Github stars](https://img.shields.io/github/stars/uzh-rpg/rpg_vid2e.svg)](https://github.com/uzh-rpg/rpg_vid2e) |[Test](https://kwanwaipang.github.io/File/Blogs/Poster/esim.html)|
|2020|`TPAMI`|[Event-based vision: A survey](https://ieeexplore.ieee.org/iel7/34/4359286/09138762.pdf)|---|---|
|2018|`CoRL`|[Esim: an open event camera simulator](http://proceedings.mlr.press/v87/rebecq18a/rebecq18a.pdf)|[![Github stars](https://img.shields.io/github/stars/uzh-rpg/rpg_esim.svg)](https://github.com/uzh-rpg/rpg_esim)|---|

<!-- |---|`arXiv`|---|---|---| -->
<!-- [![Github stars](https://img.shields.io/github/stars/***.svg)]() --> 


