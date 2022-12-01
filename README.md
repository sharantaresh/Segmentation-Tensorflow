# Segmentation-Tensorflow

Compared to Conventional convolution, Seperable convolution provides same accuracy with reduced number of parameters which in turn reduces the inference time while retaining the accuracy of the model.

Comparision of  conventional convolution vs Seperable Convolution can be understood with the following figure.

<img width="496" alt="image" src="https://user-images.githubusercontent.com/119483443/204989887-a62f46f5-01af-4d0e-8280-912bf7b16c4e.png">


In the notebook, a simple training pipeline for dataset preperation, Model defenition, and testing is presented for begginers to get started with segmentation projects.

Folder structure for data can be:

Image directory -> images
                |-> Masks
If seperate folders are available for Train, test, and validation, train test split can be commented and directly path can be given to the dataset function   


Happy Coding !
