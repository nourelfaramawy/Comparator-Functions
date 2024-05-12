Image Comparator Functions
This repository focuses on implementing and experimenting with commonly used image comparator functions. With a primary aim to provide tools for quality analysis and comparators for loss functions during the learning phase, it explores a variety of methods crucial in image processing and machine learning tasks.

Introduction
Image comparison is fundamental in numerous domains, including computer vision, medical imaging, and remote sensing. Whether assessing image quality or optimizing models, robust comparator functions are indispensable. This repository presents implementations and experiments with key image comparator functions, offering a versatile toolkit for analysis and experimentation.

Features
Quality Analysis Tools: Evaluate image quality using different comparator functions.
Loss Functions for Learning: Utilize comparators as loss functions in machine learning model training.
Experimentation Environment: Easily experiment with various comparator functions and parameters.
Implemented Functions
Pearson Correlation: Measures the linear correlation between two images' pixel intensities.
Root Mean Squared Difference (RMSD): Computes the root mean squared difference between pixel intensities of two images.
SSIM (Structural Similarity Index): Evaluates the similarity between two images considering luminance, contrast, and structure.
Intersection over Union (IoU): Computes the ratio of the intersection area to the union area of two images, commonly used in object detection tasks.
Hausdorff Distance: Measures the dissimilarity between two sets of points, often applied in shape matching and object recognition.
Dice Coefficient: Quantifies the spatial overlap between two images, commonly used in medical image segmentation.
Mean Bias: Computes the average bias between two images' pixel intensities.
Cross Correlation: Measures the similarity between two images by sliding one over the other and calculating the correlation at each position.
