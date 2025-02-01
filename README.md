# Classifying-Ragas-in-Indian-Classical-Music-using-Neural-Network-Models
This project aimed to classify Indian classical music recording clips using different machinelearning techniques. We trained three models namely CNN, LSTM and VGG16 to perform feature extraction and in turn raga-based genre classification for Indian classical music. The models were trained using the approach and initial parameters of Retta et al.who were
classifying Ethiopian Kinits (pentatonic scales). Following their work, feature extraction
was performed using MFCC, Spectrogram, and Chromagram. The first dataset on which
the models were run was Andrada’s GTZAN dataset which has a collection of 10 genres
across 100 different audio files. The second was Retta’s EMIR (Kinit) dataset, and the third
was the Indian Classical Music dataset. The audio files were broken down into smaller files
based on their lengths. The first experiment focused on training CNN and LSTM models
while the second experiment was meant to optimize the VGG16 architecture. Overall, LSTM
was found to be the most accurate model for the raga-based classification with 95% accuracy,
followed by CNN and VGG16 at 97% and 60 %. This could potentially open pathways
for more work on these models with respect to Indian classical music, thus optimizing its
classification.

