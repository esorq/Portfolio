## Pneumonia Detection from Chest X-Ray Images using Transfer Learning                                             

[Check out the code](
Efficient_Pneumonia_Detection_in_Chest_Xray_Images_Using_Deep_Transfer_Learning
.ipynb)

<pre>
Domain             : Computer Vision, Machine Learning
Sub-Domain         : Deep Learning, Image Classification
</pre>

### Description
<pre>
1. Detected Pneumonia from Chest X-Ray images using Custom Deep Convololutional Neural Network and by retraining pretrained model “efficientnet_b0” with 169 images of X-ray.
2. For retraining freezed base layers and changed output classes to Pneumonia and Normal.
3. With retrained model was testing accuracy 92.45% and loss 0.2876 attained.
</pre>

#### Code
<pre>
Colab         : <a href=https://github.com/esorq/ml-portfolio/edit/main/projects/classification/Efficient_Pneumonia_Detection_in_Chest_Xray_Images_Using_Deep_Transfer_Learning/Efficient_Pneumonia_Detection_in_Chest_Xray_Images_Using_Deep_Transfer_Learning.ipynb>Efficient_Pneumonia_Detection_in_Chest_Xray_Images_Using_Deep_Transfer_Learning</a>
Scripts       : <a href=https://github.com/esorq/ml-portfolio/tree/main/scripts>Scripts used in the Google colab notebook</a>
</pre>

#### Dataset
<pre>
Dataset Name     : Chest X-Ray Images (Pneumonia)
Dataset Link     : <a href=https://app.roboflow.com/erik-sorqvist/pneumonia-tzsk8/2>Chest X-Ray Images (Pneumonia) Dataset (subset from Kaggle)</a>
                 : <a href=https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia>Chest X-Ray Images (Pneumonia) Dataset (Kaggle)</a>
Original Paper   : <a href=https://www.cell.com/cell/fulltext/S0092-8674(18)30154-5>Identifying Medical Diagnoses and Treatable Diseases by Image-Based Deep Learning</a>
                   (Daniel S. Kermany, Michael Goldbaum, Wenjia Cai, M. Anthony Lewis, Huimin Xia, Kang Zhang)
                   https://www.cell.com/cell/fulltext/S0092-8674(18)30154-5
</pre>

<pre>
<b>Dataset Details</b>
Dataset Name            : Chest X-Ray Images (Pneumonia)
Number of Class         : 2
Number/Size of Images   : Total      : 219 
                          Training   : 169 
                          Testing    : 50 

<b>Model Parameters</b>
Machine Learning Library: PyTorch
Base Model              : efficientnet_b0 
Optimizers              : Adam
Loss Function           : CrossEntropyLoss

<b>For Custom Deep Convolutional Neural Network : </b>
<b>Training Parameters</b>
Batch Size              : 8
Number of Epochs        : 10
Training Time           : 31 seconds, on Tesla P-100 GPU

<b>Output (Prediction/ Recognition / Classification Metrics)</b>
<b>Testing</b>
Accuracy (F-1) Score    : 92.86%
Loss                    : 0.25
Precision               : 78.95%
Recall (Pneumonia)      : 100% 
<!--Specificity             : -->
</pre>

##### Sample Output: 
<kbd>
<img src=https://github.com/anjanatiha/Detection-of-Pneumonia-from-Chest-X-Ray-Images/blob/master/demo/sample/sample.png>
</kbd>

<kbd>
<a href=https://github.com/anjanatiha/Detection-of-Pneumonia-from-Chest-X-Ray-Images/blob/master/demo/images/result.png>See More Images</a>
</kbd>


##### Confusion Matrix: 
<kbd>
![cm1](https://user-images.githubusercontent.com/75247240/213099840-16cc1667-5910-400d-8990-b1862565e71d.JPG)
</kbd>
![cm1](https://user-images.githubusercontent.com/75247240/213105319-445b9e6c-1399-463b-9226-14a94c47a167.JPG)

![alt text](https://user-images.githubusercontent.com/75247240/213105319-445b9e6c-1399-463b-9226-14a94c47a167.JPG)

#### Tools / Libraries
<pre>
Languages               : Python
Tools/IDE               : Anaconda
Libraries               : PyTorch, Numpy, PIL
</pre>

#### Dates
<pre>
Duration                : October 2021 - Current
</pre>
