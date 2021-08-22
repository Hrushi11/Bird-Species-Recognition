# Bird Species Recognition

Data set of 285 bird species.40930 training images, 1425 test images(5 images per species) and 1425 validation images(5 images per species.
All images are 224 X 224 X 3 color images in jpg format. Data set includes a train set, test set and validation set. Each set contains 285 sub directories, 
one for each bird species. The data structure is convenient if you use the Keras ImageDataGenerator.flowfromdirectory to create your train, test and valid data generators. 

Visit the blog here - [Bird Species Recognition]()

![IMG](https://github.com/Hrushi11/Bird-Species-Recognition/blob/main/images/random_img_crp.jpg?raw=true)

The data set also include a file Bird Species.csv. This cvs file contains three columns. The filepaths column contains the file path to an image file. 
The labels column contains the class name associated with the image file. The Bird Species.csv file if read in using df= pandas.birdscsv(Bird Species.csv) 
will create a pandas dataframe which then can be split into traindf, testdf and validdf dataframes to create your own partitioning of the data into train, test 
and valid data sets

![IMG](https://github.com/Hrushi11/Bird-Species-Recognition/blob/main/images/random_img2.png?raw=true)

### Predictions made by the model:

![IMG](https://github.com/Hrushi11/Bird-Species-Recognition/blob/main/images/corr1.png?raw=true)

### Wrong predictions made by the model:

![IMG](https://github.com/Hrushi11/Bird-Species-Recognition/blob/main/images/wrng_multi_1.png?raw=true)

### Wrongly predicted with confusion graph:

![IMG](https://github.com/Hrushi11/Bird-Species-Recognition/blob/main/images/wrng_conf_3.png?raw=true)
