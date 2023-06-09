# HelmetDetection

This project uses Tensorflow object detection API to train object detection model.

# Data Collection

The HELMET dataset contains 910 videoclips of motorcycle traffic, recorded at 12 observation sites in Myanmar in 2016. Each videoclip has a duration of 10 seconds, recorded with a framerate of 10fps and a resolution of 1920x1080. The dataset contains 10,006 individual motorcycles, surpassing the number of motorcycles available in existing datasets. Each motorcycle in the 91,000 annotated frames of the dataset is annotated with a bounding box, and rider number per motorcycle as well as position specific helmet use data is available.
Data annotation was present in form of csv so scripts folder in Data section contains code to convert annotation from csv to xml and also remove images which has no label present.After this, we had 81,324 images in our dataset.
