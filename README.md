# image dimension ordering

|  | C: RGB | C: BGR |
| :---: | :---: |:---: |
|(N)HWC | TensorFlow, Matplotlib | OpenCV    |
|(N)CHW | PyTorch | Caffe |
|   WHC | Pillow | |

- N: Batch Size
- H: Height
- W: Width
- C: Channel/Color/Depth (R: Red, G: Green, B: Blue)
