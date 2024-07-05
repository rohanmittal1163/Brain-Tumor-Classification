# Brain-Tumor-Classification
## Members
[Naman Birla](mailto:naman22310@iiitd.ac.in)<br/>
[Mohmmad Ayaan](mailto:ayaan22302@iiitd.ac.in)<br/>

## Introduction 
A brain tumour refers to a discrete accumulation of cells in the brain, classified as benign or malignant, that pose a serious health risk due to their ability to raise intracranial pressure. Importance cannot be. Stated that the importance of early detection and accurate classification of brain tumours is not excessive. This is learned as a process of this compulsive responsibility for the interconnectedness of a cell to be seen by the brain's responsibility, classification, and locality. -taking advantage of the copy, the research process is well structured. Strives to do so, facilitating faster and more accurate clinical interventions to improve patient outcomes.

## Dataset Details
The dataset for the project has been taken from [Kaggle](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset).<br/>
It contains 7023 human brain MRI pictures sorted into 4 classes: glioma, meningioma, no tumour, and pituitary tumours.
The dataset was split into Training (5712 images) and Testing (1311 images).<br/> Out of 5712 Training images, we had 1321 glioma files, 1339 meningioma files, 1595 notumor and 1457 pituitary images as our training data. 

## Analysis
We analysed various models depending on the distribution of our data. The best fit models were Support Vector Machines (with non linear kernels), Random Forests and Convolutional Neural Networks. The in-depth analysis of each model can be found in the  ```Report.pdf```.

## Results
Upon testing the model on the test dataset, we obtained an accuracy of 97.33% using SVM with a rbf (radical base function) kernel followed by 97.02% using SVM with a polynomial kernel. Neural Networks Model worked fairly well on the dataset giving an accuracy of 96.95%.

