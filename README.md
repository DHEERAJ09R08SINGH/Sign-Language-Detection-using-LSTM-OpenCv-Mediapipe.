# SignLanguageDetectionUsingML
SignLanguageDetectionUsingML

# How to run code and step to step procedure.
1) Gather the data for training by executing following command - "python collectdata.py" , webcam window will open , in blue window make appropriate sign and then press character 
   associated with it on keyboard this will record image , number of key presses = number of images recorded .
2) Then run "python data.py" to convert images to numpy array .
3) Then run "python trainmodel.py" to train the model on numpy array .
4) At last execute "python app.py" , then a webcam window will open and in which you can show the sign and get prediction by model .

Note : "functions.py" contain functions needed to process images 
