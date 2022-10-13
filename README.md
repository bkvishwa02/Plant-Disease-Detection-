# Plant-Disease-Detection-
This is our project for Engineering clinics sem-5

LITERATURE SURVEY

Paper [1] presents classification and detection techniques that can be used for plant leaf disease classification. 
Here pre-process is done before feature extraction. RGB images are converted into white and then converted
into grey level image to extract the image of vein from each leaf.
Then basic Morphological functions are applied on the image. Then the image is converted into binary image. 
After that if binary pixel value is 0 its converted to corresponding RGB image value. 
Finally, by using pearson correlation and Dominating feature set and Naïve Bayesian classifier disease is detected.

In paper[2] there are four steps. Out of them the first one is gathering image from several part of the country for training and testing.
Second part is applying Gaussian filter is used to remove all the noise and thresholding is done to get the all green color component. 
K-means clustering is used for segmentation. All RGB images are converted into HSV for extracting feature.

In paper [3] image processing technique are used to detect the citrus leaf disease.
This system includes: Image pre-processing, segmentation of the leaf using K-means clustering to determine the diseased areas, 
feature extraction and classification of disease. 
Uses Gray-Level Co-Occurrence matrix (GLCM) for feature extraction and classification is done using support vector machine (SVM).

REFERENCES:

1.	Dhiman Mondal, Dipak Kumar Kole, Aruna Chakraborty, D. Dutta Majumder Detection and Classification Technique of Yellow Vein Mosaic Virus Disease 
    in Okra Leaf Imagesusing Leaf Vein Extraction and Naive Bayesian Classifier. 
    2015, International Conference on Soft Computing Techniques and Implementations- (ICSCTI) Department of ECE, FET, MRIU, Faridabad, India, 
    Oct 8-10, 2015.
2.  Pranjali B. Padol, Prof. AnjilA.Yadav, "SVM Classifier Based Grape Leaf Disease Detection" 2016 Conference on Advances in Signal Processing(CAPS) 
    Cummins college of Engineering for Women, Pune. June 9-11, 2016.
3.	Detection of leaf diseases and classification using digital image processing2017 International Conference on Innovations in Information,
    Embedded and Communication Systems (ICIIECS)

