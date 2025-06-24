# sign-language-recognization
##  Project Structure


├── Collect.py # For collecting ASL sign images (one hand gestures)

├── Collect2.py # For collecting ISL sign images (two hand gestures)

├── test.py # For testing ASL recognition

├── test2.py # For testing ISL recognition

├── Model(asl)/ # Trained model & labels for ASL

│ ├── keras_model1.h5

│ └── labels1.txt

├── Model(isl)/ # Trained model & labels for ISL

│ ├── keras_model.h5

│ └── labels.txt

├── Data(asl)/ # ASL dataset folder

├── Data(isl)/ # ISL dataset folder


## Dataset & Model Training

**Note:** The dataset folders used in this project (`Data(asl)` and `Data(isl)`) are not included here because they are too large to upload.

If you’d like to train your own model, you can easily create a dataset using the provided collection scripts. Just run `Collect.py` for ASL or `Collect2.py` for ISL — both will let you capture images using your webcam. Every time you press the spacebar, a new image of the hand sign will be saved in the appropriate folder.

However, if you don’t want to go through the training process yourself, no worries — this project already includes pre-trained models for both ASL and ISL. You can use them directly with the test scripts and start recognizing signs right away.

