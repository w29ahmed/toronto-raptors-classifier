# toronto-raptors-classifier
A model re-trained using Google's Inception V3 image classifier to classify Toronto Raptors players. Current model only classifies DeMar DeRozan and Kyle Lowry.

retrain.py script original source: https://github.com/tensorflow/hub/tree/master/examples/image_retraining
label_image.py original source: https://github.com/tensorflow/tensorflow/tree/master/tensorflow/examples/label_image

TODO: 
- Retrain classifier with more images of more players
- Ensure images are diverse and don't contain any other players 
- Modify label_image.py to retrieve image path from a GUI (tkinter file dialog)
- Display output from label_image.py as an image with players highlighted rather than printing prediction values to the command line
