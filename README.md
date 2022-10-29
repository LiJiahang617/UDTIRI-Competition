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

1.	Register at the UDTIRI submission system and obtain the submission ID.()
2.	Download the dataset from (https://www.kaggle.com/datasets/jiahangli617/udtiri)
3.	Submit the pre-trained model, source code, and a docker image to the UDTIRI submission system (by simply adding an attachment to the registration) for evaluation.
4.	If UDTIRI submission system is not available, please send the share link of your result to 2230745@tongji.edu.cn
5.  Registration deadline：2022.10.25
6.  Model submission deadline：2022.11.28
7.  Result announcement：2022.11.30

VII. Contact

  2230745@tongji.edu.cn


十一相关通告：
嗨大家好，我们是同济大学RAIl实验室。本次竞赛预估开启的时间会是10月底，整个11月是比赛的时间，我们会在11月底对提交上的模型等性能进行最终评估，划分各类奖项归属。大家现在可以不用着急，先搜集相关资料与整理idea即可，后续通知会继续在这个仓库中进行，祝大家十一国庆快乐鸭！！！
10.1 Relevant notices:

Hi, everyone. We are the RAIl Laboratory of Tongji University. It is estimated that the opening time of this competition will be the end of October, and the whole November will be the time of the competition. We will make a final assessment of the performance of the models submitted at the end of November, and classify various awards. You can not worry now, just collect relevant information and sort out the idea, and the follow-up notification will continue in this warehouse. I wish you a happy National Day!!!


10月15日更新：
这段时间一直比较忙，导致更新消息缓慢，希望各位参赛选手见谅！
根据之前公众号的推文，再次重申一下。本次比赛的报名时间就在10月25日之前，并且在之后的11月进行模型的训练与提交，大家可以先构思算法与模型搭建。我们预计在11月15号之前收集模型以及结果。具体提交要求以及内容后续还会有有通知，大家安心准备模型即可。祝大家好运！
                                                                                 Tongji RAIL
Updated on October 15:

We have been busy for a long time, which has led to slow update of information. I hope you will forgive us!

Once again, according to the previous official account tweets. The registration time for this competition is before October 25, and the model training and submission will be carried out in the following November. You can first conceive the algorithm and model building. We expect to collect the model and results before November 15. The specific submission requirements and content will be notified later, so you can prepare the model with ease. Good luck to everyone!
                                                                                 Tongji RAIL

10.26日更新：
今天开始比赛的报名就截至啦，现在各位参赛选手想必已经得知了本次比赛的内容（详见公众号推文），各位同学可以在Kaggle上面下载我们发布的UDTIRI (https://www.kaggle.com/datasets/jiahangli617/udtiri) 数据集（只有Train和Val部分）。请大家利用该数据集以实例分割为任务进行训练。大家可以尽情创新算法或者进行魔改，使其性能更加强大。结果与模型的提交时间应该在11月中旬左右，大家不必着急，先进行网络设计，到时候会有新的通知。最终评判性能指标（提交模型时应提交）相关docker镜像和测试脚本，具体细节11月中旬会有新的推送，如有疑问，请联系这个邮箱：2230745@tongji.edu.cn
注：目前已发送报名信息到该邮箱的同学即视为报名成功，不需要注册ID，谢谢大家理解。
                                                                                                                同济RAIL实验室MIAS group
                                                                                                                
Updated on October 26:

The registration for today's competition is up. Now you must have known the content of this competition (see official account tweets for details). You can download the UDTIRI (https://www.kaggle.com/datasets/jiahangli617/udtiri) dataset we released (only Train and Val) on Kaggle. Please use this dataset to divide examples into tasks for training. You can innovate algorithms or make magic changes to make their performance more powerful. The results and models should be submitted in the middle of November. You don't need to worry. You should first design the network, and then there will be a new notice. The final evaluation of performance indicators (which should be submitted when the model is submitted) is related to Docker images and test scripts. Specific details will be pushed in mid November. If you have any questions, please contact this email: 2230745@tongji.edu.cn

Note: At present, students who have sent registration information to the mailbox will be deemed as successful, and no registration ID is required. Thank you for your understanding.                                                                                                             
                                                                                 Tongji RAIL
