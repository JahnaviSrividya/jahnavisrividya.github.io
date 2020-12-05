## A 2D Convolutional Neural Network Approach for Severity Scoring of Lung Tuberculosis using CT Images

**Project description:** Tuberculosis (TB) is an air-borne disease, which affects the lungs and often spreads through sputum. According to the report of World Health Organization 9 million people worldwide are affected by TB. Tuberculosis can be cured easily when diagnosed in its early stage and with accurate CT Analysis.

<img src="images/lung-CT.jpg?raw=true"/>

 As an effort to form a technical forum for effective analysis and diagnosis, ImageCLEF released the Tuberculosis 2019 tasks, each dealing with one aspect of understanding and tackling the disease. We have taken up one sub-task that aims at assessing the severity of the tuberculosis disease as low or high. The task is implemented using a deep neural network approach using 2-D Convolutional Neural Network (CNN) with appropriate preprocessing. The CT volumes are segmented with the provided masks and further pre-processed with the aid of med2image, a python utility to obtain slices of CT scans, prior to training the model. The best run of the proposed CNN model resulted in an accuracy of 0.607 and an AUC of 0.626. The achieved result is placed 9th in the overall leaderboard of the ImageCLEF 2019 Tuberculosis challenge for severity scoring.


For more details see [2D CNN PDF](http://ceur-ws.org/Vol-2380/paper_133.pdf).