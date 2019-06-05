# Retinal-OCT-optical-coherence-tomography-Images-classification
Contains code for Deep Learning model for Retinal OCT(optical coherence tomography) Images classiﬁcation.

5 layered CNN architecture gives best image classification results.

Objective: 
Given a new OCT image, determine whether the image belongs to which 4 class: CNV, DME, DRUSEN, and NORMAL. We are using CNN for the classiﬁcation model.

Retinal optical coherence tomography (OCT) is an imaging technique used to capture highresolution cross sections of the retinas of living patients. Total 83,484 OCT images are there in the training dataset. Also 1000 OCT images are there in the test dataset. It is an imbalanced dataset. 
Training dataset contains below number of images:
1. CNV = 26315 2. DME = 37205 3. DRUSEN = 11348 4. NORMAL = 8616

Content: The dataset is organized into 2 folders (train, test) and contains subfolders for each image category (NORMAL,CNV,DME,DRUSEN). There are 84,495 X-Ray images (JPEG) and 4 categories (NORMAL,CNV,DME,DRUSEN). Images are labeled as (disease)-(randomized patient ID)-(image number by this patient) and split into 4 directories: CNV, DME, DRUSEN, and NORMAL. 

Acknowledgements 
1. Data: https://data.mendeley.com/datasets/rscbjbr9sj/2
2. Citation: http://www.cell.com/cell/fulltext/S0092-8674(18)30154-5
