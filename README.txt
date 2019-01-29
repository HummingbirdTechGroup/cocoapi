Using repository: https://github.com/waleedka/coco

COCO API - http://cocodataset.org/

COCO is a large image dataset designed for object detection, segmentation, person keypoints detection, stuff segmentation, and caption generation. This package provides Matlab, Python, and Lua APIs that assists in loading, parsing, and visualizing the annotations in COCO. Please visit http://cocodataset.org/ for more information on COCO, including for the data, paper, and tutorials. The exact format of the annotations is also described on the COCO website. The Matlab and Python APIs are complete, the Lua API provides only basic functionality.

For substantially more details on the API please see http://cocodataset.org/#download.

To install:
run "make" under PythonAPI
pycocotools is then installed


### MS COCO Requirements:
To train or test on MS COCO, you'll also need:
* pycocotools (installation instructions above)
* [MS COCO Dataset](http://cocodataset.org/#home)
* Download the 5K [minival](https://dl.dropboxusercontent.com/s/o43o90bna78omob/instances_minival2014.json.zip?dl=0)
  and the 35K [validation-minus-minival](https://dl.dropboxusercontent.com/s/s3tw5zcg7395368/instances_valminusminival2014.json.zip?dl=0)
  subsets. More details in the original [Faster R-CNN implementation](https://github.com/rbgirshick/py-faster-rcnn/blob/master/data/README.md).
* Please download both the COCO images and annotations in order to run the demos and use the API. Both are available on the project website.
    -Please download, unzip, and place the images in: images/
    -Please download and place the annotations in: annotations/
