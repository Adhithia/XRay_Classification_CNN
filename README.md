## 1. Project Description
In this project, we use a Chest X-Ray dataset and we identify images where an "effusion" is present. This is a classification problem, where we will be dealing with two classes - 'effusion' and 'nofinding'. Here, the latter represents a "normal" X-ray image.
## 2. Data Description
Our data is in the form of grayscale (black and white) images of chest x-rays. You can download the dataset from here: https://www.kaggle.com/shaitender/cxr-dataset
## 3. Process
1. Data Preparation: 
⋅⋅* Made sure all our images are of the same resolution
⋅⋅* Place the images in two different folders - 'effusion' and 'nofinding'. This method will work for any application where you're trying to train using images.
2. Data Pre-Processing: Morphological Operations
⋅⋅* Perform thresholding on the image - converted it from a grey image to a binary image.
⋅⋅* Look at Erosion, Dilation, Opening, Closing.
3. Data Pre-Processing: Normalisation
⋅⋅* Perform normalisation.
⋅⋅* Try different methods of normalisation.
4. Data Pre-Processing: Augmentation
⋅⋅* Perform data augmentation.
⋅⋅* Perform different ways to augment - translation, rotation, scaling, etc.
5. Model Building
⋅⋅* Run ablation experiments
⋅⋅* Overfitting on a smaller version of the training set
⋅⋅* Hyperparameter tuning
⋅⋅* Mode training and evaluation
