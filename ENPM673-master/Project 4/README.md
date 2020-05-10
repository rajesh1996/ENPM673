Project - 4 Optical flow - Lucas Kanade Affine Tracker

Bolt video detection-

![bolt](https://user-images.githubusercontent.com/8612835/81494694-dece1500-9278-11ea-977c-e4eceeec865f.jpg)



Car video detection-


![car](https://user-images.githubusercontent.com/8612835/81494704-ea214080-9278-11ea-9051-0436c42ec856.jpg)



Baby dragon video detection-


![baby](https://user-images.githubusercontent.com/8612835/81494713-f60d0280-9278-11ea-83b6-0bf2a97f4333.jpg)


The codes in .py files are as follows:

    lucas-kanade_BABY.py (lucas kanade algorithm for detection)
    rectangle_coord_Baby.py (to draw the rectangular coordinates around the baby)

    lucas-kanade_CAR.py (lucas kanade algorithm for car detection WITHOUT accounting for illumination change)
    lucas-kanade_CAR_brightened.py (lucas kanade algorithm for car detection AFTER accounting for illumination change)
    rectangle_coord_Car.py (to draw the rectangular coordinates around the car

    lucas-kanade_BOLT.py (lucas kanade algorithm for detection)
    rectangle_coord_Bolt.py (to draw the rectangular coordinates around the bolt)

NOTE: Ensure that 'APART FROM THE DATASET', the following folders are in the same directory as the codes as well 
------
Directories are:

    all_new_imgs_BABY

    all_new_imgs_CAR

    all_new_imgs_BOLT

These can be empty folders that will get populated when the code is run.
