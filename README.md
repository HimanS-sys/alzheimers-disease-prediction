# Predicting the Risk of Alzheimer's Disease

This repository contains work done as part of DS-2 course by [Univ.ai](https://www.univ.ai/).</br> 
Our team - Himanshu, Samyak, Manikya

## Project

**App Description** - Ensemble models that predict the severity of Alzheimer's Disease.

<img src="https://github.com/HimanS-sys/alzheimers-disease-prediction/blob/main/assets/images/alz-disease-intro.png">

- Alzheimer’s Disease is the most common disease of dementia.
- Which may involve the decline of memory, communication, and judgment.
- Yet it is hard to diagnose. 

## Data

- The datasets that can be utilized are from the OASIS Brains project.
- The dataset contains references to brain scanning images and the demographic, clinical, and derived brain anatomical information of the participants.
- The datasets is available here: https://www.oasis-brains.org/

- The OASIS Brains Project contains 3 datasets:
  - **OASIS 1**:</br>
    - This set consists of a cross-sectional collection of 416 subjects aged 18 to 96. For each subject, 3 or 4 individual T1-weighted MRI scans obtained in single scan sessions are included.
    - Learn more [here](https://doi.org/10.1162/jocn.2007.19.9.1498).
  - **OASIS 2**:</br>
    - This set consists of a longitudinal collection of 150 subjects aged 60 to 96. Each subject was scanned on two or more visits, separated by at least one year for a total of 373 imaging sessions.
    - Learn more [here](https://doi.org/10.1162/jocn.2009.21407).
  - **Oasis 3**:</br>
    - Participants include 609 cognitively normal adults and 489 individuals at various stages of cognitive decline ranging in age from 42-95yrs.
    - Learn more [here](https://doi.org/10.1101/2019.12.13.19014902). 

## Methodology

### Tree Based Model

- Different models ranging from linear to ensemble-based were used to predict if the given patient had dementia or not.
- Download this [notebook](https://github.com/HimanS-sys/alzheimers-disease-prediction/blob/main/dimentia_pred.ipynb).


### 3D CNN Model on T1-weighted MRI Scans

- 3D CNN model was used on T1 weighted MRI scans of OASIS 2 data.
- download this [notebook](https://github.com/HimanS-sys/alzheimers-disease-prediction/blob/main/Oasis2_Image_Data.ipynb).

## Showcase
- [Presentation slides](https://github.com/HimanS-sys/alzheimers-disease-prediction/blob/main/Presentation/alz_detection.pdf) for more details.
- [Presntation video](https://github.com/HimanS-sys/alzheimers-disease-prediction/blob/main/Presentation/alz_detection.mp4).
