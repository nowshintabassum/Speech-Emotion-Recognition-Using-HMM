

### Please UPLOAD the following files before testing for a Single Audio in Google Colab

1. SER_Spec_35  -> Trained model pickle file.
2. feature_extraction_utils.py  -> Praat software utils for feature extraction.
3. Audio file 'happy.wav'/'angry.wav'
4. SER_features-on-3-datasets.csv  -> All 81 extracted features from 3 datasets.(Only needed to Train)

### Run the following functions before running <b>Test on one audio </b>

1. !pip install praat-parselmouth
2. extract_pros_features
3. extract_spec_features
4. get_features
5. imported libraries
6. HMMTrainer Class

It may take 2 days to extract all the features and train the model, so only executing the above mentioned
functions and executing from the section "Test on One audio File' will be enough to test an audio file.
Links for the 3 Datasets are given in the Notebook.
