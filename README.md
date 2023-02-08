# Cervical Cell Cancer Classification
The primary purpose of this project is to design and implement a custom visual transformer
(ViT) for medical imaging applications. Since their debut to machine learning in 2017 with the paper
"Attention is All You Need", Transformers have quickly become the dominant deep learning architecture in
data science [1]. They saw initial success as unparalleled text generators and eventually were redeveloped
to work with computer vision in 2021 with a new paper "An Image is Worth 16x16 Words: Transformers
for Image Recognition at Scale" [2]. Now all of the top state-of-the-art models for the benchmark computer
vision dataset ImageNet are either ViTs or Transformer-Hybrids [3]. The goal of this research is to utilize
the developed visual transformer to classify images of cervical cells to classify and assist in diagnosing
of cervical cancer. The data set consists of images that have been previously categorized into medically
significant classifications. Using these provided classifications, the developed transformer will be able to
sort these images into their respective categories. This project will have implications on the usability of
machine learning in a medical environment, specifically in aiding diagnosis of cell screenings in the medical
environment Specifically, the results of this project aim to provide an outlook on how transformers can
be applied to revolutionize cell screening and imaging in the medical field with specific concentration on
cervical cancer cells. (Sources in project paper)

## Files:
CS540_Project_Group5.pdf - Original project paper with results.  
Vision_Transformer.ipynb - The original proposed vision transformer, assembled with assistance from professor Dr Prashant Shekhar  
16x16_ViT.ipynb - The original proposed vision transformer (set to use CIFAR10 dataset).  
16x16_ViT_Cervical_Cancer.ipynb - Cervical Cancer classification performed on vanilla ViT as control.  
Compact_ViT.ipynb - Vanilla ViT but with sequence pooling instead of class embedding (set to use CIFAR10 dataset).  
CCT.ipynb - Further compaction by introducing convolutional layer over patching (set to use CIFAR10 dataset).  
Dataset_Prep.ipynb - Custom dataset loader for Cervical Cancer Cells.  
CCT_Cervical_Cancer.ipynb - Our actual research program, CCT with the custom dataset.  
CCT_Cervical_Cancer_wGAN.ipynb - Same as previous file but also includes code to mix in generated cervical cancer cells.  
GAN_V3_Cells.ipynb - GAN trained to generate new cervical cancer cell samples and measure their similarity to true samples.  
