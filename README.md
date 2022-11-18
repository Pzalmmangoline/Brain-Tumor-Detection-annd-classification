# Brain-Tumor-Detection-annd-classification
A brain tumor detection and classification system, that can classify various types of Brain tumors correctly.

This is a collaborative project with Maikyau Israel. An additional development of a streamlit web based application was created, to give the classification models an end user Innterface.

Early detection of brain tumours is critical to enhancing diagnostic accuracy in treatments as well as patient survival. Deep learning algorithms have
emerged as one of the most effective forms of machine learning recently, making it possible to categorise magnetic resonance images of the brain to 
determine particular tumour types under investigation. In this project, a web application was built and implemented to classify brain tumours from MRI 
scans. Combining modern image processing techniques with computer vision and advanced pattern analysis enables the diagnosis of brain tumours with more 
sensitivity, greater specificity, and lower costs than ever before. The MRI brain tumour scans obtained from Kaggle were used to train and validate four 
pre-trained convolutional neural networks; AlexNet, ResNet152, MobileNetV2, and Xception. The hyperparameters of the classifiers were tuned to obtain 
optimal results in terms of accuracy and sensitivity. On the average, the classification accuracy of the networks are AlexNet (64.1%), ResNet152V2 (92.7%), 
MobileNetV2 (91.76%), and Xception (91.5%). The sensitivity, a measure of how well the classifier correctly identified the class of the tumour, ranged from 
0.53 to 0.91, with ResNet152V2 performing best. The optimal classifiers were thus implemented with Python in the web application accordingly. Given the 
shortage of radiologists in places with limited resources, utilising deep learning technology to detect brain malignancies can save time and effort and 
speed up the detection process.
