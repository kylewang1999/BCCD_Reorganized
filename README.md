# BCCD_Reorganized

This dataset is a re-organized and re-sized version of the [kaggle Blood Cell Classification Dataset](https://www.kaggle.com/paultimothymooney/blood-cells), which contains 12515 images of blood cells.

The original GitHub repository of the dataset can be found [here](https://github.com/Shenggan/BCCD_Dataset/tree/master/BCCD)

The previous GitHub repo also has an [ancestor](https://github.com/dhruvp/wbc-classification), which contains annotations for white blood cell bounding boxes.

This reorganization is an attempt to alleviate the potential [labeling mistakes](https://www.kaggle.com/paultimothymooney/blood-cells/discussion/63703) in the testing dataset of the original datasets. All images in the dataset were re-shuffled and re-split into Train(75%)/Test(20%)/Validation(5%) sets. In this way, the mislabeld images are dispersed into all three subsets, instead of cluttering together in the testing set and causing lower-than-expected testing accuracy.
