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

- screen_cap.py - Python Script to capture images of drawn digits.
![rsz_1screenshot_29](https://user-images.githubusercontent.com/81034448/128590229-05a12ab5-97ce-4770-b3b2-754acb251ec7.png=250x50)
 
- gen_dataset.py - Python Script to generate csv.
![image](https://user-images.githubusercontent.com/81034448/128590308-8d550421-f0ee-4098-8002-370129bf21d2.png)

- main.py - Python Script to create the classifier file , calculate accuracy and predict handwritten digits.

- photo_1.jpg - Test image number 1 to test the classifier
- photo_2.jpg - Test image numbre 2 to test the classifier
- Python Script to create the classifier file digits_cls.pkl.Classifier file for digit recognition.
