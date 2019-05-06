# CS460 Project - DGA Detection 

This is a DGA detection python code that is able to classify between benign domains and maliciou domains.

# File Content
1. DGA_detection.ipynb: jupyter notebook python code for classifier
2. Data/general-train.txt: general training dataset
3. Data/general-test.txt: general testing dataset
4. Data/dictionary-based.txt: dictionary-based testing dataset
5. Data/*.h5 and Data/*.json : model weight for CNN and LSTM neural network

# Training and Testing Dataset format
The dataset is in a csv format with the order from left to right as:

SLD,TLD,MX,SPF,NXdomain,TTL

SLD - second level domain

TLD - top level domain

MX - boolean value of whether MX record exists

SPF - boolean value of whether SPF record exists

NXdomain - boolean value of whether this domain is non-existant

TTL - Average TTL value


