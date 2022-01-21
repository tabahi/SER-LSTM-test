# wildspeech
Speech emotion recognition in real-time using LSTM

Demo: https://tabahi.github.io/SER-LSTM-test/

Uses tensorflow JS library to predict emotions from speech MFCC features.

## Layer structure

- Dense, 33
- LSTM, 16
- LSTM, 8
- Drop-out, 0.8
- Time Distributed Dense, 5
- Softmax
