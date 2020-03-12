# Multimodality-Weight-and-Score-Fusion-for-SLAM

DATASET - https://drive.google.com/open?id=1vA_dmdMGyekGiB95ec_Eh7QAzcNeAuT_


•	Google Collaboratory GPU runtime environment is used to execute the entire project.


•	Steps to Run:

1.	Upload dataset on Google Drive.
2.	Open any “.ipynb” file give dataset directory path from google drive.
3.	Create three folders under files section on google colab naming datasets, models, utils.
4.	Upload files in each folder as given in code section on github respiratory.
5.	Run all the parts of code to calculate translation and rotation errors and get a trajectory of vehicle.


•	Folder Structure to be created on Google colab:

1.	datasets:
    a.	apolloscape.py
    
2.	utils:
    a.	training.py
    b.	common.py
    
3.	models:
    a.	posent.py is used for ResNet pretrained Feature Extractor.
    b.	posent1.py is used for VGG pretrained Feature Extractor.
    c.	posent2.py is used for AlexNet pretrained Feature Extractor.

