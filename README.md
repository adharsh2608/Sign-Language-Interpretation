# Sign-Language-Interpretation
Sign language to text convertor can convert ASL (American Sign Language) to pure english text in real time. It uses MediaPipe holistic to extract key points and the extracted data is fed to the LSTM model. The model is trained with the collected data. The python notebook contains the code for dataset colection , training and testing. We have already trained the model using our own dataset and the model is saved as an action.h5

Steps to run the trained model:

Install all the necessary dependencies: !pip install tensorflow==2.4.1 tensorflow-gpu==2.4.1 opencv-python mediapipe sklearn matplotlib (Run the first cell if not previously installed).
In the python notebook only run the cells numbered 1-12 to load the trained model
Run the cell immediately below the 12th cell, which will open the application window
