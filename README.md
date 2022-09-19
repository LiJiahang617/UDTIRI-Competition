# UDTIRI-Competition
1st UDTIRI Competition instruction 

I．General Information

  Using the popular deep learning methods can achieve more efficient identification and segmentation of defects on urban roads. Because the general road defects are mainly potholes, the main goal of this competition is to separate the potholes from lanes. The participating teams will use the unified road pothole dataset for their instance segmentation algorithm and finally obtain an instance segmentation model with excellent performance indicators. Participants need to submit their pre-trained model and the corresponding Docker image file for the sponsor to evaluate the algorithm (based on speed and accuracy).

II．Datasets

  This competition will use the road pothole dataset collected by the organizer. There are 1000 RGB images total, and the sponsor marks all annotations. All annotations are in JSON format (coco dataset format). The sponsor will provide training sets and validation sets for each team. When evaluating the model finally, the sponsor will use undisclosed test set images for evaluation.

III．Evaluation

  The evaluation method of this competition selects the general mAP indicators in instance segmentation fields, as well as the general performance indicators such as the algorithm FPS value for evaluation, and then carries out a comprehensive ranking.

IV．Rewards

  The total prize of this competition is 2500 dollars! Among the ranking, the first team will get 1000 dollars, the second and third teams will get 600 dollars, the fourth, fifth, and sixth teams will get 500 dollars, and the seventh and tenth teams will get 400 dollars. 

V．Submission Rules

  The model must predict the bounding box and polygon mask of the pothole. If the requirements cannot be met, the organizer has the right to refuse to receive.

VI. Instructions

1.	Register at the UDTIRI submission system and obtain the submission ID.
2.	Download the dataset from ()
3.	Submit the pre-trained model, source code, and a docker image to the UDTIRI submission system (by simply adding an attachment to the registration) for evaluation.
4.	If UDTIRI submission system is not available, please send the share link of your result to 2230745@tongji.edu.cn

VII. Contact

  2230745@tongji.edu.cn
