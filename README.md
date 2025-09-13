# Cybersickness Dataset with Real-Time Reduction Techniques

## Overview

This dataset is derived from a controlled study on **cybersickness in virtual reality (VR)** environments. It is designed to support research into **real-time visual comfort techniques** by providing multimodal data collected during immersive VR experiences under different visual conditions.

- **Study Focus**: Real-time reduction of cybersickness using dynamic blur techniques.
- **VR Environment**: Roller coaster simulation designed to induce motion-related discomfort.
- **Dataset Access**: [Google Drive Link](https://drive.google.com/drive/folders/1wEc2Wi2zSRgReCic_n56OtDfghARNDDK?usp=sharing)

---

## Participants

- **Total Participants**: 38  
  - 21 Male (55.3%)  
  - 17 Female (44.7%)  
- **Age Range**: 18 – 59 years  
  - Mean Age: 26.3 years (SD = 7.2)
- **Recruitment**: From two universities, including students and members of the general public

### Demographics

- **VR Experience**:  
  - 44.7% Never used  
  - 44.7% Rarely used  
  - 5.3% Occasionally  
  - 5.3% Frequently  

- **Gaming Experience**:  
  - Mean score: 3.3 (SD = 1.4) on a 5-point scale

- **Corrective Lenses**:  
  - 47.4% wore glasses or contacts

- **Reported Conditions**:  
  - 5 participants reported motion sickness  
  - 3 participants reported frequent headaches or migraines

---

## Experimental Conditions

Each participant experienced **three counterbalanced conditions**, each lasting ~7 minutes in a VR roller coaster simulation:

### Condition A - No Blur
- Blur intensity = 0%

### Condition B - Dynamic Blur
- Blur intensity adjusted in real-time based on FMS score  
  - e.g., FMS score of 7 → 70% blur

### Condition C - Static Maximum Blur
- Constant blur at 100% throughout the session

---

## Data Collected

The dataset is **multimodal**, including subjective, physiological, and behavioral data.

### Subjective Measures

- **Simulator Sickness Questionnaire (SSQ)**  
  - Administered pre- and post-session  
  - Measures: nausea, oculomotor strain, disorientation

- **Fast Motion Sickness Scale (FMS)**  
  - Self-reported every 30 seconds during simulation

- **Igroup Presence Questionnaire (IPQ)**  
  - Completed post-session to assess sense of presence

### Physiological Data

| Signal | Device | Sampling Rate |
|--------|--------|----------------|
| ECG (heart activity) | Shimmer3 ECG | 512 Hz |
| GSR (skin conductance) | Shimmer GSR | 128 Hz |

### Tracking Data

| Signal | Source | Sampling Rate |
|--------|--------|----------------|
| Eye and head Tracking | HP Reverb Omnicept | 120 Hz |


Includes:
- Gaze position
- Pupil dilation
- Head orientation and position

---

## Equipment

| Equipment | Details |
|----------|---------|
| VR Headset | HP Reverb Omnicept G2 |
| Display | 2160×2160 pixels per eye @ 90 Hz |
| Built-in Tracking | Eye and head tracking |
| Sensors | Shimmer3 ECG & GSR units |

---

## VR Environment

- Built in **Unity 3D**
- Custom **roller coaster simulation** designed to induce motion cues

---

## Dataset Folder Structure

Data was collected from 2 different university which is given in 2 folder -Uni 1 data and Uni 2 data. SSQ folder in github has pre and post SSQ for both universities.
