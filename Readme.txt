This is the Garments Price Prediction.

The folder includes 4 ipython notebook which are configured for 4 different conditions. (2-DatasetsX2-Sizes of images. )

The images can be found in 2 datasets in the following link. --> https://drive.google.com/open?id=0B4wcTeTa5IeNcExhbS1iaXBGLTA


The datasets are split into 2. 

	1) Data with background
	2) Data Without Background


Along with the images 2 seperate sheets have been attached which contain the labels corresponding to them (MAHATI corpus.xlsx and cotton.csv).


To run the ipython notebooks ensure that both the dataset and the notebooks are aligned as per the OS paths.

//

It is suggested to run the notebooks using a Jupyter Kernal, which can be installed by downloading Anaconda 2.7. 
Along with them, we require the installation of TensorFlow-GPU which enhances the neural networks performance, which can be designed using a "Keras" Package.


RUNNING THE SYSTEM -


The notebooks are ->
	1) final_with_back.ipynb (The notebook for images with background and all images resized down to 30X30)
	2) final_with_back 50x50.ipynb (The notebook for images with background and all images resized down to 50X50)
	3) Final_without_back.ipynb (The notebook for images without background and all images resized down to 30X30)
	4) Final_without_back 50x50.ipynb (The notebook for images without background and all images resized down to 50X50)

Keras allows you to modulate all the combinations for neural network. 

As you load the images the algorithm uses an antialiasing approach to resize the images. After that the images are sent through the model created using keras ('a'). The output from the neural network which is fed into SVR by appending along with the meta features from MAHATI corpus. The output from the regression is considered the final output. The accuracy of the predictor is tested using Mean-Square-Error-Percentage.
 

FOR FURTHER ANALYSIS SEE THE REPORT. 


Thank You. 
