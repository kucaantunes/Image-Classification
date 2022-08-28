# Image-Classification

Source code:

https://drive.google.com/file/d/1CFe3Sg7T26cyqHFm79F99oDC2bU7cZx7/view?usp=sharing


![image](https://user-images.githubusercontent.com/26171557/187052788-d4fdde0d-2812-48db-b9d2-558424871756.png)


![image](https://user-images.githubusercontent.com/26171557/187052792-5c9b1b25-c3bb-4c86-9529-5c8aad035161.png)


![image](https://user-images.githubusercontent.com/26171557/187052794-e97b1bea-a849-407f-9a62-c070b6ca4f93.png)



An application was developed with the VGG-16 architecture using Python, the TensorFlow software library and the Keras framework based on classification to identify in an image based on light gray scale the existence of possible diseases. In order to analyze X-Rays via web was used Flask, allowing doctors to upload the pictures and see if there is a possible disease on the uploaded image. For this application only the diseases Covid-19 for chest X-rays and CT Scans and brain tumor for MRI scans above thorax were considered.
     
Obtaining the datasets for head and chest.
Via Python code, the classification process was implemented with the VGG-16 architecture, which uses convolution layers of 3x3 filter with a stride 1 and a layer of 2x2 filter of stride 2. The output uses a softmax, and the process is based on 16 layers with weights and has approximately 138 million parameters.

The VGG-16 architecture and the process for datasets validation and testing.
A Receiver operating characteristic (ROC) analysis was done to evaluate the performance of the diagnostic tests and the accuracy of the statistical models. The formulas used in the trained Keras models are showed below.
False Positive Rate:

True Positive Rate:

Micro-average Precision:

Macro-average Precision:

The confusion matrix allows to measure the performance of an algorithm in supervised learning and the Receiver Operating Characteristic (ROC) curve shows the level of performance for a classification model taking usually in account the True Positive Rate (TPR) and the False Positive Rate (FPR).
    
 Analysis of the VGG-19 and the Resnet34 architectures for classification. Python Jupyter code to generate the ROC Curve; the Probability Density Function (PDF) and the Confusion Matrix of the classification process used.

	A general web application made mainly with JavaScript and PHP manages the process, allowing to combine the results obtained with the vital signs information and other medical data of the patient with the analysis done for medical images via Deep Learning for specific diseases.
   
 Usage of AI Care by uploading an image and showing the results (possible disease or no disease detected). Code adapted from [67].
