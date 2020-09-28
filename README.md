# US-UK-Speech-Accent-Reconition    


## DataSet  

All of the speech file come from [Mozilla Voice data](https://commonvoice.mozilla.org/en/datasets).
I random chose 35,000 data for England and US each.    

## Dependencies  

Python                 &ensp3.7 
CUDA                   10.1  
cudnn                  8.0.3  
Tensorflow             2.1.0  
Keras                  2.3.1  
Librosa                0.8.0  
Scikit-learn           0.23.2    


## Method  

First, vectorize all the .mp3 audio files by Mel Frequency Cepstrum Coefficients (MFCC). It can be easily completed by Librosa package. Save the MFCC value and labels in a .json file. And then creat model and train them!    


## Result  

Test accuracy of each model below:    

MLP :              0.7884029  
2-D CNN :          0.7967419  
RNN-LSTM :         0.8145798  
