# Image-Segmentation
Biomedical Image Segmentation using Unet with PyTorch. This is an in-class assignment for CMPT 732 G200 at SFU. 

## Introduction

The image segmentation task has been a challenge as a result of the it being a problem of pixel space. Various methods have been tried for performing it on an image level with quite slow results or not so satifying results.

Image segmentation can be of two types:
1. Semantic Segmentation
: We try to segment images using a pixel mask.

2. Instance Segmentation
: It's a level further ahead of instance segmentation. Here we try to count the number of instances of each object that we segmented. For example, semantic segmentation might tell us, where each objects are located in an image- people, dog, cars etc. But instance will tell us about how many of each kind is there or will put a label on all of them separately.

We are choosing to implement semantic segmentaiong for this classification to single out cells present in this images. 

> For implementation details please read the report.
