# SER-LSTM-test
Speech emotion recognition in real-time using LSTM

Demo: https://tabahi.github.io/SER-LSTM-test/

Uses tensorflow JS library to predict emotions from speech MFCC features.

## Trained Model

The model is trained with following layers and parameters using the IEMOCAP database to predict 4 basic emotions (Anger, Happy, Sad, Neutral, and Silence). 
- Dense, 33
- LSTM, 16
- LSTM, 8
- Drop-out, 0.8
- Time Distributed Dense, 5
- Softmax

Note: The latency increases as the MFCC buffer size increases.
