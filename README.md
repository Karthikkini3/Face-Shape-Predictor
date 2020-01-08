# Face-Shape-Predictor
To identify face shape and eye position on videostream

To run the program, download the iBug 300-W Dataset and perform the following steps:
1) to seperate eye coordinates, run the parse_xml.py script to reduce the size of dataset
2) run the train_shape_predictor.py to train the model and create eye_predictor.dat
3) to evaluate your model, rum evaluate_shape_predictor.py script
4) run the predict_eyes.py to start the videostream
