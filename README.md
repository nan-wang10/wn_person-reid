# wn_person-reid
We provides a new person re-identification (Re-ID) dataset containing both images and videos, called the extended image-video person (EIVP) dataset.

Due to the scarcity of image-video person Re-ID dataset, we provides a new person Re-ID dataset containing both images and videos, called the extended image-video person (EIVP) dataset. The EIVP dataset employed 8 cameras positioned on both sides of the road to capture 102 videos of varying durations. The videos are processed by setting different frame extraction frequencies to obtain 5223 basic images. After manually labeling the frames, we obtained 814 labeled images with 57 distinct identities.
The overall structure of the dataset is shown in the figure below. 
![image](https://github.com/user-attachments/assets/d7779ea9-274d-4989-8a4c-fd4c348f2040)

The image set mainly contains bounding_box_test, bounding_box_train and query, as well as a collection of image folders named in the format of ID_mobile phone number corresponding to 57 IDs.Moreover, all images adopt the same naming format as the popular person Re-ID dataset Market-1501 for identities, so that it can be applied to various models for performance evaluation based on the expansion of person information.Taking the name of the picture "1601_c1s5_40.jpg" as an example, 1601 represents the ID of the person, c1 represents that the picture comes from the first camera, s5 represents that the picture comes from the non-continuous 5th video clip of this camera, and 40 represents the number of frames in which the selected bbox appears.Using a ratio of approximately 1:1, we randomly divided the image set in the EIVP dataset into a train set and a test set with a ratio of approximately 1:1. Ultimately, the train set involves 402 images, whereas the test set comprises 412 images, comprising 349 gallery images and 63 query images. In order to generate a query set for evaluating the model's performance, for each ID, we select an image from each camera at random during the testing phase.

The video set contains video subfolders named in the format of ID_mobile phone number corresponding to 57 IDs. Each subfolder contains all the videos where that ID appears, and the videos are named in the overall order of Arabic numerals.

For the protection of personal privacy, the mobile phone numbers in the uploaded dataset folder are processed.The full dataset will be uploaded and made public in the future.

The EIVP dataset can be obtained from the following link: https://pan.baidu.com/s/14dFnnBPflp_nUpNx4Mqd4A?pwd=EIVP, and the password is EIVP.
