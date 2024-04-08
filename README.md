Gated Context Aggregation Network for Image Dehazing and Deraining
=======
![image](imgs/net_arch.png)

This is the implementation of  paper *"Feature attention gated context aggregation network for single image dehazing and its application on unmanned aerial vehicle images"*.

In this paper, we propose a new end-to-end gated context aggregation network GCANet for image dehazing, in which the smoothed dilated convolution is used to avoid the gridding artifacts and a gated subnetwork is applied to fuse the features of different levels. Experiments show that GCANet can obtain much better performance than all the previous state-of-the-art image dehazing methods both qualitatively and quantitatively
![image](imgs/dehaze_visual.png)

We further apply our proposed GCANet to the image deraining task, which also outperforms previous state-of-the-art image deraining methods and demonstrates its generality.
![image](imgs/derain_visual.png)


## Getting Started

This paper is implemented with Pytorch framework.

Demo
----

Directly put all your test images under one directory. Then run:

```bash
python test.py --task [dehaze | derain] --gpu_id [gpu_id] --indir [input directory] --outdir [output directory]
```

For training, please download the training code from <https://drive.google.com/file/d/1T7X1HYztbz6S75vTRNtREgGEOI269KDk/view?usp=sharing>

```

```
Contact
-------

If you find any bugs or have any ideas of optimizing these codes, please contact me via cddlyf [at] gmail [dot] com

