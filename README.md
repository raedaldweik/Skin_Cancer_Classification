# Skin_Cancer_Classification

## Description:
In this project, I have developed a comprehensive deep learning-based solution for the classification of skin lesions. The primary goal is to distinguish between malignant, precancerous, and benign lesions, a crucial step in aiding early detection and treatment strategies in dermatology.

## Key highlights of the project include:

**Utilization of Advanced Deep Learning Models:** The project leverages several state-of-the-art deep learning architectures, including VGG16, VGG19, Densenet, and InceptionV3. Each of these models brings a unique approach to feature extraction and pattern recognition, essential in the nuanced field of skin lesion analysis.

**Dataset and Preprocessing:** The images used in this project were collected from the International Skin Imaging Collaboration (ISIC)(https://www.isic-archive.com/). The datset consisted of malignant, actinic keratosis (benign, pre-cancerous) and benign(nevus) images to make a total of 4838 images. A 80% training and 20% training split was used with FULL data augmentation techniques to increase overall accuracy and precision of the model.

**Model Training and Evaluation:** To compare the accuracy and computational efficiency of different deep learning models, VGG16, VGG19, InceptionV3 and DenseNet101 were used. Each model had the same data augmentation techniques and were run for 10 epochs.

**Results and Discussion:** **VGG16 Model**: Secured an accuracy of 81.4%, proving its capability in a more complex, multiclass scenario.
**VGG19 Model**: Marginally outperformed VGG16 with an accuracy of 81.9%, reflecting subtle improvements in its classification ability.
**InceptionV3 Model**: Showcased a more notable performance leap, achieving an accuracy of 84.81%, underscoring its advanced feature detection capabilities.
**DenseNet101 Model**: Emerged as the top performer, reaching an accuracy peak of 84.91%, thus setting a high standard for accuracy in this multiclass classification challenge.


The repository aims to contribute to the field of medical image analysis, specifically in dermatology, by providing a detailed exploration of how different deep learning models can be effectively applied to the challenging task of skin lesion classification.
