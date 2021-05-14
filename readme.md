# object-detection
This repo includes the implemetation of some of the state of the art object detection techniques such as faster-rcnn, mask-rcnn, ssd, yolo v3 and retinanet on subsets of some of the most popular public datasets for object detection task. 
On Datasets folder, you can find notebooks with which you can get specific number of specific classes from OpenImagesV6, Coco, PascalVoc and ImageNet datasets. You can use these subsets to any of the notebooks that implement the above techniques, with only few changes to the appropriate input format for each case, especially to annotation files, e.g. from xml to txt or to csv, or csv to tfrecord, etc. Find more details to notebooks. Two additional notebooks, Scocco_Detector_with_RetinaNet and Real_Time_Sign_Language_Detector_with_SSD_Mobilenet, are included with examples of implementation of retinaNet and sse_mobileNet on custom datasets.
