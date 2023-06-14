# (Ir)regularity in musical structure 

## (Ir)regularity in children's folk songs

In music, regularity is perceived as a highly ordered texture with prominent periodic patterns and strong neighboring relationships, in which musical ideas are organized in a way that the human mind can understand. In contrast, irregularity is experienced in an unstructured or poorly structured musical piece, where the relationship between patterns is rarely discernible and enjoyment is diminished by the enormous mental space required to process unique musical content. The interaction between regularity and irregularity in musical structure is one of the fundamental forms of musical expression used by composers across all musical styles (perhaps with different proportions in different aesthetics). 

Even though interest in children's folk songs has increased among ethnomusicologists, sociologists, educators, and folklorists since 1940, there is a lack of study on children's folk songs. The majority of research on children's folk songs is related to musical content, the social and cultural significance of children's folk songs and their relationships to adult music, the contribution of children's folk songs to cultural preservation, and the transmission of children's folk songs from generation to generation. Generally, the musical structure of children's folk songs is analyzed in terms of musical elements/dimensions, i.e., how the elements/dimensions are used (e.g., pitch span, use of meter, keys, rhythm, contour etc.).

The impact of various musical elements/dimensions on children's folk song perceptions of (ir)regularity and complexity is mostly unclear. Although cross-cultural study on melodic complexity has been undertaken, the majority of it has focused on children's lullabies. There are currently no studies that use computational models to simulate the perception of (ir)regularity in children's folk songs. This may be because children's folk songs are generally considered to be regular, with a simple structure with repeated patterns, and even as a primitive layer of folk songs.


<code style="color : cyan">PAPER:</code>

Paper (please cite): Mihelač, L., Povh, J. & Wiggins, G. A. (2021). A computational approach to the detection and prediction of(ir)regularity in children’s folk songs. Empirical Musicology Review, 16(2), 205-230. https://doi.org/10.18061/emr.v16i2.8245 

<code style="color : cyan">DATASET with description:</code>

[Ir_regularity_CFS_Songs.zip](https://github.com/LMihel/LMihel.github.io/files/10477669/Ir_regularity_CFS_Songs.zip)


## (Ir)regularity in different musical genres

### Exploring harmony (experimental approach)

In the article by Mihelač & Povh (2020), we contribute to the longstanding challenge of how to explain the listener’s acceptability for a particular piece of music, using harmony as one of the crucial dimensions in music, one of the least examined in this context. We propose three measures for the complexity of harmony: (i) the complexity based on usage of the basic tonal functions and parallels in the harmonic progression, (ii) the entropies of unigrams and bigrams in the sequence of chords, and (iii) the regularity of the harmonic progression. Additionally, we propose four measures for the acceptability of musical pieces (perceptual variables): difficulty, pleasantness, recognition, and repeatability.

These measures have been evaluated in each musical example within our dataset, consisting of 160 carefully selected musical excerpts from different musical styles. The first and the third complexity measures and the musical style of excerpts were determined by the first author using criteria described in the article, while the entropies were computed by computer using Shannon’s formula, after the harmonic progression was determined. The four perceptual variables were obtained by a group of 21 participants, taking their mean values as the final score.

A statistical analysis of this dataset shows that all the measures of complexity are consistent and are together with the musical style important features in explaining the musical acceptability. These relations were further elaborated by regression tree analysis for difficulty and pleasantness after unigram entropy was eliminated due to high correlation with bigram entropy. Results offer reasonable interpretations and also illuminate the relative importance of the predictor variables. In particular, the regularity of the harmonic progression is in both cases the most important predictor.

### Using computational approach

Human experts involved in the detection of (ir)regularity were replaced with artificial intelligence algorithms. Eight variables were evaluated in  measuring entropy and information content, which can be analysed for each musical piece using the computational model Information Dynamics of Music (IDyOM) and different viewpoints (functions for the observation of musical surface). Tested were 160 musical excerpts. A preliminary statistical analysis indicated that three of the eight variables were significant predictors of regularity (Ecpitch, ICcpintfref,and Ecpintfref). Additionally, linear separation was observed between regular and irregular excerpts.   Support vector machine and artificial neural network (ANN) algorithms with a linear kernel and a linear activation function were employed to predict regularity. The final algorithms were capable of predicting regularity with an accuracy ranging from 89% for the ANN algorithm using only the most significant predictor to 100% for the ANN algorithm using all eight prediction variables.

<code style="color : cyan">PAPERS:</code>

Paper 1 (please cite): Lorena Mihelač and Janez Povh. 2020. The Impact of the Complexity of Harmony on the Acceptability of Music. ACM Trans. Appl. Percept. 17, 1, Article 3 (January 2020), 27 pages. https://doi.org/10.1145/3375014

Paper 2 (please cite): Mihelač,L. & Povh,J.(2020).AI based algorithms for the detection of (ir)regularity in musical structure. International Journal of Applied Mathematics and Computer Science,30(4) 761-772. https://doi.org/10.34768/amcs-2020-0056

Paper 3 (please cite): Mihelač, L. & Povh, J. (2017). Predicting the acceptability of music with entropy of harmony. In Proceedings SOR’17 (pp. 371-375).

Paper 4 (please cite): Mihelač, L., Wiggins, G. A., Lavrač, N., & Povh, J. (2018). Entropy and acceptability: information dynamics and music acceptance. In Proceedings of ICMPC15/ESCOM10 (pp. 313-317).

Paper 5 (please cite): Mihelač, L. & Povh, J. (2019). The impact of harmony on the perception of music. In Proceedings SOR’19 (pp. 360-365).

<code style="color : cyan">DATASET:</code>

Dataset:Mihelac_Povh_all_harm1, Mihelac_Povh_all_harm2, Mihelac_Povh_all_harm3

[DATA_HARMCOMP.zip](https://github.com/LMihel/LMihel.github.io/files/11329843/DATA_HARMCOMP.zip)



[Back to README (MAIN)](https://github.com/LMihel/LMihelac)
