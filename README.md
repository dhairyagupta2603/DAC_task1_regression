**20BRS1077**
# Problem Statement 
Can you use your regression skills to predict the age of a possum, its head length, whether it is male or female? This classic practice regression dataset comes originally from the DAAG R package (datasets used in examples and exercises in the book Maindonald, J.H. and Braun, W.J. (2003, 2007, 2010) "Data Analysis and Graphics Using R"). This dataset is also used in the OpenIntro Statistics book chapter 8 Introduction to linear regression.
<br>
The possum data frame consists of nine morphometric measurements on each of 104 mountain brushtail possums, trapped at seven sites from Southern Victoria to central Queensland.

## Dataset

The dataset used is the [Name of the Dataset](Download link) from (source of download e.g Kaggle). If the task is a classification task, then you must specify the number of classes and give a 1 line description of each class as follows(example of Iris Dataset). 

The class labels are:
<br>

**1. Case:** Observation number
<br>
**2. Site:** The site number where the possum was trapped
<br>
**3. Pop:** Population, either Vic (Victoria) or other (New South Wales or Queensland)
<br>
**4. Sex:** either m (male) or f (female)
<br>
**5. Age:** Age of possum
<br>
**6. Hdlngth:** Head length
<br>
**7. Skullw:** Skull width in mm
<br>
**8. Totlngth:** Total length in cm
<br>
**9. Tail:** Tail length in cm
<br>
**10. Footlgth:** Foot length
<br>
**11. earconch:** ear conch length
<br>
**12. Eye:** Distance from medial canthus to lateral canthus of right eye
<br>
**13. Chest:** Chest girth in cm
<br>
**14. Belly:** Belly girth in cm

**Target Variables: -**
<br>
<ul>
    <li>Can we use total length to predict a possum's head length?</li>
    <li>Which possum body dimensions are most correlated with age and sex?</li>
    <li>Can we classify a possum's sex by its body dimensions and location?</li>
    <li>Can we predict a possum's trapping location from its body dimensions?</li>
</ul>

## Model(s) Used

This needs to be a description of the model used and a brief overview of how it works in theory (e.g taken of a CNN Model): 

The network architecture used was a basic CNN model, with Max Pooling and ReLU Activation functions. Input images are resized to an optimal size and then fed into the **Convolutional layer**. These images are converted to their pixel values, which can be imagined as a three-dimensional matrix for the purpose of visualization. The **Convolutional layer** has a kernel. This kernel is generally a small matrix of specified kernel size mxnx3 (3 for RGB images). 
<br>

**Rectified Linear Unit (ReLU)** is the activation layer used in CNNs.The activation function is applied to increase non-linearity in the CNN. Images are made of different objects that are not linear to each other.


**Max Pooling:** A limitation of the feature map output of Convolutional Layers is that they record the precise position of features in the input. This means that small movements in the position of the feature in the input image will result in a different feature map. This can happen with re-cropping, rotation, shifting, and other minor changes to the input image. A common approach to addressing this problem from signal processing is called down sampling. This is where a lower resolution version of an input signal is created that still contains the large or important structural elements, without the fine detail that may not be as useful to the task.

## Future Work
Good ideas or strategies that you were not able to implement which you think can help  improve performance.