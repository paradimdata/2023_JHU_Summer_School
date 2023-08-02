#46,000 Image Data Set

This data set will help you build image recognition algorithms to detect original Legos vs. Generic Legos.

#Classes
The classes in this set are both for Lego and Generic Bricks:

1x1 Lego & Bricks
1x2 Lego & Bricks
1x4 Lego & Bricks
2x2 Lego & Bricks
2x2_L Lego & Bricks
2x3 Lego & Bricks

#File Included

Two Csv Files:

1 - ImageKey.csv: Includes a list of all the images, folder location, the corresponding background image at the time of capture, and the classification

2 - EvaluationKey.csv: The evaluation sets don't have the class in their filename, and in this file you will find each files brick type class.

3 Sets of Images:

1 - Base Images:  These are the original takes of each brick, using four cameras.  You can use the timestamp of the imagekey.csv to figure out which ones should be grouped.

2 - Cropped Images:  These already crop the brick section of the image, just in case you want to save youself some image manipulation steps and jump right into the Data Science.

3 - Four Cameras:  These are 4 camera vies for each bring merged into a single one, just in case you also want to save yourself some time and start here.

You will most likely need to reinforce the 1x1 bricks, so I have added an additional run for 1x1s.

I have also included the Background captures I peformed per run, which you can see the map in the ImageGuide file, just in case you need to run a background extraction algorithm.

Rest of the file structure is self explanatory :)