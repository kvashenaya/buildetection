BuildingDetection - dataset buildings

Building-detection-dataset should be annotated in YOLOv8 format

The following pre-processing should be applied to each image:
* Auto-orientation of pixel data (with EXIF-orientation stripping)
* Resize to 416x416 (Stretch)
* Auto-contrast via adaptive equalization

Put your dataset into the 'datasets' directory
The next folders should be in your datasets directory:
* test
* train
* valid