# Dataset4LandslideNets
A large-scale and multisensor dataset is developed for deep learning-based landslide detection. The dataset aims to address the challenges encountered in landslide recognition. With the increase in landslide occurrences due to climate change and earthquakes, there is a growing need for a precise and comprehensive dataset to support fast and efficient landslide recognition. In contrast to existing datasets with dataset size, coverage, sensor type, and resolution limitations, the Landslide Dataset comprises 20,865 images, integrating satellite and unmanned aerial vehicle data from nine regions. The dataset is open and accessible to all landslide researchers and professionals. The data contains a project file labelled CAS Landslide Dataset, along with a study areas shp file and 16 zip files representing the different sub-datasets. Each sub dataset consists of three subfolders: img, label, and mask. It is important to note that in our mask files, landslide areas are labelled as 1, while non-landslide areas are labelled as 0. Dataset4LandslideNets is available at https://doi.org/10.5281/zenodo.10294997
# Location map of the study areas
![Location map of the study areas](https://github.com/HydroPML/Dataset4Landslide/blob/main/41597_2023_2847_Fig1_HTML.webp)
# [LandslideNet](https://github.com/xupine/LandslideNet)
![](https://github.com/HydroPML/Dataset4LandslideNets/blob/main/landslideNet.png)
# Benchmarks
Results for different subdatasets.
|   **UAV**   |           |         |         |          |         |         |
|:-----------:|:---------:|:-------:|:-------:|:--------:|:-------:|:-------:|
|    Models   | Precision |  Recall |   IoU   | F1 score |   mIoU  |    OA   |
|     FCN     |  75.045%  | 84.016% | 65.057% |  86.724% | 77.456% | 91.468% |
|     Unet    |  73.694%  | 86.394% | 65.991% |  87.136% | 78.019% | 91.658% |
|  DeepLabv3+ |  89.289%  | 93.739% | 84.261% |  94.715% | 90.142% | 96.721% |
|   MFFENet   |  89.326%  | 93.839% | 84.375% |  94.756% | 90.214% | 96.746% |
|   **SAT**   |           |         |         |          |         |         |
|     FCN     |  62.981%  | 84.142% | 55.716% |  84.391% | 75.173% | 94.972% |
|     Unet    |  61.795%  | 78.550% | 51.179% |  82.316% | 72.619% | 94.410% |
|  DeepLabv3+ |  74.275%  | 89.187% | 68.137% |  89.675% | 82.397% | 96.881% |
|   MFFENet   |  74.141%  | 89.141% | 67.998% |  89.621% | 82.318% | 96.862% |
| **UAV&SAT** |           |         |         |          |         |         |
|     FCN     |  70.847%  | 84.014% | 61.757% |  85.864% | 76.515% | 92.848% |
|     Unet    |  67.479%  | 82.360% | 60.115% |  85.311% | 75.697% | 92.653% |
|  DeepLabv3+ |  86.128%  | 92.013% | 80.125% |  93.563% | 88.316% | 96.687% |
|   MFFENet   |  86.133%  | 92.121% | 80.088% |  93.608% | 88.299% | 96.754% |
# References
[1] Xu, Y., Ouyang, C., Xu, Q. et al. CAS Landslide Dataset: A Large-Scale and Multisensor Dataset for Deep Learning-Based Landslide Detection. Scientific Data 11, 12 (2024). https://doi.org/10.1038/s41597-023-02847-z.  
[2] Xu, Q. et al. MFFENet and ADANet: a robust deep transfer learning method and its application in high precision and fast cross-scene recognition of earthquake-induced landslides. Landslides 19, 1617–1647 (2022). [Paper](https://doi.org/10.1007/s10346-022-01847-1). [Code](https://github.com/xupine/LandslideNet) 


