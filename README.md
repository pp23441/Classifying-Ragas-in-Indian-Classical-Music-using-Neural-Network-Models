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

# Introduction of Ragas and Western Classical Music
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

## Prerequisites

Before running the notebook, ensure you have the following installed:

- Python 3.12.2 or later
- Google Colab based program
- Required Python libraries:
  - `numpy`
  - `pandas`
  - `librosa`
  - `math`
  - `scipy`
  - `scikit-learn`
  - `matplotlib`
  - `Keras`
  - `TensorFlow`
  - `q visualkeras`
  - `SpeechRecognition pydub`
  - `Sklearn`


You need to install the required libraries for run this program `pip`:

```bash
pip install numpy pandas librosa scipy scikit-learn matplotlib IPython Keras TensorFlow SpeechRecognition pydub Sklearn
```

# North Indian Classical Music Dataset


Here, the dataset is North Indian Classical Music by Kcwaghmare Waghmare[36]. This dataset
has 8 different ragas ( Such as Asawari, Bageshree, Bhairavi, Boopali, Darbari Kanada, Malkauns,
Vrindavan Sarang, and Yaman) and this side the Kaggle folder 80 Wav format Ragas as
well as including instrumental music. But, this Wav Ragas length is 4 to 5 minutes. So, this
program is splitting the data into 30 and 3 Seconds. After this process, the dataset converts into
a larger scale dataset, it’s around 500 plus 30 Seconds of Wav music and 3 Seconds of around
4425 Wav songs with instrumentals.

The Ragas included are:

  - `Asawari`
  - `Bageshree`
  - `Bhairavi`
  - `Boopali`
  - `Darbari Kanada`
  - `Malkauns`
  - `Vrindavani Sarang`
  - `Yaman`
#### Confusion Matrix
![image](https://github.com/user-attachments/assets/3c68cdba-fe0d-4304-9113-ce3f023d11dc)


# Conclusion 

As part of the project, we investigated the essence of ragas, talas, and the complex exchange of tune and beat. We also examined the overlap between Indian and Western Classical music which could potentially be used to build MIR systems which can handle both. Thus the project carries out training experiments as well as expanding our knowledge about how North Indian and Western classical musics interrelate. In this project, we used the North Indian Classical Music dataset, which classifies a set of recordings in terms of four main scales for Ragas and Talas, and in addition two other datasets for comparison, GTZAN, a Western music genre dataset, and an Ethiopian Kinit dataset. Here, tools and techniques such as CNNs and MIR can help set up a model that can identify these complexities within an Indian classical music piece and query a database consisting of such audio to identify specific features of the music. This can be useful for musicians, musicologists and specialists working with Indian classical music as it can make analysis of the traditional music much easier. Existing database such as SangeetXML can be the starting point. Such databases can be used with existing systems such as MusicXML, in a modified way to create such a model.




