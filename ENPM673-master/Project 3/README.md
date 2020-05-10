Project - 3 Underwater Buoy detection using Gaussian Mixture Models (GWM)

Green buoy detected
![green_buoy](https://user-images.githubusercontent.com/8612835/81492498-3dd65e80-9266-11ea-8e70-bb922c8c6f0c.png)

Orange Buoy detected
![Orange_buoy](https://user-images.githubusercontent.com/8612835/81492502-4333a900-9266-11ea-97a7-1732b62d7795.png)

All buoy detected
![all_buoys](https://user-images.githubusercontent.com/8612835/81492509-4a5ab700-9266-11ea-9baf-b4034cd8ba30.PNG)


---------------------------------------------- CODES-----------------------------------------------------------------


NOTE: CODE BELOW WILL ONLY WORK IF THERE ARE A BUNCH OF IMAGES IN THE FOLDER TO CROP<br />
roipoly.py - > does the cropping using points given by the user<br />

NOTE: CODE BELOW WILL ONLY WORK IF THERE ARE A BUNCH OF IMAGES IN THE FOLDER<br />
Training_Images.py - > Python script to train the images <br />

NOTE: CODE BELOW WILL ONLY WORK IF THERE IS A VIDEO IN THE LINK<br />
Frame_Splitting.py - > Splits the frames for testing and training<br />

NOTE: CODE BELOW WILL ONLY WORK IF THERE ARE A BUNCH OF IMAGES IN THE FOLDER TO CROP<br />
green_crop.py - > just to crop the green image even further<br />

NOTE: CODE BELOW WILL ONLY WORK IF THERE IS A FOLDER AS SHOWN IN THE SCRIPT WITH IMAGES IN IT<br />
Colour_Hist_Determine.py - > to get the RGB histogram as well as R,G and B histograms seperately<br />

EM_1d_Gaussian.py - > Code for sample expectation maximization<br />

NOTE: THE THREE CODES BELOW WILL REQUIRE THE TRAINING IMAGES IN THE FOLDERS AS MENTIONED IN THE CODE. THEY HAVE ALREADY BEEN RUN,<br />
AND THEY OUPUT THE .npy files. You can find the .NPY Files in the submissions.<br />
yellow_dataset_training.py<br />
green_dataset_training.py<br />
orange_dataset_training.py<br />

NOTE: Please make sure the path is given properly for the below images,<br />
NOTE: Also, in that case, make sure the data set is present as well<br />
1D_GMM_Green.py - > 1D gaussian for the green buoy<br />
1D_GMM_Orange.py - > 1D gaussian for the Orange buoy<br />
1D_GMM_Yellow.py- > 1D gaussian for the Yellow buoy<br />

NOTE : Running the next file should give all the outputs in one image itself
combined_buoys.py -> Combined output for all the buoys together



The .npy files have been attached here as well.<br />

They contain the means weights and covariances for green orange and yellow buoys, respectively.<br />




