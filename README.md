The detect.py is the changed file in the yolov dir which is used by the model to draw bounding boxes on classes as well
as write the probability of the particular class . The only difference is that it along with that also gives the 
index value of the class being detected . So it detects like dog1 ,dog2,cat1,cat3,dog4,cat2 , etc. It gives index 
value to the class in order to associate the particular bounding box to other objects to extract insights from the 
image. 
