# Image-Captioning
Automatically describing the content of an image is one of the challenging problems in Deep Learning where a textual description must be generated. It requires methods from computer vision to understand the content of the image and a language model from natural language processing to convert the understanding of the image into words in the correct structure. For this project I have taken Flickr8k dataset which consists of images along with their captions and implemented neural network-based image caption generator in Pytorch. 

# Data
I have used Flickr8k dataset for this project which consists of 8,000 images extracted from Flickr website. For each image, it provides five different sentence annotations. Each annotation is a sentence of around 10-20 words. Adopted the standard separation of training, validation and testing set provided by the dataset. There are 6,000 images for training, 1,000 images for validation and 1,000 images for testing.

Dataload, vocab builder are common files for without and with attention. In case of attention, train.py has evaluate function included in it for testing purpose aswell. 
Test.py gives bleu for the batch level, Sample.py prints predicted caption and shows the input image. (only one sample image can be predicted in a run given the image id. ) 

# Conclusion
I was able to develop an image captioning model and extended the architecture to use attention mechanism and achieved a BLEU-4 score of 13.5. There can be many improvements in this project, and I would like to continue working on it. Overall working on this project has helped me develop more interest in understanding the Deep Learning concepts and I  would like to explore more on this project in future.
