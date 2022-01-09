# Image dimensions cheatsheet for Python packages

|  | C: RGB | C: BGR |
| :---: | :---: |:---: |
|(N)HWC | TensorFlow, Keras, Pillow, Matplotlib, Albumentations | OpenCV, MMCV |
|(N)CHW | PyTorch | Caffe |

- N: Batch Size
- H: Height
- W: Width
- C: Channel/Color/Depth (R: Red, G: Green, B: Blue)

Note: PyTorch's data loader uses Pillow internally.
