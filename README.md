# Pedestrian detection with DNN
This project contains scripts and programs for pedestrian detection using deep neural networks. The dataset used is currently only Caltech dataset for pedestrians ([Caltech Pedestrian Detection Benchmark](http://www.vision.caltech.edu/Image_Datasets/CaltechPedestrians/)).

## Project Tree:
```
.
+-- data                                        // directory to store datasets
+-- download_and_convert.py                     // script to download and convert Caltech dataset
+-- README.md                                   // readme
```

#### download_and_convert.py
This script downloads and extract Caltech Pedestrian Detection dataset and convert it to a format that is understood by python and OpenCV. OpenCV is used to visualize annotation and labeling.
For easier use afterwards, binary files can be created consisting strings of extracted samples and labels.
###### Parameters: 
1. data_dir   = path to download and store binaries
2. resize     = will resize the collected samples if True
3. display    = displays video sequence on the fly if True
4. MIN_WIDTH  = minimum allowable samples' width
5. MIN_HEIGHT = minimum allowable samples' height
6. P_WIDTH    = resize samples to final width of P_WIDTH
7. P_HEIGHT   = resize samples to final height of P_HEIGHT
8. DEPTH      = specifies number of channels
 
