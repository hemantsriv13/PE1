## Introduction

UAV-BD is a dataset for bottle detection on the UAV perspective. It contains 16252 images for training, 4063 images for validation, and 5079 images for testing.

### Annotation

uav-bd
├── train
│   ├── images
│   ├── labels (annotations of VOC format)
├── val
│   ├── images
│   ├── labels (annotations of VOC format)
├── test
│   ├── images
│   ├── labels (annotations of VOC format)
├── annotation
│   ├── coco (annotations of coco format)
│   ├── train (symlink to training images)
│   ├── train (symlink to val images)
│   ├── test (symlink to test images)
