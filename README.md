# Image-Classification
Image classification of sports celebrity This project is an end-to-end data science and machine learning initiative aimed at classifying images of sports personalities. The classification is restricted to the following five individuals: Maria Sharapova Serena Williams Virat Kohli Roger Federer Lionel Messi

OpenCV Haar cascades were used to detect faces and eyes in the images. This helped to focus on the most relevant parts of the images for classification. Wavelet transform was applied to the detected faces and eyes to extract detailed features. This step helped to capture both spatial and frequency information from the images Various models were tested using GridSearchCV to find the best-performing model. Logistic Regression was found to give the best results with a training score of 82.01%. 
![telegram-cloud-photo-size-5-6203985611333943484-y](https://github.com/user-attachments/assets/113aef57-c589-40f6-ba2e-b54192f9bc0e)

The heatmap below shows the results of Logistic Regression on the test data, with an accuracy of 95% on test images. 

![image](https://github.com/user-attachments/assets/82917bdf-8843-40f3-b4fe-5deb98ee2de2)



The trained model was integrated into a Flask server (server folder). The server handles incoming requests from the UI, processes the images, and returns classification results.
