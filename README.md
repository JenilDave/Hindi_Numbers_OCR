# Hindi_Numbers_OCR
This Project is developed which has simple DNN which works on detecting numbers written on Devanagari Number Script.

Model was trained using UCI Machine Learning Dataset Available: https://archive.ics.uci.edu/ml/datasets/Devanagari+Handwritten+Character+Dataset
Model is trained in Google Colab in code.ipynb file.
digits.h5 is the model

Preprocess.py consists of the image preprocessing algorithm to extract the number to be given into model.
Images are to be converted into 32x32 form.

To run the file type-> ```python main.py```
It will run on the image given in directory will be considered for detection.

main.py is creating obejct of the class.
