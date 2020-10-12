# FAED-50-Dataset-for-DE-Eye
A finely annotated eye dataset denoted as FAED-50 has been built and published to give all researchers working in the area of eye localization the possibility to compare the quality of their eye localization algorithms with others. During the annotation, the complete contour of the eye including the pupil, iris, upper eyelid and lower eyelid are labelled. Therefore, the dataset can be used not only for the test of pupil localization or iris localization, but also for the segmentation of eyes. The images are captured under the near-infrared environment with a low-cost camera.

The dataset consists of two sub-folders,"Images" and "Annotations" and a “Readme.txt” file.
Image file format: The images are in the folder of "Images". There are 50 subfolders in the name of "Subjectxx" in "Images", one folder for each person. The images are stored in each folder in the name of "Subjectxx #xxxx.jpg".

Annotation file format: The annotation information are in the folder of "Annotations". There are 50 subfolders in the name of "Subjectxx" in "Annotations", one folder for each person. The annotations are stored in each folder in the name of "Subjectxx #xxxx.mat". The data are arranged in Struct format.
Data.Name -> The image name;
Data.upper_eyelid -> The labelled contour points of the upper eyelid;
Data.lower_eyelid -> The labelled contour points of the lower eyelid; 
Data.limbus_left -> The labelled contour points of the left limbus; 
Data.limbus_right -> The labelled contour points of the right limbus; 
Data.pupil -> The labelled contour points of the pupil.
