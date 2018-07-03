# Text vs Non Text Classifier

This is a SVM classifier which takes HOG of images as feature vectors. Usefully for clearing out false positives in OCR

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

Libraries needed

```
numpy
sklearn
cv2
matplotlib
```
## Running the tests

The folder crossvalidation-set and text_nontext-dataset has two sub-folders text and non-text. Add your own dataset for better results.

Run text_nontextregion_classifier.ipynb

### Results

The classifier gets a f1-score of 0.91 on training set and 0.84 on cv set

![SettingsWindow]https://raw.github.com/Vishwesh4/Text-vs-Non-Text-Classifier/master/images/false.png
![SettingsWindow]https://raw.github.com/Vishwesh4/Text-vs-Non-Text-Classifier/master/images/true.png
