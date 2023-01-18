## Pneumonia Detection from Chest X-Ray Images using Transfer Learning                                             

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
Scripts       : <a href=https://anjanatiha.wixsite.com/website>Anjana Tiha's Portfolio</a>
</pre>

#### Dataset
<pre>
Dataset Name     : Chest X-Ray Images (Pneumonia)
Dataset Link     : <a href=https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia>Chest X-Ray Images (Pneumonia) Dataset (Kaggle)</a>
                 : <a href=https://data.mendeley.com/datasets/rscbjbr9sj/2>Chest X-Ray Images (Pneumonia) Dataset (Original Dataset)</a>
Original Paper   : <a href=https://www.cell.com/cell/fulltext/S0092-8674(18)30154-5>Identifying Medical Diagnoses and Treatable Diseases by Image-Based Deep Learning</a>
                   (Daniel S. Kermany, Michael Goldbaum, Wenjia Cai, M. Anthony Lewis, Huimin Xia, Kang Zhang)
                   https://www.cell.com/cell/fulltext/S0092-8674(18)30154-5
</pre>

<pre>
<b>Dataset Details</b>
Dataset Name            : Chest X-Ray Images (Pneumonia)
Number of Class         : 2
Number/Size of Images   : Total      : 5856 (1.15 Gigabyte (GB))
                          Training   : 5216 (1.07 Gigabyte (GB))
                          Validation : 320  (42.8 Megabyte (MB))
                          Testing    : 320  (35.4 Megabyte (MB))

<b>Model Parameters</b>
Machine Learning Library: PyTorch
Base Model              : efficientnet_b0 && Custom Deep Convolutional Neural Network
Optimizers              : Adam
Loss Function           : CrossEntropyLoss

<b>For Custom Deep Convolutional Neural Network : </b>
<b>Training Parameters</b>
Batch Size              : 64
Number of Epochs        : 10
Training Time           : 13 seconds

<b>Output (Prediction/ Recognition / Classification Metrics)</b>
<b>Testing</b>
Accuracy (F-1) Score    : 89.53%
Loss                    : 0.41
Precision               : 88.37%
Recall (Pneumonia)      : 95.48% (For positive class)
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
