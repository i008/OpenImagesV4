# OpenImagesV4 Bounding Box Subset. 

#### Download the *small* OpenImagesV4 dataset

This is a reduced version of the original 500gb dataset. In the small version i sampled 5000 train images and 500 train/val images.
This should be a handy drop-in replacement to create a dev environment and test stuff out.

Download Small OpenImagesV4 (2GB):
https://drive.google.com/file/d/14nukC03LSp37Qw8XOAdNOsJNJ_Px2fb2/view?usp=sharing

The naming is unchanged as here: 
https://storage.googleapis.com/openimages/web/download.html


```bash
~tree --filelimit=10 small_openimages/
small_openimages/
├── bbox
│   ├── test-annotations-bbox.csv
│   ├── train-annotations-bbox.csv
│   └── validation-annotations-bbox.csv
├── challenge2018
├── class-descriptions-boxable.csv
├── imageIds
│   ├── test-images-with-rotation.csv
│   ├── train-images-boxable-with-rotation.csv
│   └── validation-images-with-rotation.csv
├── image-labels
│   ├── test-annotations-human-imagelabels-boxable.csv
│   ├── train-annotations-human-imagelabels-boxable.csv
│   └── validation-annotations-human-imagelabels-boxable.csv
├── test [499 entries exceeds filelimit, not opening dir]
├── train [4951 entries exceeds filelimit, not opening dir]
└── validation [490 entries exceeds filelimit, not opening dir]

```

Be aware that is is a random sample so it might happen that it does not reflect the original dataset distribition. And it might not contain all the labels!

#### Use the notebook to customize what you need. Different sampling? just downloading the label files? checkout the notebook


