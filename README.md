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

## REULTS:

| Text                                                     | Label     | Polarity |
|----------------------------------------------------------|-----------|----------|
| I absolutely loved this movie! It was fantastic.         | positive  | 0.8519   |
| The product is terrible and broke after one day.         | negative  | -0.4767  |
| It was an average experience, nothing special.           | neutral   | 0.0000   |
| I'm not sure if I liked it or not.                       | neutral   | 0.0000   |
| Such a wonderful time with great friends.                | positive  | 0.8316   |
__________________________________________________________________________________


Model: "sequential"

Layer (type)   | Output Shape | Param #
---------------|--------------|---------
Dense          | (None, 64)   | 6464
Dropout        | (None, 64)   | 0
Dense_1        | (None, 3)    | 195

Total params: 6,659  
Trainable params: 6,659  
Non-trainable params: 0


Input: "I hate this product, it’s awful."
Predicted Sentiment: negative

Input: "This was a fantastic experience!"
Predicted Sentiment: positive

Input: "Not bad, could be better though."
Predicted Sentiment: neutral

Test Accuracy: 89.56%




