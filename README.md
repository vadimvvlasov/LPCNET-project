## Vadim Vlasov
## May 2020
# LPCNET project
### Abstract


## 1	Introduction


### 1.1	Team
This project was completed individually by Vadim Vlasov.


### 2	Related Work
#### feachure Extraction
- waveform
- spectrogram
- mel-spectrogram
- mel-frequency ceptral coeffitients

- LPC Speech Coding as a comptression mechanism for downscaling input features
Voice production mechanism consists of 2 sources (white noise or impuls) so we can sweetch between them. And we have a filter that shapes the sound. The idea is to store the speech signal not as a sequance of samples but as a sequance of segments, for which we specify the type of exitation and filter coeffitients. This is much more compact representation of a speech signals.
Resonator model is an all-pole filter in frequency domain which is an autoregressive model in the time domain
So we have observable output signal and unknown exitation and filter coeffitients
we predict current speech sample as a linear combination of a previous samples. 
For small segments we can consider speech signal to be stationary, so we split signals approximately of 20ms chanks

#### Applications



