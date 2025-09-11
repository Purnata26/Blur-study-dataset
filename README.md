Cybersickness Dataset with Real-Time Reduction Techniques
Overview
This dataset, derived from a study on cybersickness in virtual reality (VR), is designed to facilitate research into real-time visual comfort strategies. It contains multimodal data collected from participants during a VR roller coaster simulation under three different visual conditions: no blur, static maximum blur, and real-time dynamic blur.

Participants:
A total of 38 participants (21 male, 17 female) took part in the study. The ages ranged from 18 to 59 years, with a mean age of 26.3 (SD=7.2). Participants were recruited from two universities and included students and general public.

Demographics:

Gender: 55.3% Male, 44.7% Female

VR Experience: 44.7% never used VR, 44.7% rarely used VR, 5.3% occasionally, and 5.3% frequently.

Gaming Experience: Average self-reported score of 3.3 (SD=1.4) on a 5-point scale.

Corrective Lenses: 47.4% used corrective lenses (glasses or contacts).

Reported Conditions: 5 participants reported motion sickness, 3 reported frequent headaches or migraines.

Experimental Conditions
Participants experienced three counterbalanced VR conditions in a roller coaster simulation. Each session lasted approximately 7 minutes.

Condition A (No Blur): The VR simulation ran with blur intensity set to 0.

Condition B (Dynamic Blur): The blur intensity dynamically changed based on the participant's self-reported Fast Motion Sickness (FMS) score, using a linear mapping (e.g., an FMS score of 7 corresponded to a blur level of 70%).

Condition C (Static Maximum Blur): A fixed maximum blur intensity (100%) was maintained for the entire duration of the session.

Data Collected
The dataset is multimodal, including physiological, behavioral, and subjective data. The data points were collected at a high frequency to capture subtle changes in user response.

Subjective Ratings
Simulator Sickness Questionnaire (SSQ): Administered pre- and post-session to quantify nausea, oculomotor strain, and disorientation.

Fast Motion Sickness Scale (FMS): Self-reported scores were recorded every 30 seconds during the simulation for real-time sickness assessment.

Igroup Presence Questionnaire (IPQ): Completed post-session to evaluate the user's sense of presence in the virtual environment.

Physiological Data
Electrocardiogram (ECG): Captured with a Shimmer3 ECG unit to monitor heart activity.

Galvanic Skin Response (GSR): Measured via a Shimmer GSR unit to track skin conductance, an indicator of autonomic arousal.

Tracking Data
Eye Tracking: From the HP Reverb Omnicept headset, including gaze position (where the user is looking) and pupil dilation.

Head Tracking: From the HP Reverb Omnicept headset, capturing head position and orientation.

Equipment
The study utilized a state-of-the-art VR setup and specialized physiological sensors to ensure high-fidelity data collection.

VR Headset: HP Reverb Omnicept Edition G2

Display: 2160x2160 pixels per eye at a 90 Hz refresh rate.

Built-in features: Integrated eye and head tracking via the HP Omnicept.

Physiological Sensors: Shimmer 3 ECG and GSR




VR Environment: A roller coaster simulation built in Unity 3D, designed to induce motion cues.
Dataset folder: Here is the dataset folder: https://drive.google.com/drive/folders/1wEc2Wi2zSRgReCic_n56OtDfghARNDDK?usp=sharing
Data was collected from 2 different university which is given in 2 folder -Uni 1 data and Uni 2 data. SSQ folder in github has pre and post SSQ for both universities.
Pilot study data is also shared here. The sampling rate for ECG was 512, GSR (128), Eye tracking (120) Hz respectively. The files are labeled with FMS.


