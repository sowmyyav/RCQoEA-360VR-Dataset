# **RCQoEA-360VR-Dataset: Real-time, Continuous QoE scores for HMD-based 360° VR (RCQoEA 360VR) Dataset**

The RCQoEA-360VR dataset is a novel multi-modal dataset designed for continuous QoE evaluation in virtual reality (VR) environments. The dataset contains continuous QoE annotations, synchronised physiological signals (ECG and GSR), behavioural data (eye and head movements) and post-viewing QoE ratings gathered through a within-VR interface from 32 participants. RCQoEA-360VR addresses a critical gap in existing public datasets by providing a fine-grained, synchronised multimodal data for immersive QoE analysis, as well as behavioural modelling, adaptive streaming, and implicit perceptual analysis.

## **Dataset Structure**

The RCQoEA-360VR folder contains the following six subfolders

    1.Behavioral_Data
    2.Physiological_Data
    3.QoE_Annotation_Data
    4.Questionnaires
    5.Scripts
    6.Stimuli

The following is a detailed description of each sub-file:

###1.Behavioral_Data

- Raw_EM_Data
	contains the raw eye movement captured from each participant
- Raw_HM_Data
	contains the raw head movement captured from each participant

###2.Physiological_Data

- ECG
	contains the raw and processed ECG data captured from Polar H10 chest belt for each participant
- GSR
	contains the raw and processed GSR data captured from Shimmer GSR device for each participant

###3.QoE_Annotation_Data

- Continuous_QoE_Score
	contains the continuous QoE annotation data captured from the touch-pad for each participant
- Post_Video_QoE_Score
	contains the post-video QoE scores captured using within-VR interface for each participant

###4.Questionnaires

- contains questionnaire data (IPQ, SSQ, NASA TLX and participant information) for each participant

###5.Scripts

- Physiological_DataPreprocessing
	contains the code (python scripts) used for preprocessing the acquired raw data.
- Unity_RCQoEA
	contains the Unity scripts used for the experiment

###6.Stimuli

- contains the videos (mp4 format) used in the experiment


## **Dataset Description**

The RCQoEA-360VR Dataset Description.pdf introduces the dataset description and key steps in the stage of data acquisition and pre-processing.

## **Dataset License**

RCQoEA-360VR dataset is licensed under a Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0) license.

## **Usage**

We have performed the time alignment of physiological data and videos for each participant. Researchers can use the raw data or processed data for the analysis (using AI techniques) of continuous QoE annotation or post-viewing QoE data using physiological or behavioral data.