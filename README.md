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

## Contributors
<table>
  <tr>
    <td align="center"><a href="http://chiragsamal.github.io/"><img src="https://avatars.githubusercontent.com/u/52205244?s=400&u=dd85ae5a28a5cceb54d7dcdbda442341efb0ed45&v=4" width="100px;" alt=""/><br /><sub><b>Chirag Samal</b></sub></a><br /><a href="https://github.com/chiragsamal/Steel-Surface-Defect-Detection/commits?author=chiragsamal" title="Code">💻</a> <a href="https://github.com/chiragsamal/Steel-Surface-Defect-Detection/commits?author=chiragsamal" title="Documentation">📖</a> <a href="#maintenance-chiragsamal" title="Maintenance">🚧</a> <a href="#ideas-chiragsamal" title="Ideas, Planning, & Feedback">🤔</a> <a href="#question-th3c0d3br34ker" title="Answering Questions">💬</a></td>
    <td align="center"><a href="https://github.com/prince2312yadav"><img src="https://avatars.githubusercontent.com/u/47516627?s=400&u=0d52fa7f2c3c6b03c6ca4416a75b638ae39fefc2&v=4" width="100px;" alt=""/><br /><sub><b>Prince Yadav</b></sub></a><br /><a href="https://github.com/chiragsamal/Steel-Surface-Defect-Detection/commits?author=prince2312yadav" title="Documentation">📖</a><a href="https://github.com/ashutosh1919/masterPortfolio/commits?author=dineshnadimpalli" title="Code">💻</a> <a href="#question-th3c0d3br34ker" title="Answering Questions">💬</a></td></td>
  </tr>
</table>
