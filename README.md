# A-machine-learning-approach-to-skin-cancer-classification
This project deals with performance evaluation of machine learning techniques in classifying malignant, benign melanoma and normal mole. Skin tumor is a condition of uncontrolled growth of cells in the skin which may be cancerous. Melanoma is one of the common types of skin cancer. The aim is to develop a standalone application for the diagnosis of skin tumors. 

# Data
Dermoscopic images are obtained from the PH2 database, an authorized and standardized database accepted by many dermatologists all over the world. The images were obtained with the help of the dermoscopy system with a magnification power of 20X. The database contains more than 5000 images of skin tumors which include abnormal naevi, melanomas, common naevi, and benign tumors. We used 1500 images that were collected across three different types of skin tumors including atypical naevus (benign tumors), malignant melanoma, and common naevus (moles). 

# Feature Extraction
We extracted 15 different features including morphological, diagnostic clinical, statistical, and Grey Level Co-occurrence Matrix (GLCM). A complete description of the features and the feature selection processes are available in the published paper. 

Apart from the results published, here, we performed a comprehensive study of the different classification methods and visualized their performance toward finding the optimal classifier for the underlying task. With state-of-art machine learning, we observed that the Bagging classifiers perform exceptionally better than the SVM. 

# Prerequisites:

Python 3.5
Keras 2.2.0
Tensorflow-GPU 1.9.0 
Scikit-Learn

We believe the code would be of good value for the research community and request to kindly cite our study:

#T. R. Thamizhvani, Suganthi Lakshmanan & R. Sivaramakrishnan (2018). Mobile application-based computer-aided diagnosis of skin tumours from dermal images, The Imaging Science Journal, 66:6, 382-391, DOI: 10.1080/13682199.2018.1492682
