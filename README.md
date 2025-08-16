## Overview
Developed a facial recogniton model using openly available pictures from the web to train a model to classify images.
The project is a facial recognition model that can recognize human emotion in pictures.

## Languages/Frameworks/Tools
- **Python**: Primary language for scripting, data processing, and model development.
- **Jupyter Notebook**: Interactive environment enabling rapid prototyping and visualization.
- **TensorFlow**
  - Used for deep learning model construction and GPU-accelerated computation.
  - `tf.keras.utils.image_dataset_from_directory` is leveraged for efficient image data ingestion and preprocessing.
  - GPU memory management via TensorFlow configuration APIs.  
- **Keras**
  - High-level neural network API (integrated with TensorFlow).
  - Used for streamlined model architecture and training workflows.
- **OpenCV**
  - Utilized for low-level image reading and verification.
  - Provides robust image manipulation operations critical for data cleaning.
- **Matplotlib**
  - Visualization of image batches and dataset inspection.
  - Facilitates exploratory data analysis through graphical output.
- **NumPy**
  - Underpins array manipulation, batch processing, and numerical operations.
- **imghdr**
  - Python standard library for image file format validation.

## Dependencies
```bash
pip install opencv-python tensorflow
```

## Acknowledgement
Many thanks to Nicholas Renotte for his guidance on the project!
