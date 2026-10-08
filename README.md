# Pancreas_segmentation
This group project explores how deep learning can identify and segment the pancreas in abdominal CT scans. Using the annotated Pancreas-CT dataset, we prepared the scans and segmentation masks, analysed the imaging data, and compared approaches that process individual 2D slices with models that use the full 3D structure of a scan.

The experiments include 2D U-Net architectures, a 3D U-Net and Swin UNETR. We investigated preprocessing, training strategies and loss functions to address the challenges of segmenting a small organ across scans with varying image characteristics.

For further details refer to "presentation_pancreas_segmentation" file.
