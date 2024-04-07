# Awsome-Multi-modal-based-PHM (基于多传感器信息的故障诊断和预测，持续更新)

This repository contains papers, code, and datasets related to multi-modal-based fault diagnosis.  

We will keep updating this library.  

# Contents
- [Papers](#section-id1)
 
- [Data](#section-id2)

- [Code](#section-id3)

## Papers
<a name="section-id1"></a>

### Heterogeneous sensors

| Year 	| Index 	| Title                                                                                                                                                                       	| modal                                     	|
|------	|-------	|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------	|-------------------------------------------	|
| 2024 	| 1     	| Multi-modal data cross-domain fusion network for gearbox fault   diagnosis under variable operating conditions                                                              	| vibration signal+infrared image           	|
|      	| 2     	| Multi-sensor multi-mode fault diagnosis for lithium-ion   battery packs with time series and discriminative features                                                        	| current+voltage+temperature               	|
|      	| 3     	| Deep feature interactive network for machinery fault diagnosis   using multi-source heterogeneous data                                                                      	| vibration signal+infrared image           	|
|      	| 4     	| A synchronization-induced cross-modal contrastive learning   strategy for fault diagnosis of electromechanical systems under   semi-supervised learning with current signal 	| vibration signal+current signal           	|
|      	| 5     	| Multi-sensor fusion fault diagnosis method of windturbine   bearing based on adaptive convergent viewable neural networks                                                   	| vibration signal+acoustic signal          	|
| 2023 	| 6     	| A New Multisensor Partial Domain Adaptation Method for   Machinery Fault Diagnosis Under Different Working Conditions                                                       	| vibration signal+acoustic signal          	|
|      	| 7     	| AI-enabled and multimodal data driven smart health monitoring   of wind power systems: A case study                                                                         	| image+acoustic                            	|
|      	| 8     	| Online Fault Diagnosis of Harmonic Drives Using   Semi-supervised Contrastive Graph Generative Network via Multimodal data                                                  	| motor encoder+hall current sensor.        	|
|      	| 9     	| Cross-modal Fusion Convolutional Neural Networks with Online   Soft Label Training Strategy for Mechanical Fault Diagnosis                                                  	| acoustic+vibration                        	|
|      	| 10    	| An Online Multiple Open-Switch Fault Diagnosis Method for   T-Type Three-Level Inverters Based on Multimodal Deep Residual Filter Network                                   	| current + voltage                         	|
|      	| 11    	| Multi-modal information analysis for fault diagnosis with   time-series data from power transformer                                                                         	| infrared image+dissolved gas data         	|
|      	| 12    	| Multi-Sensor Fault Diagnosis for Misalignment and Unbalance   Detection using Machine Learning                                                                              	| Infrared image+vibration                  	|
|      	| 13    	| A Residual Multihead Self-Attention Network Using Multimodal   Shallow Feature Fusion for Motor Fault Diagnosis                                                             	| vibration signal+current signal           	|
| 2022 	| 14    	| Multi-heterogeneous sensor data fusion method via   convolutional neural network for fault diagnosis of wheeled mobile robot                                                	| inertial measurement unit+encoder         	|
|      	| 15    	| Bearing fault diagnosis method based on attention mechanism   and multilayer fusion network                                                                                 	| vibration signal+current signal           	|
|      	| 16    	| Intelligent worm gearbox fault diagnosis under various working   conditions using vibration, sound and thermal features                                                     	| vibration+sound+ thermal                  	|
|      	| 17    	| A Multisensor Information Fusion Method for High-Reliability   Fault Diagnosis of Rotating Machinery                                                                        	| Infrared image+vibration                  	|
|      	| 18    	| Multisensory data fusion-based deep learning approach for   fault diagnosis of an industrial autonomous transfer vehicle                                                    	| vibration signal+acoustic signal          	|
|      	| 19    	| Multiview enhanced fault diagnosis for wind turbine gearbox   bearings with fusion of vibration and current signals                                                         	| vibration signal+current signal           	|
|      	| 20    	| A multi–modal unsupervised fault detection system based on   power signals and thermal imaging via deep AutoEncoder neural network                                          	| thermal images+current+power measurements 	|
| 2021 	| 21    	| Bearing fault diagnosis based on vibro-acoustic data fusion   and 1D-CNN network                                                                                            	| vibration signal+acoustic signal          	|
|      	| 22    	| Novel Three-Stage Feature Fusion Method of Multimodal Data for   Bearing Fault Diagnosis                                                                                    	| vibration signal+ torque signals          	|
|      	| 23    	| A Fusion CWSMM-based Framework for Rotating Machinery Fault   Diagnosis under Strong Interference and Imbalanced Case                                                       	| Infrared image+vibration                  	|
| 2020 	| 24    	| Dynamic Routing-based Multimodal Neural Network for   Multi-sensory Fault Diagnosis of Induction Motor                                                                      	| vibration signal+current signal           	|
| 2019 	| 25    	| Multilevel Information Fusion for Induction Motor Fault   Diagnosis                                                                                                         	| vibration signal+current signal           	|
|      	| 26    	| Thermal Imaging and Vibration-Based Multisensor Fault   Detection for Rotating Machinery                                                                                    	| Infrared image+vibration                  	|
| 2018 	| 27    	| Deep Coupling Autoencoder for Fault Diagnosis With Multimodal   Sensory Data                                                                                                	| vibration signal+acoustic signal          	|
| 2016 	| 28    	| Gearbox fault diagnosis based on deep random forest fusion of   acoustic and vibratory signals                                                                              	| vibration signal+acoustic signal          	|
|      	|       	|                                                                                                                                                                             	|                                           	|
### Homogeneous sensors

| Year 	| Index 	| Title                                                                                                                                      	| modal     	|
|------	|-------	|--------------------------------------------------------------------------------------------------------------------------------------------	|-----------	|
| 2024 	| 1     	| MIFDELN: A multi-sensor information fusion deep ensemble   learning network for diagnosing bearing faults in noisy scenarios               	| Vibration 	|
|      	| 2     	| Cross-Sensor Correlative Feature Learning and Fusion for   Intelligent Fault Diagnosis                                                     	| Vibration 	|
| 2023 	| 3     	| MIM-Graph: A multi-sensor network approach for fault diagnosis   of HSR Bogie bearings at the IoT edge via mutual information maximization 	| Vibration 	|
|      	| 4     	| Multi-sensor information fusion and coordinate attention-based   fault diagnosis method and its interpretability research                  	| Vibration 	|
|      	| 5     	| A signal-to-image fault classification method based   onmulti-sensor data for robotic grinding monitoring                                  	| Vibration 	|
|      	| 6     	| A fault diagnosis method based on feature-level fusion of   multi-sensor information for rotating machinery                                	| Vibration 	|
| 2022 	| 7     	| Intelligent Mechanical Fault Diagnosis Using Multisensor   Fusion and Convolution Neural Network                                           	| Vibration 	|
|      	| 8     	| Bearing Fault Diagnosis Method Based on Complementary Feature   Extraction and Fusion of Multisensor Data                                  	| Vibration 	|
|      	| 9     	| Mix-VAEs: A novel multisensor information fusion model for   intelligent fault diagnosis                                                   	| Vibration 	|
| 2021 	| 10    	| A novel approach of multisensory fusion to collaborative fault   diagnosis in maintenance                                                  	| Vibration 	|
|      	| 11    	| Multi-sensor gearbox fault diagnosis by using feature-fusion   covariance matrix and multi-Riemannian kernel ridge regression              	| Vibration 	|

##  Open-source dataset
<a name="section-id2"></a>
|         Type         	| Index 	| Year 	|  Dataset Name  	| Component 	| Sensor Number 	|      Modality      	|    Data Link    	|
|:--------------------:	|:-----:	|:----:	|:--------------:	|:---------:	|:-------------:	|:------------------:	|:---------------:	|
|   Homogenous sensor  	|   1   	| 2015 	|      CWRU      	|  Bearing  	|       2       	|      vibration     	| [[data link]()] 	|
|          　          	|   2   	| 2016 	|       KAT      	|  Bearing  	|       　      	|      vibration     	| [[data link]()] 	|
|          　          	|   3   	| 2019 	|       SEU      	|  Gearbox  	|       　      	|      vibration     	| [[data link]()] 	|
|          　          	|   4   	| 2019 	|      DIRG      	|  Bearing  	|       　      	|      vibration     	| [[data link]()] 	|
| Heterogeneous sensor 	|   5   	| 1996 	|      Mill      	|     /     	|               	|         　         	| [[data link]()] 	|
|          　          	|   6   	| 2023 	| iFLYTEKbearing 	|  Bearing  	|       　      	| vibration+acoustic 	| [[data link]()] 	|
|          　          	|   7   	| 2024 	|    HUSTmotor   	|   motor   	|       2       	| vibration+acoustic 	| [[data link]()] 	|


# Contact

If you have any problem, please feel free to contact me.

Name: Chao Zhao

Email address: zhaochao734@hust.edu.cn


# Related Projects

- We collect all open source mechanical failure datasets [[Link](https://github.com/CHAOZHAO-1/Machine-Fault-Dataset)]
  
- We have sorted out the domain generalization-based fault diagnosis, including data, papers, codes and so on [[Link](https://github.com/CHAOZHAO-1/DG-PHM)]
