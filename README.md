# IndicSwipe

## About

IndicSwipe is aimed at developing a keyboard that supports gesture typing in Indic languages on mobile devices. IndicSwipe provides a novel Deep Learning architecture that jointly uses Transformers and LSTMs to accurately decode noisy swipe inputs and has been tested on 7 languages. To further research in this field, we release two datasets that are generated by simulations that model human motor control using the principles of jerk minimization. The models and datasets have been developed to cater to two closely related tasks:

#### Indic-to-Indic Decoding
To support users who prefer to type in the native Indic script (Devanagari, Bengali, etc.)

#### English-to-Indic Decoding
To support users who prefer to type using an English script keyboard but want the output in the native script.

IndicSwipe demonstrates high decoding accuracies on both tasks varying from 70% to 95% across the 7 languages.

<p align="center">
   <img src="../gh-pages/assets/images/gesture_sample.jpg" width=400 height=300>
</p>

## Key Contributions

1. A Gesture Path Decoding model that uses a multi-headed Transformer along with LSTM layers for coordinate sequence encoding and a character-level LSTM model for character sequence decoding.
2. A Contrastive Transliteration correction model that uses position-aware character embeddings to measure word proximities and correct spellings of transliterated words.
3. Two datasets of simulated word traces for supporting work on gesture typing for Indic language keyboards including low resource languages like Telugu and Kannada.
4. The accuracies of the proposed models vary from 70 to 89% for English-to-Indic decoding and 86-95% for Indic-to-Indic decoding across the 7 languages used for the study.

## People

This work has been developed by [Emil Biju](https://github.com/emilbiju), [Anirudh Sriram](https://github.com/anirudhs123), [Prof. Mitesh Khapra](https://www.cse.iitm.ac.in/~miteshk/) and [Prof. Pratyush Kumar](https://www.cse.iitm.ac.in/~pratyush/) from the Indian Institute of Technology, Madras. Ask us your questions at [emilbiju7@gmail.com](mailto:emilbiju7@gmail.com) or [anirudhsriram30799@gmail.com](mailto:anirudhsriram30799@gmail.com).
