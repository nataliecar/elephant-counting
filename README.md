# elephant-counting

Contents:

.ipynb_checkpoints: Contains the notebooks for the initial data exploration and a template for using YOLO through PyTorch (didn't end up using).

AED: Contains the initial csv files and data description from the Aerial Elephant Dataset.

bbox_maker: Contains the notebook for the general bounding box maker (creates 25x25 bounding boxes), and a sample input and output for it (csv and images).

canny_bbox: Contains the notebook for the canny edge detection bounding box creation, and sample output images and the training set csv output.

gsd_resizing_test: Contains the notebook for converting the images to a consistent GSD, and the sample input and output for it (csv and images).

image_splitter: Contains the notebook for splitting the images into 9 subimages and translating the coordinates of the elephants to those subimages.

megadetector_test: Contains the notebook that tried to make use of MegaDetector (our initial experiment that didn't work), and the sample inputs and outputs.

stitching: Contains the notebook that found the images that overlapped and stitched them together, the output csv file for the stitched test set images, and a link to a Google Drive with those images.

yolo_results: Contains the training and testing results from yolov5 including the statistics, weights, graphs, and sample detections. This was done both on the split images and unsplit images. With the split images, we also have sample detections for the stitched images.

yolov5_setup: Contains the notebook that converts the elephant position to the YOLO bounding box format and outputs the labels, and it contains the YAML files used for YOLO.
