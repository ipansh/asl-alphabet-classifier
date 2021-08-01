# asl-alphabet-classifier
Custom-built CNN model for image classification task of American Sign Language with Keras high-level API.
Accuracy on the test subset: 96.3%.

Three Jupyter notebooks:
1. **Data Pre-Processing** where we turn images into numpy arrays (on CPU) and save it to local.
2. **Model Training** – Importing numpy arrays to Python environment on Google Colab with GPU support (for the purpose of CNN training).
3. **Evaluation** Exporting the "pickled" model in h5 format and testing it on the previously split test subset. Displaying the correct predictions as well as incorrect predictions.
