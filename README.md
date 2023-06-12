# HelmetDetection

This project uses Tensorflow object detection API to train object detection model.

# Data Collection

The HELMET dataset contains 910 videoclips of motorcycle traffic, recorded at 12 observation sites in Myanmar in 2016. Each videoclip has a duration of 10 seconds, recorded with a framerate of 10fps and a resolution of 1920x1080. The dataset contains 10,006 individual motorcycles, surpassing the number of motorcycles available in existing datasets. Each motorcycle in the 91,000 annotated frames of the dataset is annotated with a bounding box, and rider number per motorcycle as well as position specific helmet use data is available.
Data annotation was present in form of csv so scripts folder in Data section contains code to convert annotation from csv to xml and also remove images which has no label present.After this, we had 81,324 images in our dataset.

No. of labels in each class-

'DNoHelmet': 49815,
 'DHelmet': 113620,
 'DHelmetP1Helmet': 57142,
 'DNoHelmetP1NoHelmetP2NoHelmet': 6080,
 'DNoHelmetP0NoHelmetP1NoHelmet': 1535,
 'DNoHelmetP1NoHelmet': 27409,
 'DNoHelmetP1Helmet': 3174,
 'DHelmetP1NoHelmetP2Helmet': 2862,
 'DHelmetP1NoHelmet': 12202,
 'DHelmetP1NoHelmetP2NoHelmet': 2170,
 'DHelmetP0NoHelmetP1NoHelmetP2Helmet': 468,
 'DHelmetP0NoHelmetP1NoHelmet': 637,
 'DNoHelmetP0NoHelmetP1NoHelmetP2NoHelmet': 865,
 'DHelmetP0NoHelmet': 868,
 'DNoHelmetP0NoHelmet': 837,
 'DHelmetP1HelmetP2Helmet': 516,
 'DNoHelmetP1HelmetP2Helmet': 77,
 'DHelmetP0NoHelmetP1Helmet': 1047,
 'DHelmetP0NoHelmetP1NoHelmetP2NoHelmet': 180,
 'DHelmetP0HelmetP1NoHelmetP2Helmet': 100,
 'DHelmetP0HelmetP1HelmetP2Helmet': 18,
 'DHelmetP0HelmetP1Helmet': 563,
 'DHelmetP1HelmetP2NoHelmet': 120,
 'DNoHelmetP1NoHelmetP2NoHelmetP3NoHelmet': 279,
 'DHelmetP0Helmet': 274,
 'DHelmetP0HelmetP1NoHelmetP2NoHelmet': 22,
 'DNoHelmetP0NoHelmetP1Helmet': 23,
 'DHelmetP0NoHelmetP1NoHelmetP2NoHelmetP3NoHelmet': 29,
 'DNoHelmetP1NoHelmetP2Helmet': 196,
 'DHelmetP1NoHelmetP2NoHelmetP3NoHelmet': 43,
 'DHelmetP1NoHelmetP2NoHelmetP3Helmet': 59,
 'DNoHelmetP0NoHelmetP1NoHelmetP2NoHelmetP3NoHelmet': 10,
 'DHelmetP0NoHelmetP1HelmetP2Helmet': 46,
 'DNoHelmetP0HelmetP1NoHelmet': 28,
 'DHelmetP0NoHelmetP1NoHelmetP2NoHelmetP3Helmet': 49,
 'DNoHelmetP0NoHelmetP1NoHelmetP2Helmet': 14
