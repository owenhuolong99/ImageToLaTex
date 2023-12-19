****Image To Latex****

This is the final project code for DS301 fall 2023, by Sydney Cao, Owen Ou and Jacob Xue

Project Goal: build a model that effectively transcribe images that contain mathematical formula into LaTex code. We will experiment with several model implementations and find out the best model for the  task. 

**Model Architecture:**
encoder-decoder framework
Encoder: CNN-based with Positional Encoding
Decoder: RNN-based( Double-layer BiLSTM) + attention 
Training: Cross-entropy loss, MLE
Dataset: IM2LATEX100K 

**Note:**
The experimentations with encoder that we tried but is not applied in the final model (eg: Resnet Encoder) are in the OtherEncoder.py file.
