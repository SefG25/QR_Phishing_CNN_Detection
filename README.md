# QR_Phishing_CNN_Detection
A lightweight CNN-based deep learning model for detecting QR code phishing (quishing) attacks through pre-scan image analysis, tested on distorted, blurred, and skewed QR datasets

## Key Features
- Lightweight CNN architecture designed for real-time, pre-scan analysis
- Tested on a dataset of 1,000 synthetic QR images (benign and malicious):
  - Achieved upto 90% accuracy and was atleast 50% faster in comparison to select models
- Tested on a dataset of 5,000 synthetic QR images (benign and malicious), including:
  - Skewed, blurred, and logo-overlaid QR codes
  - Achieved up to 80% accuracy on the distorted dataset
- Easily extendable to integrate URL or metadata analysis in future hybrid models

## Dataset
- 1,000-image baseline dataset (500 malicious, 500 benign) which can be found here (DOI: 10.17632/cmhh7744sp.1)
- Expanded to 5,000 images with simulated real-world distortions (Dataset not Published)
- QR codes generated using URLs from PhishTank, URLhaus, VirusTotal, and other open sources

## Technologies
- Python 3.11
- TensorFlow / Keras
- NumPy, Matplotlib
- Google Colab / Jupyter Notebook

## Results
- Validation accuracy up to **80%** on extended dataset
- Robustness tested under varying distortions (blur, skew, overlays)

## Attribution
This project adapts a basic CNN architecture originally developed by **Akavsh Chauhan** for 10-class image classification on the Fashion MNIST dataset.  
The original model served as a foundational structure for this work. It has been modified to suit binary classification of phishing and benign QR code images, with additional dataset handling, augmentation, and hyperparameter tuning.

You can find the original work here: [Avkash Chauhan on GitHub](https://github.com/prodramp/python-projects/tree/main/deeplearning/cnn)

## Citation
This model was developed as part of an academic paper titled:  
**"Detect QR Phishing Using Novel Algorithms"**  
Accepted at **ICCCNT 2025**

## Contact
For questions or collaborations, reach out:  
**Sefiya Galadima**
