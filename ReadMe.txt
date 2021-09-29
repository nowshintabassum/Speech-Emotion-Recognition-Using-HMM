README:

Please UPLOAD the following files before testing for a Single Audio in Google Colab,

i)   SER_Spec_35  -> Trained model pickle file.
ii)  feature_extraction_utils.py  -> Praat software utils for feature extraction.
iii) Audio file 'happy.wav'/'angry.wav'
iv)  SER_features-on-3-datasets.csv  -> All 81 extracted features from 3 datasets.(Only needed to Train)

Run the following functions before running Test on one audio,

i)  !pip install praat-parselmouth
ii) extract_pros_features
iii)extract_spec_features
iv) get_features
v)  imported libraries
vi) HMMTrainer Class

It may take 2 days to extract all the features and train the model, so only executing the above mentioned
functions and executing from the section "Test on One audio File' will be enough to test an audio file.
Links for the 3 Datasets are given in the Notebook.