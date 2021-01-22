# Steel-Surface-Defect-Detection 
This  project  proposes  an  automatic  recognition  approach that classifies and detects steel surface defects present on the steel plates using advanced deep learning methods.
We trained our model using few layers of EfficientNet B3 and adding few layers by our own  and  finally got a test accuracy of 97%.

## Main Contributions
 - Our Defect Detection system consisting of two parts :  Defect classification, and Instance Segmentation of Surface Defects.
 - For defect inspection on steel plates, the detection task has superior advantages to complicated defects, e.g. multiple defects, multiclass defects and overlapping defects.
 - Designed and trained a CNN framework using EfficientNet-B3 architecure as initial layers and added few layers at bottom, to build an efficient search-heuristics method for feature extraction and representations from raw pixel and segmenting a masks over the defects using Mask R-CNN. 
 


### About Dataset Used


The  high-resolution  steel  surface  defect  dataset  provided by  Severstal  contains  a  large  scale  real-world  industry  steelsurface defect image dataset which has pixel-wise annotation created  by  various  technical  professionals.  The  steel  surface images(256, 1600, 3) contain a total of 14,369 images whichis  of  height  256  px,  the  width  of  1600  px,  and  three  colorchannels(RGB). All the images were classified into defects of four categories or classes.

Dataset Link: [Steel Dataset Link](https://www.kaggle.com/c/severstal-steel-defect-detection/data)


## Methodology of this project
<img src="https://github.com/chiragsamal/Steel-Surface-Defect-Detection/blob/master/Images/methodology.png">
