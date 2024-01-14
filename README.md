# Fusion Network for Multimodal Hate Speech Detection


`The paper has been accepted for presentation at the 9th International Conference on Intelligent Information Technology (ICIIT 2024) in 2024.`


## Abstract

In an era where social network platforms are increasingly plagued by harmful content, effective detection methods are crucial for maintaining healthy online communities. In this paper, we introduce a multimodal approach to hate speech detection, leveraging a fusion network that integrates text and image analysis. We mainly use state-of-the-art pre-trained language models like DistilBERT, MPNet, and image processing models such as ResNet and EfficientNetV2. These models facilitate a nuanced understanding of both intra- and inter-modality content dynamics. Additionally, we compare the effectiveness of context-free word embedding models like GloVe and fastText with contextual language models. Extensive experiments on the MMHS150K dataset, a popular and specialized dataset for multimodal hate speech analysis, demonstrate competitive performance compared with existing multimodal hate speech detection methods.


## Dataset

The proposed model is evaluated using the [MMHS150K](https://gombru.github.io/2019/10/09/MMHS/) dataset, a manually annotated multimodal hate speech dataset consisting of 150,000 tweets. Each tweet contains both text and an image. It is noted that some instances in the dataset include `image_text`, which refers to text within an image, extracted using OCR techniques.

Download the MMHS150K dataset:

 - Original dataset ([Direct Link](http://datasets.cvc.uab.es/MMHS150K/MMHS150K.zip) | [Google Drive](https://drive.google.com/file/d/1S9mMhZFkntNnYdO-1dZXwF_8XIiFcmlF/view?usp=sharing))
 - For the preprocessed dataset used in the paper, please send me an email at dhp@DeepLearning.com.vn.


## Source Code

The source code and pre-trained hate speech detection models associated with the paper will be available soon.


## Authors

 1. Phuc H. Duong (Corresponding author) / Email: duonghuuphuc@tdtu.edu.vn / Artificial Intelligence Laboratory, Faculty of Information Technology, Ton Duc Thang University, Ho Chi Minh City, Vietnam
 2. Truc T. Nguyen / Email: nguyenthanhtruc@tdtu.edu.vn / Center for Applied Information Technology, Ton Duc Thang University, Ho Chi Minh City, Vietnam
 3. Hien T. Nguyen / Email: hiennt.mis@buh.edu.vn / Department of Economic Mathematics, Banking University of Ho Chi Minh City, Ho Chi Minh City, Vietnam