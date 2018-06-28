# Analysis-of-Image-Segmentation-Methods
### This study consists of a comparative analysis of various image segmentation methods on cytological images

In this study, we implemented various segmentation techniques on cytological images. The segmentation methods are listed below:
1. Thresholding
2. Adaptive Thresholding
3. Otsu Binarization
4. Edge Detection Techniques - Sobel, Prewitt, etc.
5. KMeans clustering based Segmentation
6. Watershed Algorithm

We tried various combinations and achieved best results using thresholding + watershed algorithm.

Then we implemented the whole script using threading techniques in python to imporve the efficiency and included task parallelism.

The cytological dataset is provided by murphy labs and is available on their official [website](http://murphylab.web.cmu.edu/data/).
