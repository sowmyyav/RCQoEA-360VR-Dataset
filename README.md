**# RCQoEA-360VR-Dataset: Real-time, Continuous QoE scores for HMD-based 360° VR (RCQoEA 360VR) Dataset**

The RCQoEA-360VR dataset is a novel multi-modal dataset designed for continuous QoE evaluation in virtual reality (VR) environments. In a controlled study (N=32), participants watched five selected 360° video sequences across eight different video quality configurations (from the VQEG database) using a Vive Pro Eye while providing continuous QoE annotations via a touchpad-based input method, enhanced by the DotMorph peripheral visualisation technique.The dataset also includes synchronised physiological signals
(electrocardiogram and galvanic skin response), behavioural data (eye and head movements) and post-viewing QoE ratings gathered through a within-VR interface. RCQoEA-360VR addresses a critical gap in existing public datasets by providing a fine-grained, synchronised multimodal data for immersive QoE analysis. It offers a unique and valuable resource for the research community, supporting a wide range of research applications, including QoE prediction, behavioural modelling, adaptive streaming, and implicit perceptual analysis.

**## Dataset Structure**

The RCQoEA-360VR folder contains the following six subfolders

    1.Behavioral_Data
    2.Physiological_Data
    3.QoE_Annotation_Data
    4.Questionnaires
    5.Scripts
    6.Stimuli

The following is a detailed description of each sub-file:

1.Behavioral_Data

- Raw_EM_Data
	contains the raw eye movement captured from each participant
- Raw_HM_Data
	contains the raw head movement captured from each participant

2.Physiological_Data

- ECG
	contains the raw and processed ECG data captured from Polar H10 chest belt for each participant
- GSR
	contains the raw and processed GSR data captured from Shimmer GSR device for each participant

3.QoE_Annotation_Data

- Continuous_QoE_Score
	contains the continuous QoE annotation data captured from the touch-pad for each participant
- Post_Video_QoE_Score
	contains the post-video QoE scores captured within-VR interface for each participant

4.Questionnaires

- contains questionnaire data for each participant

5.Scripts

- Physiological_DataPreprocessing
	contains the code (python scripts) used for preprocessing the acquired raw data.
- Unity_RCQoEA
	contains the Unity scripts used for the experiment

6.Stimuli
    contains the videos (mp4 format) used in the experiment

## **Dataset Description**

The RCQoEA-360VR Dataset Description.pdf introduces the dataset description and key steps in the stage of data acquisition and pre-processing.

**## Dataset License**

RCQoEA-360VR dataset is licensed under a Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0) license.

**## Usage**

We have performed the time alignment of physiological data and videos for each participant, as well as the processing scripts that can be used to generate both the transformed and frame data.
Researchers can run their analysis methods on them.

For researchers who want to try other data processing methods, you can directly use the raw data.