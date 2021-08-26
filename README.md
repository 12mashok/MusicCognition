# MusicCognition
Self Organising Maps models of Music Cognition

## About ## 
In [1], a two-layer self organising map model was trained to recognize chords and keys in western music.
The model was shown to match empirical findings on tonal hierarchies and musical expectancies. While
[1] provides a detailed account of the implicit tonal perception and organisation of the model, it directly
reports parameters used during the training phase without discussing their optimisation. 

This Jupyter script sets up the code required to run the experiments detailed in [1]. Here, self organising maps are created using MiniSOM [2].

## Coming Soon ##
The script developed here was used as a basis to optimise training parameters for the self organising maps, thereby contributing to their reproducibility. The updated scripts will be made open source soon. 

## References ##
[1] B. Tillmann, J. J. Bharucha, and E. Bigand, “Implicit learning of tonality: A self-organizing approach.,”
Psychological Review, vol. 107, no. 4, pp. 885–913, 2000, issn: 1939-1471. doi: 10.1037/
0033-295X.107.4.885. [Online]. Available: http://doi.apa.org/getdoi.cfm?doi=10.1037/
0033-295X.107.4.885.

[2] G. Vettigli, GitHub - JustGlowing/minisom: MiniSom is a minimalistic implementation of the Self
Organizing Maps. [Online]. Available: https://github.com/JustGlowing/minisom (visited on
03/30/2021).
