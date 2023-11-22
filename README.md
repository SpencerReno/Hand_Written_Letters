# Hand_Written_Letters
In this project I'm using a dataset with handwritten letters and using machine learning and neural networks to predict on the dataset. 

## Viewing Written Letters
![grid](https://github.com/SpencerReno/Hand_Written_Letters/assets/88803320/5d3c07ab-fd2f-471c-8601-e6726b40a38e)

This is a good way to start off with the data after cleaning is to view some of the letters. this lets us see the vast differences in how the letters are written. However, since all letters will have the same consistency in terms of a "path" they will follow to be written 
this is how the models will later predict each individual letter and be able to identify them. 

## Letter Count 
![letter count](https://github.com/SpencerReno/Hand_Written_Letters/assets/88803320/239aaeb0-6ca1-4150-9fe2-8d39a2f38985)

So, we know that the dataset is letters we do not want too much of one letter compared to another which would make our models later on over fit. looking at this graph its a pretty even distribution other than a few letters being higher than all the rest this is ok as these are very common letters you'd find in most words. 

# Machine Learning and Neural Networks 
![loss](https://github.com/SpencerReno/Hand_Written_Letters/assets/88803320/683d0f9b-ed8d-47eb-81eb-e8f9602a5cad)
![accuracy](https://github.com/SpencerReno/Hand_Written_Letters/assets/88803320/987f261d-e247-46a0-80ef-878a7e61442e)

The model I'm using to train the data on is Sequential. After some trial and error with different parameters, the best results with the model were surprisingly really good with my accuracy only off by 1%. 
Training: 98% 
Testing: 97%


