# ColorNet

ColorNet is a neural network model for automatic image colorization. This repository includes a model implemented with Caffe and uses Git LFS to handle large files.

## Repository Contents

- `colorization_deploy_v2.prototxt`: The architecture file for the Caffe model.
- `colorization_release_v2.caffemodel`: Pre-trained model for colorization (tracked with Git LFS).
- `pts_in_hull.npy`: Cluster centers for colorization.
- `main.py`: Script to perform image colorization.

## Features

- **Automatic Image Colorization**: Converts grayscale images to color images using deep learning.
- **Pre-trained Model**: Utilizes a pre-trained Caffe model for high-quality colorization.
- **Cluster Centers for Improved Accuracy**: Incorporates cluster centers to enhance colorization results.
- **Easy to Use**: Simple command-line interface for processing images.


## Output
![original_img](https://github.com/user-attachments/assets/35161188-63a8-4082-9639-16782b35c819)
![colorized_img1](https://github.com/user-attachments/assets/e92bf26c-827a-4a33-a4e6-09b6ac37a2ae)



