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

**Introduction of Ragas and Western Classical Music:-** 
This research is focused on applying these techniques to classify Indian music, specifically
Indian classical music. There are nuances that separate Western and Indian classical music.
As [2] states, Indian music has very ancient roots. Despite it being one of the oldest musical
traditions, ”very little work has been done in the areas of genre recognition, classification,
automatic tagging, comparative studies, etc.” Though some research have existed, most of the
work done has been on classification or feature extraction centered around the Raga. Not many
researchers have worked on genre classification for Indian music.
This research aims to use CNN, LSTM, and VGG models for genre classification of Indian
music, emphasizing Indian classical music. The structure of this paper follows a brief introduction
to Indian classical music through differentiation between Indian and Western classical
music. It then explains the importance of music information retrieval, and the machine learning
models used for MIR, specifically the CNN, LSTM, and VGG models, diving deep into the
evaluation metrics. The paper then details the dataset and the experiments performed for genre
classification for Indian music, followed by discussing the limitations and future possibilities of
using such techniques on Indian music and its implications for the industry.
To better understand why there is a need for a separate classification model for Indian classical
music, it is important to understand the differences that separate Indian and Western classical
music. There are certain nuances in the features of these different styles of music that can
be leveraged to better understand and identify Indian classical music. The underpinnings of
India’s Classical music style can be traced back to centuries-old Vedas, works that filled in as the
foundation of Indian culture and thinking[32]. These texts laid the basis for a complex melodic
framework because of complicated melodic structures (ragas) and musical cycles (talas), as well
as significant profound and philosophical ideas, for example, ’bhava’ (close to home articulation)
and ’sruti’ (microtonal spans).
Conversely, Western-style Music developed from the melodic practices of antiquated Greece
and Rome, with huge commitments from archaic European writers and scholars. The improvement
of Western music hypothesis was vigorously impacted by crafted figures like Pythagoras,
who investigated the numerical connections of melodic stretches, and later by researchers, for
example, Guido of Arezzo [35], who conceived the arrangement of melodic documentation utilized
today. One eminent distinction between Indian and Western style Music lies in their ways
of dealing with song and agreement. While Western music majorly emphasizes concordance,
with complex harmony movements, Indian Traditional Music is principally melodic, zeroing in
on the ornamentations and subtleties of individual ragas.



