# GRAB-SEA-AI-challenge
Safety challenge submission for GRAB's SEA AI challenge.

### Problem Statement

Given the telematics data for each trip and the label if the trip is tagged as dangerous driving, derive a model that can detect dangerous driving trips.

### Dataset

The dataset can be downloaded from <a href="https://s3-ap-southeast-1.amazonaws.com/grab-aiforsea-dataset/safety.zip">here</a> (direct link was taken from the <a href="https://www.aiforsea.com/safety?utm_campaign=f1dd5e04-1a38-49d3-b6c1-fd98961f9920&utm_source=so">GRAB challenge website</a>).

The dataset (a folder named 'safety') should be stored in the same directory as the python notebook, at the same level.

The given dataset contains telematics data during trips (bookingID). Each trip will be assigned with label 1 or 0 in a separate label file to indicate dangerous driving. Dangerous drivings are labelled per trip, while each trip could contain thousands of telematics data points. Participants are supposed to create the features based on the telematics data before training models.

### Model

The data cleaning & processing and the model training & testing process can all be found within the python notebook.
