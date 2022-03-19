# face-shape-recognition
Webapplication designed for Hair Salon to suggest hair styles to the user based on the face shape and feature to book an appointment



## Project Flow

- Collect Dataset of images
	- [Reference Datasets which can be used ](https://analyticsindiamag.com/10-face-datasets-to-start-facial-recognition-projects/#:~:text=%2010%20Face%20Datasets%20To%20Start%20Facial%20Recognition,by%20Google%20is%20a%20large-scale%20facial...%20More%20?msclkid=6127b717a78b11ec9537f8eaebc622ce)
- Create CNN Model
	- [Reference CNN Tutorial](https://www.tensorflow.org/tutorials/images/cnn?msclkid=f20b94fba78a11ec926ec6e0517dc44d)
- Test the model and check the accuracy.
- save the model in pickle file.
- 	- - [Reference for PICKLE FILE](https://medium.com/@maziarizadi/pickle-your-model-in-python-2bbe7dba2bbb#:~:text=Python%20has%20provided%20the%20pickle%20library%20which%20makes,into%20your%20python%20code%20with%20load%20%28%29%20function.?msclkid=3388ce68a78b11ec96d93fb44f0eb638)
- Create a Flask API which will call the model saved in pickle file and pass image as input data to get for getting the prediction.
-	- [Reference for creating API to call ML Model](https://www.datacamp.com/community/tutorials/machine-learning-models-api-python?msclkid=322b44d5a79611ecab7580490e3be14e) 
- Create a UI to get the user image.

## Web Application

- Technologies used HTML, CSS, JS

- Creating Appointment feature using SMS/Email (Suggestion to go with WhatApp Business API)
- Create FaceRecognition UI Page.
    - Create DIV which shows Webcam View.
    - Button to Capture the Image from Webcam View (to show the styles based on shape {Calls API from backend}).
    - Show the Fixed list based on the API result (i.e. Face shape).

## API's (To call ML model from Frontend)

- Technologies used Python (Flask).
- Create a API which will call the saved ML model and pass the predition (image) which comes from the front end and returns face shape as result.

## Machine Learning Model
	
- Technologies used Python.
- Create a Dataset of images will all face shapes (at least 100 images for each shape).
- Create a CNN (Convolution Neural Network) Model.
- Test the model and try to improve the accuracy.

## Documentation

To be Done
