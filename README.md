# PaddleOCR c++ infet 

Build the project using VS2019 and cmake on win10.

## Environment

CUDA:11.3

TensorRT:8.4.0.6

OpenCV:4.8.0

### Run the main.cpp

After downloading the model, modify the model path in main.cpp.

```c++
std::string model_dir = "D:/code/PaddleOCR/model/";
FLAGS_det_model_dir = model_dir + "ch_PP-OCRv4_det_server_infer";
FLAGS_rec_model_dir = model_dir + "ch_PP-OCRv4_rec_server_infer";
// image path
FLAGS_image_dir = "D:/12.jpg";

```



## Acknowledgement

1.[PaddleOCR](https://github.com/PaddlePaddle/PaddleOCR)

