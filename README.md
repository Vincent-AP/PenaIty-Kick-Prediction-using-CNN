# PenaIty-Kick-Prediction-using-CNN
This project focuses on predicting the direction of a football penalty kick—left or right—using computer vision and deep learning. The system analyzes image frames extracted from penalty kick videos and learns visual cues from the kicker’s body posture.

Two different approaches are implemented and compared:

- Raw image-based CNN approach

- CNN combined with YOLO Pose Estimation

The goal is to evaluate whether incorporating pose estimation improves prediction performance compared to using raw images alone.


Project Workflow :

1.Data collection from penalty kick videos

2.Frame extraction and labeling (left / right)

3.Image preprocessing

4.Model training and hyperparameter tuning

5.Model evaluation and comparison


File Description:

Model 1(main).ipynb (CNN using raw image input)

ModelYOLO 1(main).ipynb (CNN with YOLO pose estimation preprocessing)
