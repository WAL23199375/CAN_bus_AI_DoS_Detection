# CAN_bus_AI_DoS_Detection
overview
This project is an AI intrusion detection system that focuses on identifying DoS attacks on CAN bus
the dataset is Car-Hacking Dataset @ https://ocslab.hksecurity.net/Datasets/car-hacking-dataset
the raw files can be found in this link by filling out a google form
the notebook expects-
- normal_run_data.txt
- DoS_dataset.csv

  results
              precision    recall  f1-score   support

           0       0.94      0.86      0.90    197774
           1       0.96      0.98      0.97    733155

    accuracy                           0.96    930929
   macro avg       0.95      0.92      0.93    930929
weighted avg       0.96      0.96      0.96    930929

run this in google colab
