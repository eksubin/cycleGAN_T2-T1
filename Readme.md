T1 -T2 Airway & Brain MRI syntheic Image generation

Step 1 : Preprocessing

The Raw data we have is in Dicom format. So it needs to be sliced and staked on different set of folders. 
The preprocessing code is indipendently used to slice and store the images.Convert the raw dicom file using readDicomImages
The code have essesntial steps to convert the Dicom to images and to save them into specific folders.

Step 2 : Data

A sample dataset is provided with this code in data folder. The sample data contain T2 and T1 examples from brain MRI dataset.
The path towards dataset is provided in configuration/config.py file. Only this path need to be changed when running on a
custom dataset

Step 3 : Model Training

The model can be trained using demo.ipynb code. On running the code the data is extracted and converted into a numpy file.
Later this data is loaded into the gan model for training.

Step 4 : Results

the results get automaticaly generated into the root folder including the model.
