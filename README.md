<div align="center">
  <h1>Akeso : Android Depth Estimation SDK In Android With MiDaS</h1>
</div>

The repository contains an Android Library project which uses the [MiDaS](https://github.com/isl-org/MiDaS) model to perform monocular
depth estimation. You can find the official Android example here -> https://github.com/isl-org/MiDaS/tree/master/mobile/android

This Library project uses the TFLite model from the [MiDaS's TensorFlow Hub repo](https://tfhub.dev/intel/midas/v2_1_small/1).
The following steps can helps to integrate this library with your own sample project. You can input your image to this library which use
model to process it and give you a Image Bitmap back.

## Explore the code

We're now going to walk through the most important parts of this library code.