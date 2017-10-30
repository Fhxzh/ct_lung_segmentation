# CT Lung Segmentation

This repository contains the codes for lung and airway segmentation from CT scans, used in "Discriminative Localization in CNNs for Weakly-Supervised Segmentation of Pulmonary Nodules", [MICCAI'17](https://arxiv.org/abs/1707.01086).

## Files

* ```demo_ct_lung_segment.ipynb```: demo code to walk through the steps implementated in ```main.py```.
* ```main.py```: main code of the segmentation.
* ```segment_lung.py```: coarse segmentation of lung & airway. 
* ```segment_airway.py```: extraction of airway. 
* ```utils.py```: utility functions.
* ```data```: input sample.
* ```result```: output sample.

***Note***: the sample image is down-sampled from a CT scans in the [LIDC-IDRI](http://doi.org/10.7937/K9/TCIA.2015.LO9QL9SX) dataset.

## Requirements

* numpy
* nibabel
* scipy
* scikit-image

## Usage

```
    $ git clone https://github.com/wanwanbeen/ct_lung_segmentation
    $ cd ct_lung_segmentation
    $ python main.py
```
