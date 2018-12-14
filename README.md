# Keras2OpenCV
Sample code for exporting Keras (tensorflow backend) model to OpenCV

4 Steps:
1. Create training model and train on Keras
2. Create inference model and load weight from training model
3. Export keras model as tensorflow ".pb" (binary protocol buffer) file
4. Load tensorflow model from OpenCV
