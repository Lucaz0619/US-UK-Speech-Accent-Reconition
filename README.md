# US-UK-Speech-Accent-Reconition    


## DataSet  

All of the speech file come from [Mozilla Voice data](https://commonvoice.mozilla.org/en/datasets).
I random chose 35,000 data for England and US each.    

## Dependencies  

* Python                 &emsp;&emsp;3.7  
* CUDA                   &emsp;&emsp;10.1  
* cudnn                  &emsp;&emsp;8.0.3  
* Tensorflow             &emsp;&emsp;2.1.0  
* Keras                  &emsp;&emsp;2.3.1  
* Librosa                &emsp;&emsp;0.8.0  
* Scikit-learn           &emsp;&emsp;0.23.2    


## Method  

First, vectorize all the .mp3 audio files by Mel Frequency Cepstrum Coefficients (MFCC). It can be easily completed by Librosa package. Save the MFCC value and labels in a .json file. And then creat model and train them!    


## Result  

Test accuracy of each model below:    

* MLP :              &emsp;&emsp;0.7884029  
* 2-D CNN :          &emsp;&emsp;0.7967419  
* RNN-LSTM :         &emsp;&emsp;0.8145798  
