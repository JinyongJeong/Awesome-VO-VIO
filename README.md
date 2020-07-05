# Awesome Visual-odometry (VO) and Visual-inertial-odometry (VIO) [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)



## Dataset (VO)
- [KITTI](http://www.cvlibs.net/datasets/kitti/eval_odometry.php)

## Dataset (VIO)
- [EuRoC MAV Dataset](https://projects.asl.ethz.ch/datasets/doku.php?id=kmavvisualinertialdatasets)
- [Fast Flight Dataset](https://github.com/KumarRobotics/msckf_vio/wiki/Dataset)
- [TUM VI Dataset](https://vision.in.tum.de/data/datasets/visual-inertial-dataset)

## Open Source (VO)

### Feature based method
- [PTAM](https://github.com/ethz-asl/ethzasl_ptam)
- [REMODE](https://github.com/uzh-rpg/rpg_open_remode)
- [ORB-SLAM](https://github.com/raulmur/ORB_SLAM)
- [ORB-SLAM2](https://github.com/raulmur/ORB_SLAM2)
- [Pro-SLAM](https://github.com/AhmedShaban94/ProSLAM)
- [OpenVSLAM](https://github.com/xdspacelab/openvslam)
- [UcoSLAM](https://github.com/lambdaloop/ucoslam-cv3)

### Direct method
- [DTAM](https://github.com/TeddybearCrisis/OpenDTAM-3.1)
- [LSD-SLAM](https://github.com/tum-vision/lsd_slam)
- [SVO](https://github.com/uzh-rpg/rpg_svo)
- [SVO2](https://github.com/symao/svo2)
- [DSO](https://github.com/JakobEngel/dso)

## Open Source (VIO)

- [VINS Mono](https://github.com/HKUST-Aerial-Robotics/VINS-Mono)
- [VINS Fusion](https://github.com/HKUST-Aerial-Robotics/VINS-Fusion)
- [Open VINS](https://github.com/rpng/open_vins)
- [MSCKF_VIO](https://github.com/KumarRobotics/msckf_vio)
- [OKVIS](https://github.com/ethz-asl/okvis)
- [ROVIO](https://github.com/ethz-asl/rovio)
- [Maplab](https://github.com/ethz-asl/maplab_rovio)

| Category | Paper | Summary | Group | Publisher | Year | Author | Paper Link | Github Link |
|-|-|-|-|-|-|-|-|-|
| VO(Feature-base) | MonoSLAM: realtime single camera SLAM | Mono-SLAM | Imperial college | PAMI | 2007 | Andrew J. Davison/ Olivier Stasse | https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=4160954&casa_token=ocUpw-ETyoYAAAAA:OA8njpLXpG5SeDxGo3PyV6P3Za7lj8MVlyxHcP2DINZopX7nhx-UQzBm9YeHcFVc8DAepztD | https://github.com/rrg-polito/mono-slam |
|  | Parallel Tracking and Mapping on a Camera Phone/ S-PTAM: Stereo parallel tracking and mapping | PTAM/ S-PTAM | oxford | ISMAR | 2009 | Georg Klein/ David Murray | https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=5336495&casa_token=ll9RhGU6XmUAAAAA:qLvAnV-CWWWmzfncpEzMTFU57jw_5UPkrsguZ1pQEIuxjRNH4EOLuwS0Dr3mOAVxKghDwMAr |  |
|  | REMODE: Probabilistic, monocular dense reconstruction in real time | REMODE | ETH | ICRA | 2014 | Matia Pizzoli/ Davide Scaramuzza |  | https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=6907233&casa_token=GyVH_tkmmoIAAAAA:t3nUxue0XwippewDGP0R2SSWR8-BDULImgobW_v2jd3KliHjlfth5qQSrsoeFEbOvKZxuXf1 |
|  | ORB-SLAM: a versatile and accurate monocular SLAM system | ORB-SLAM | Zaragoza | TRO | 2015 | Raul Mur-Artal/ Juan D. Tardos | https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=7219438&casa_token=8bptlPQoSj8AAAAA:VgnQUHUd76D74otic8lcKs1WnodOR9CCsqalqHwVk1cV3lvDiRYalotx1itJcALBCVVMKdV7 |  |
|  | Proslam: Graph SLAM from a programmer's perspective | pro-SLAM |  | ICRA | 2018 | Dominik Schlegel/ Giorgio Grisetti | https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8461180&casa_token=NDpAFNSQKwQAAAAA:B3aP6KUqPrU5LlLvUEyxS5d7brJvJLuNH_XTDyLvwjwYzH8ETQXMEXT07Rm_UBiGnFYVigo6 | https://github.com/NamDinhRobotics/proSLAM |
|  | OpenVSLAM: A Versatile Visual SLAM Framework | OpenVSLAM |  | ACM | 2019 | Shinya Sumikura/ Ken Sakurada | https://dl.acm.org/doi/pdf/10.1145/3343031.3350539?casa_token=upYd2H8-9iQAAAAA%3A_sLRuDkKSt9OfLuJnIJtYcSb1KwaNhZKbHImZ-VaqO9Y-3iKiuVcB7sZAZt3PsK6Z1A59V7sxXQwdRo | https://github.com/xdspacelab/openvslam |
|  | UcoSLAM: Simultaneous Localization and Mapping by Fusion of KeyPoints and Squared Planar Markers | VO + Marker |  | Arxiv | 2019 | Rafael Munoz-Salinas/ R. Medina-Carnicer | https://arxiv.org/pdf/1902.03729.pdf | https://github.com/lambdaloop/ucoslam-cv3 |
| VO(Direct method) | DTAM: Dense tracking and mapping in real-time | DTAM | Imperial college | ICCV | 2011 | Richard Newcombe/ Andrew J. Davison | http://ugweb.cs.ualberta.ca/~vis/courses/CompVis/readings/3DReconstruction/dtam.pdf | https://github.com/anuranbaka/OpenDTAM |
|  | LSD-SLAM: Large-scale direct monocular SLAM | LSD-SLAM | TUM | ECCV | 2014 | Jakob Engel/ Daniel Cremers | http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.646.7193&rep=rep1&type=pdf | https://github.com/tum-vision/lsd_slam |
|  | SVO: Fast semi-direct monocular visual odometry | SVO | ETH | ICRA | 2014 | Christian Forster/ Davide Scaramuzza | https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=6906584&casa_token=e0Moh5-SPYoAAAAA:RimrVnGDDOPzcXtWflDM_zwQR3reV87xDGTEh9dBPfnJS6Ps6HhtomygpQL26vxQL_6HCFSx | https://github.com/uzh-rpg/rpg_svo |
|  | SVO2 | SVO2 |  |  |  |  |  |  |
|  | Direct sparse odometry | DSO | TUM | PAMI | 2018 | Jakob Engel/ Daniel Cremers |  | https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=7898369 |
| VIO | A multi-state constraint Kalman filter for vision-aided inertial navigation | MSCKF | Minnesota | ICRA | 2007 | Anastasios I. Mourikis/ Stegios I. Roumeliotis | https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=4209642&casa_token=nf_xDVl0fLsAAAAA:qk_WrEd9z_xTdGwGAkgGo08CmB3yettabBYVOc8sMubJN3r2aGB9bYx5JReTzj2yR2-BZSrE | https://github.com/KumarRobotics/msckf_vio |
|  | Robust vision-aided navigation using sliding-window factor graph | Sliding window approach |  | ICRA | 2013 | Han-pang Chiu/ Rakesh Kumar | https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=6630555&casa_token=hAFeDN2QZsYAAAAA:AKQm2s5T8GEbkVnJroyV48zaj33nGRAEDxEnqt8T79SGISMCDQ8H6bqFL2l8IAOjXhYS9BWy |  |
|  | Keyframe-based visual–inertial odometry using nonlinear optimization | Global optimization approach | ETH | IJRR | 2015 | Stefan Leutenegger/ Paul Furgale | https://journals.sagepub.com/doi/pdf/10.1177/0278364914554813?casa_token=jsKuLFCNeBMAAAAA:nB1VDGIvPffhzWNihvv1vcGS8FM3cgsFO6VVDDitNew7s1HGM_JrmtNzxvpa46d0kNrJF96dluA4 |  |
|  | IMU preintegration on manifold for efficient visual-inertial maximum-a-posteriori estimation | IMU Preintegration | ETH | TRO/ RSS | 2015, 2016 | Christain Forster/ Davide Scaramuzza | https://arxiv.org/pdf/1512.02363.pdf,https://smartech.gatech.edu/bitstream/handle/1853/55417/IMU%20Preintegration%20on%20Manifold%20for%20Efficient.pdf?sequence=1&isAllowed=y,https://www.researchgate.net/profile/Davide_Scaramuzza2/publication/286513661_On-Manifold_Preintegration_for_Real-Time_Visual-Inertial_Odometry/links/5a4231480f7e9ba868a281f1/On-Manifold-Preintegration-for-Real-Time-Visual-Inertial-Odometry.pdf |  |
|  | Keyframe-based visual–inertial odometry using nonlinear optimization | OKVIS | ETH | IJRR | 2015 | Stefan Leutenegger / Paul Furgale | https://journals.sagepub.com/doi/pdf/10.1177/0278364914554813?casa_token=oILTEHQI9YEAAAAA:BaiwqkcamMvRdclAM455MN2pwRv8tkUKWk1tIT8oJ0UAcVoYK3GLb3HAFAJPGr8X_ub3cYVsi7Aq | https://github.com/ethz-asl/okvis |
|  | Simultaneous state initlaization and gyroscope bias calibration in visual inertial aided navigation | IMU + Camera initialization | ETH | RAL | 2017 | Jacques Kaiser/ Davide Scaramuzza | https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=7390213&casa_token=aYEDDgQOQ5kAAAAA:pL8yxTFEmG15AxSGEcy0Fd_5u3b_IPuJKM3u7riKFXlZFyIMOT4Wz8TsujzWqS4gnaW9-AO0 |  |
|  | Rovio/ Roviloi/ Maplab | Rovio/ Roviloi/ Maplab | ETH | IROS/ IJRR | 2015/ 2017 | Michael Bloesch/ Roland Siegwart | https://journals.sagepub.com/doi/pdf/10.1177/0278364917728574?casa_token=0u2wF2vQIVMAAAAA:xd81KJ_h0doNHGkt1Fbe6dYLqXRKdrSejpCFgcMXdfQ07rgrBzl2LCMAdthFfCdDIlif8Cu6gUey,https://www.research-collection.ethz.ch/bitstream/handle/20.500.11850/155340/1/eth-48374-01.pdf | https://github.com/ethz-asl/rovio |
|  | Vins-mono: A robust and versatile monocular visual-inertial state estimator / A General Optimization-based Framework for global pose estimation with multiple sensors | VINS-Mono/ VINS-Fusion | HKUST | TRO/ arxiv | 2018/ 2019 | Tong Qin/ Shaojie Shen | https://arxiv.org/pdf/1901.03642.pdf,https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8421746&casa_token=zKwB9VXPhOcAAAAA:dJ3nzTW5cu8UGksKC7cAP4VUZ0k0lffY2ZKXS6LmllXw1GPD_NSlQx4HuF2aDY3wotjGH3OG | https://github.com/HKUST-Aerial-Robotics/VINS-Fusion,https://github.com/HKUST-Aerial-Robotics/VINS-Mono |
|  | Robust stereo visual inertial odometry for fast autonomous flight | Stereo + IMU | Kumar lab (penn) | RAL | 2018 | Ke Sun/ Vijay Kumar | https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8258858&casa_token=9HVSH95BMDAAAAAA:YoiAMx2aVwrFFE9vWNFUog-NrYpGDUvV_m-uV-npMyHtSKNUWYozWYQoycg943pdbP7IsItH |  |
