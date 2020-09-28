# US-UK-Speech-Accent-Reconition    


## DataSet  

All of the speech file come from [Mozilla Voice data](https://commonvoice.mozilla.org/en/datasets).
I random chose 35,000 data for England and US each.    

<p align="right">诶嘿</p>
## Dependencies  

Python                 <p align="right">3.7</p>  
CUDA                   <p align="right">10.1</p>  
cudnn                  <p align="right">8.0.3</p>  
Tensorflow             <p align="right">2.1.0</p>  
Keras                  <p align="right">2.3.1</p>  
Librosa                <p align="right">0.8.0</p>  
Scikit-learn           <p align="right">0.23.2</p>    


## Method  

First, vectorize all the .mp3 audio files by Mel Frequency Cepstrum Coefficients (MFCC). It can be easily completed by Librosa package. Save the MFCC value and labels in a .json file. And then creat model and train them!    


## Result  

Test accuracy of each model below:    

MLP :              <p align="right">0.7884029</p>  
2-D CNN :          <p align="right">0.7967419</p>  
RNN-LSTM :         <p align="right">0.8145798</p>  
