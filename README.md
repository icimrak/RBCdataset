# RBCdataset
Dataset containing partially annotated video sequences of cell flow through microfluidic devices. Dataset contains two video sequences, xml files containing cell annotations in the form of bounding boxes and track annotations so that individual cell can be tracked throughout the video sequence.

When using this dataset, please cite the following paper:
I. Cimrák, P. Tarábek, F. Kajánek, Curated dataset for red blood cell tracking from video sequences of flow in microfluidic devices, Data 2023, X(X), XX; https://doi.org/10.3390/dataXXXXXX (to be updated after publishing)

Dataset contains two directories for two video sequence. Each sequence directory contains individual frames sorted consecutively in subdirectories with 50 images (for annotated frames). The un-annotated frames can be extracted from the original video. Original video file is present together with the xml file containing the bounding boxes for the cells and information about the tracks for individual cells throughout the video sequence. Finally, here is a file containing the flow matrix that gives the information about the fluid flow in the microfluidic channel. his information may be used for tracking algorithms.

For further details we refer to above open-access article. 
