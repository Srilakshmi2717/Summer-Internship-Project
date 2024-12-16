**Semantic segmentation of aerial satellite imagery**

Semantic segmentation of aerial satellite imagery is a 
critical task in geospatial applications, including urban planning, 
environmental monitoring, and disaster management. This project 
presents the implementation and evaluation of four advanced deep 
learning models—U-Net, E-Net, DeepLabV3+, and Attention U
Net—on high-resolution satellite imagery of Dubai, obtained from 
MBRSC satellites. The dataset includes pixel-wise annotations 
across six classes: Building, Land (unpaved area), Road, 
Vegetation, Water, and Unlabeled. 

Each model was implemented with tailored preprocessing 
techniques, including resizing, normalization, and one-hot 
encoding, ensuring efficient training and testing. The U-Net 
model employs a symmetric encoder-decoder structure, while E
Net is a lightweight model optimized for real-time segmentation. 
DeepLabV3+ leverages atrous convolution and spatial pyramid 
pooling to capture multi-scale features, and Attention U-Net 
enhances spatial focus through attention mechanisms. 
Performance evaluation was conducted using Intersection-over
Union (IoU) and class-wise IoU metrics. 

Experimental results highlight the comparative strengths and 
limitations of these models in accurately segmenting land cover 
classes. The findings underscore the applicability of deep learning 
techniques for semantic segmentation in geospatial contexts, with 
a particular emphasis on balancing accuracy and computational 
efficiency. Future work will involve fine-tuning models for larger 
datasets, improving real-time inference, and integrating advanced 
post-processing techniques to enhance segmentation accuracy 
further. 
