# Bosch_AI_hackathon_07Jun2021
Submission of TEAM "M-Art" towards Bosch AI hackathon in Techgig Code Gladiators 2021

It is a custom object detection model trained for identifying furnitures, doors, cables and cloths.

For this, pre-trained [YOLOV5](https://github.com/ultralytics/yolov5) s6 and m6 models were trained separately on [1995 images](https://github.com/DarkShadow-web/Bosch_AI_hackathon_2021/releases/download/v1.0/Team_M-Art_Bosch_AI_hackathon_round2_dataset.zip) including labelled, augmented and background images.

The two resultant models, [S6_B32_E61](https://github.com/DarkShadow-web/Bosch_AI_hackathon_2021/releases/download/v1.0/S6_B32_E61.pt) and [M6_B20_E61](https://github.com/DarkShadow-web/Bosch_AI_hackathon_2021/releases/download/v1.0/M6_B20_E61.pt), are ensembled to detect the objects.


