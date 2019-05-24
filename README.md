# Brain-Tumour-Extraction-from-MRI-Images
The algorithm has two stages, first is pre-processing of given MRI image and after that segmentation and then perform morphological operations. Steps of algorithm are as following:-
1) Give MRI image of brain as input.
2) Convert it to gray scale image.
3) Apply high pass filter for noise removal.
4) Apply median filter to enhance the quality of image.
5) Compute threshold segmentation.
6) Compute watershed segmentation.
7) Compute morphological operation.
8) Finally output will be a tumour region.
