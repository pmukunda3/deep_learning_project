# Deep Violance Detection

This is a repository for the violence Detection with 3D Convolutional Nets and data acquisition 

Spatiotemporal feature learning using deep 3-dimensional convolution networks (3D ConvNets) trained on a large scale supervised video dataset
 - Used the pre trained weights of sports 1M, fine tuned the model using UCF101 dataset
 - Tested on the Hockey Fight Dataset(96.5% accuracy) and Movies Dataset (98.6% accuracy)

## Important Links

**Papers**
- https://arxiv.org/pdf/1412.0767.pdf

**Code**
- https://github.com/hx173149/C3D-tensorflow
- https://github.com/facebook/C3D

**Action Recognition Datasets**
- http://crcv.ucf.edu/data/UCF101.php
- https://cs.stanford.edu/people/karpathy/deepvideo/

**Violance Dataset Links**
- https://www.openu.ac.il/home/hassner/data/violentflows/
- http://visilab.etsii.uclm.es/personas/oscar/FightDetection/index.html

## Notes

- Network is trained on **train/test split 1** of action recognition split of UCF-101
- [ ] Need to test preprocessing speed difference of extracting frames on the fly vs extracting them before
