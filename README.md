#Fuzzy Logic Based Sentiment Classification

This project utilizes fuzzy logic and neural networks to analyze sentiments from sentences where meaning is uncertain.

#Features
- Fuzzy logic membership functions for sentiment interpretation  
- TF-IDF feature extraction using scikit-learn  
- Simple neural network classifier (tensorflow)

#tech stack
- python 3.12.1
- scikit-fuzzy  
- scikit-learn  
- tensorFlow  
- nltk
- pandas, numpy, matplotlib


Upload python file in any interpreter and run code. default data is hardcoded. To use another dataset, replace with path/file name.

REULTS:
                                                text     label  polarity
0  I absolutely loved this movie! It was fantastic.  positive     0.8519
1  The product is terrible and broke after one day.  negative    -0.4767
2  It was an average experience, nothing special.    neutral     0.0000
3  I'm not sure if I liked it or not.               neutral     0.0000
4  Such a wonderful time with great friends.        positive     0.8316


Model: "sequential"
_________________________________________________________________
 Layer (type)                Output Shape              Param #
=================================================================
 dense (Dense)               (None, 64)                 6464
 dropout (Dropout)           (None, 64)                 0
 dense_1 (Dense)             (None, 3)                  195
=================================================================
Total params: 6,659
Trainable params: 6,659
Non-trainable params: 0
_________________________________________________________________


Test Accuracy: 89.56%

