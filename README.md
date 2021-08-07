## HandWritten Digit Recognition

![5hke9w](https://user-images.githubusercontent.com/81034448/126903214-b410b635-88c7-4746-b8eb-653aaecee61a.gif)
- Used Scikit-learn to achieve an accuracy of 96% in
detecting legible handwritten numeric digits.
- Generated dataset using Pyscreenshot & OpenCv to train the
model.

## Dependencies

1. [scikit-learn](https://scikit-learn.org/stable/)
2. [cv2](https://docs.opencv.org/4.5.2/d6/d00/tutorial_py_root.html)
3. [pyscreenshot](https://pypi.org/project/pyscreenshot/)
4. [Joblib](https://joblib.readthedocs.io/en/latest/)
5. [pandas](https://pandas.pydata.org/)

## Contents
This repository contains the following files-

- **screen_cap.py :**   Python Script to capture Test images to test the classifier.
 
- **gen_dataset.py :**   Python Script to generate csv.

- **main.py :**   Python Script to create the classifier file , calculate accuracy and predict handwritten digits.

- **digit_recognizer :**   Classifier file for digit recognition.

- **dataset.csv :**   The dataset to train the classifier.

## Online References

- https://thedatafrog.com/en/articles/handwritten-digit-recognition-scikit-learn/
- https://scikit-learn.org/stable/auto_examples/classification/plot_digits_classification.html
