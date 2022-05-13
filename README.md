# Automatic Blood Cell Detection with Convolutional Neural Networks

Detecting and counting blood cells is beneficial to biology and medical practices in order to identity a patient's health. A complete blood count (CBC) can help medical professionals identify blood-related disorders such as anemia, leukemia, and much more. Due to the high number of blood cells, having a computer count the number of cells is the best method to determining the CBC. 

Machine learning can be used to identify and count blood cells through a training data set. The computer is able to use pre-highlighted blood cell images to "learn" the characteristics of the different type of blood cells. Using the newly learned characteristics, the computer is then able to successfully identify blood cell types.

## Installation

Using [Anaconda](https://www.anaconda.com/):

```sh
conda install -c pytorch pytorch
conda install -c anaconda numpy
conda install -c conda-forge detectron2
conda install -c conda-forge opencv
conda install notebook
```

Then, run the `blood_cell_detection.ipynb` file as a jupyter notebook.

## Contributors

- [Brandon Nguyen](https://github.com/gnuyent)
- [Jordan Shands-Sparks](https://github.com/12jordans)

## Resources

- [BCCD Dataset](https://public.roboflow.com/object-detection/bccd)
- [Blood Cell Detection Dataset](https://www.kaggle.com/datasets/draaslan/blood-cell-detection-dataset)
- [detectron2](https://github.com/facebookresearch/detectron2)
