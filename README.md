# Song-Classification
Ceci est un repositoire pour le projet du module Interactions Homme-Machine (M2 VMI- FI) qui consiste en la classification d'une chanson selon son genre musical

## Dataset utilisé:
 lewtun/music genres (25k audio files) - [Hugging face](https://huggingface.co/datasets/lewtun/music_genres)

## Etapes:
* Transformation du dataset audio en données Mel spectrogrammes (visuelles)
* Creation d'un dataset avec les spectogrames precedents en FFT (Fast Fourier Transform)
* Classification avec CNN  ou Transformer
