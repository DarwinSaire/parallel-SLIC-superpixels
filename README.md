# parallel-SLIC-superpixels
parallel SLIC-superpixels algorithm. C++, OpenCV, OpenMP, CUDA

| Image                              | SLIC                                                     | Parallel-SLIC                                                |
| ---------------------------------- | -------------------------------------------------------- | ------------------------------------------------------------ |
| <img src="img/suco.jpg" alt="img"> | <img src="img/suco_segmentation.jpg" alt="segmentation"> | <img src="img/test_suco_segmentation.jpg" alt="parallel-segmentation"> |
| <img src="img/dog.png" alt="img">  | <img src="img/dog_segmentation.png" alt="segmentation">  | <img src="img/dog_segmentation_test.png" alt="parallel-segmentation"> |



##### Run the code

Compiler

```c++
pkg-config --cflags opencv` -o test_slic test_slic.cpp slic.cpp `pkg-config --libs opencv
```

Running

```c++
./test_slic dog.png 400 40 dog_segmentation.png
```

