# GRAB-SEA-AI-challenge
Safety challenge submission for GRAB's SEA AI challenge.

### Problem Statement

Given the telematics data for each trip and the label if the trip is tagged as dangerous driving, derive a model that can detect dangerous driving trips.

### Dataset

The given dataset is held within the 'safety' folder and contains telematics data during trips (bookingID). Each trip will be assigned with label 1 or 0 in a separate label file to indicate dangerous driving. Dangerous drivings are labelled per trip, while each trip could contain thousands of telematics data points. Participants are supposed to create the features based on the telematics data before training models.

### Model

The data cleaning & processing and the model training & testing process can all be found within the python notebook.
