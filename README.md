# Brain-Tumor-Segmentation
This notebook builds end-to-end image classifier and image segmentation models using TensorFlow 2.0.

**1. Problem:**
Identifying from the MRI scans whether the brain tumor exists or not. And if the tumor is present, locate and segment the tumor accurately.

**2. Data:**
We are using the TCGA (The Cancer Genome Atlas Program) dataset downloaded from The Cancer Imaging Archive website.

**3. Evaluation:**
* Our goal is to beat the scores of current research papers on Brain Tumor segmentation from MRI scans.
* In 2021, Lucas Fidon, Sebastien Ourselin, and Thomas Vercauteren used the nnUNet architecture-based model which had achieved an accuracy of 92% on the segmentation of the Brain Tumor.
* So, our model needs to score more than 92% accuracy.
* We are using Tversky accuracy and loss as our evaluation metrics.

**4. Features:**
Some information about the data:
* We're dealing with images (unstructured data), so it's probably best we use deep learning/transfer learning.
* There are 3929 MRI scan images of patients, out of which 2556 of them have tumors and 1373 patients have no tumors.
* We have split 85% of the data for training and 15% of the data for testing.

**5. Conclusion:**
Our segmentation model has scored an accuracy of 90.41% on the validation data.
