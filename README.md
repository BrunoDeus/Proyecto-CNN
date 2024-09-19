# Detection of Criminal Behavior in Auto Parts Theft using CNN

This project consists of a program developed in Python for the detection of criminal behavior related to auto parts theft. The base code was reused from open-source code and adapted to the specific needs of the project.

The development was carried out in Google Colab, using libraries such as TensorFlow, cv2, numpy, among others. Additionally, different models were implemented for comparison purposes, including LSTM, GRU, BiGRU, and CNN3D, to determine which model achieved the highest efficiency.

The dataset was created from scratch, classifying two categories: "Theft" and "No Theft." Initially, only 10 videos per class were loaded, but the complete dataset consists of 1000 videos for each category, totaling 2000 videos. To optimize performance and reduce computational consumption, the TFRecords format was used for data processing.
