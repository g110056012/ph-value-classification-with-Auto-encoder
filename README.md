# ph-value-classification-with-Auto-encoder

There are three types of anthocyanin, which are  LPE__calibrated, PFPE__calibrated, Jabuticaba_calibrated. 

STEPS: 
1. Using Mask R-CNN pretrained model to implement object detection task for the bottle object. 
2. We crop the middle part of the bottle which is the liquid part image, and then we crop the image into several 32X32 size pixels(Dataset). 
3. Train Auto-Encoder Model. 
4. Scatter the data to 2-dimention for analysis.
5. Do the classification task and confusion matrix.
6. Compared with PCA and CNN. 



HOW TO RUN THESE CODES:

*File directory must be adjusted to satisfy your route.

(ex:Jabuticaba_calibrated)

1. Go under Forder/Class Jabu
2. Run Jabu_bottle_detect.ipynb
3. Run Jabu_imagecrop.ipynb
4. Run Jabu_experiment_2dim.ipynb
5. Run classifier_cnn.ipynb (Go under Forder/Code)
