# keyword_spotting
keyword spotting for speech 

the key word is 'dog',and the time length of the wav file is about 1 second. 

Noise are other words, and all the words wav files could be find in 

https://github.com/tensorflow/tensorflow/blob/master/tensorflow/examples/speech_commands/input_data.py 
Thanks to the corpus.

You can test the project.

The data input reference the project 

https://github.com/friday27/KeywordSpotting

Just used for shuffle the wav data and label the data with 0 or 1.


About the feature,this version is mfcc-128,also you can use other feature, such plp,plcc,mfcc-delta,mfcc-delta2,
Nowadays,I have tried mfcc-20,mfcc-delta-20,mfcc-delta2-20,but the result is not good, worse than mfcc-128.
