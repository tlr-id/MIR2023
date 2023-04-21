Projects realised in the context of Music Information Retrieval class of the SMC Master inside the MTG @ UPF - 2022/2023.

Final grade : 100/100.

# 1 - Mid Project : Classification task

The goal is to realise a classification task on a dataset by implementing several models.

In my case, I'm doing genre classification of electronic music genres using the EDM Beatport Key Dataset (https://zenodo.org/record/1101082), a dataset initially made for Key estimation of EDM tracks.

Obtaining the following results : 
*  SVM : 42% accuracy
*   Sequential model (Neural Network) : 60% accuracy
*   KNN : 68% accuracy but very sensitive to noise and outliers
*   KNN with LDA : Nearly 90% accuracy

Could be improved in many way, but it's a nice introduction to this topic.

# 2 - Final Project : Automatic lyrics & phonemes alignment

Goal of the project : providing the experience of going through the “standard”
workflow of R&D in this domain. This involves solving a small research problem or
reproducing an already existing system on a different dataset

In my case, I chose to work on automatic lyrics & phonemes alignment on a dataset that wasn't 

I applied 2 SoTA algorithms on a dataset : 
- `Phoneme Level Lyrics Alignment and Text-Informed Singing Voice Separation` by `K Schulze-Forste Et Al.` - `https://github.com/schufo/lyrics-aligner#readme`.
- `Improving lyrics alignment through joint pitch detection` by `J.Huang et Al.` - `https://github.com/jhuang448/lyricsalignment-mtl`
- Vocadito dataset by `RM Bittner Et Al.` - `https://zenodo.org/record/5578807`

Results are presented in the pdf paper within Git : 
`Expanding the Vocadito dataset by experimenting with automatic lyrics & phonemes alignment algorithms`

![alt text](https://github.com/tlr-id/MIR2023/blob/main/results_1.png?raw=true)
![alt text](https://github.com/tlr-id/MIR2023/blob/main/results_2.png?raw=true)

# 3 - Side Quest

A secondary objectif I set myself : The paper `Phoneme Level Lyrics Alignment and Text-Informed Singing Voice Separation` doesn't have a Colab notebook to showcase how to apply the algorithm. 
I created this one, and requested it to the author of the paper.