---
title: "Unstable trees: The challenge of frequency and phonology in phylogenetics"
collection: talks
type: "Talk"
permalink: /talks/unstable-trees
venue: "The 5th Edinburgh Symposium on Historical Phonology"
date: 2021-12-06
paperurl: 'https://ed-ac-uk.zoom.us/rec/play/vEiSdzG9rvyFdMvCfEMZ7AlR6Gpcd7m_h5oosZ8qBvFp6U2ARDdFqasdUG4hEo5zFuNc8EGRIodcC2sy.9PXB5JuWLcvaaMot?startTime=1638810203000&_x_zm_rtaid=9gcrN7FFSzG6jJhJnwe0kg.1642525542292.fe712ad7428611b932b24a465a94f1ce&_x_zm_rhtaid=742'
location: "University of Edinburgh, Scotland"
---

[Zoom recording](https://ed-ac-uk.zoom.us/rec/play/vEiSdzG9rvyFdMvCfEMZ7AlR6Gpcd7m_h5oosZ8qBvFp6U2ARDdFqasdUG4hEo5zFuNc8EGRIodcC2sy.9PXB5JuWLcvaaMot?startTime=1638810203000&_x_zm_rtaid=9gcrN7FFSzG6jJhJnwe0kg.1642525542292.fe712ad7428611b932b24a465a94f1ce&_x_zm_rhtaid=742)

In this paper, I present a cautionary tale of phylogenetic tree inference gone awry. The study is an attempt to infer a phylogeny of the western branch of the Pama-Nyungan family with a combination of lexical data (binary cognates) and phonotactic data (biphone frequencies). Although the study largely fails to produce stable results, it is illustrative of the challenges ofincorporating data beyond lexical cognates in linguistic phylogenetics. Here, I elucidate why thischallenge is important and outline a path forward for the field.

### Background

Computationally inferred language phylogenies have become a regular feature of mainstream historical linguistics (e.g. Yanovich 2020; Savelyev & Robbeets 2020; Jacques & Pellard 2020). A limitation of phylogenetic tree inference at present, however, is an overreliance on lexical cognate data. There is thus some interest in expanding phylogenetic datasets to be more encompassing of other parts of human language (e.g. Greenhill et al. 2017). As this study demonstrates, however, this is a bigger challenge than one might assume, particularly when matters of frequency are considered.

Earlier research has found phylogenetic signal in statistical phonotactic data, namely the frequencies of transitions between adjacent phonemes and sound classes, indicating possible utility in tree inference (Dockum 2018; Macklin-Cordes, Bowern & Round 2021). This study puts that indication to the test, attempting the actual task of phylogenetic tree inference using statistical phonotactic data and lexical cognate data combined.

### Methodology

To test whether phonotactic data strengthens tree inference, I compare the relative fits of two models, a ‘linked’ model in which a tree is inferred from cognate data and phonotactic data together and a ‘separate’ model in which trees are inferred from phonotactic data and cognate data separately. The language sample consists of 44 Pama-Nyungan languages from the major western clade identified by Bowern & Atkinson (2012). Cognate data comes from from Bouckaert, Bowern & Atkinson (2018) and phonotactic data was extracted from the AusphonLexicon database (Round 2017). Trees are inferred using a Bayesian Markov Chain Monte Carlo (MCMC) approach in BEAST software (Suchard et al. 2018). For each model, I infer marginal likelihood estimates (MLEs) which give an indication of model fit. The MLEs are compared to one another to indicate relative fit. If the hypothesis that phonotactic data strengthens tree inference is true, the fit of the linked model should be relatively better than the separate model.

### Results

The results of the study are indeterminate, due to a lack of stable MCMC convergence. Essentially, when the MCMC process is repeated multiple times on each model, it produces inconsistent results. MLEs ostensibly favour the linked model, which would give support to the study’s hypothesis, but these values are revealed to be unreliable upon further interrogation. It is also illustrative to compare the phylogeny produced by the linked model to a baseline tree inferred from cognate data only. The addition of phonotactic data has the undesirable effect of flattening the internal structure of the tree into more of a ‘star’ (a.k.a. ‘rake’) phylogeny, and certain specific
phonological changes in proto-Arandic have an outsized effect on subgroup placement.

### Discussion

Is this the end of the road for phonotactic data in phylogenetics or just a hiccup in experimental design? I present a more nuanced interpretation. There are real computational challenges to modelling the evolution of frequency variables. The model in this study was drastically simplified to make the study computationally feasible, but this rendered it an unrealistic abstraction of real language change. There are technical solutions (most straightforwardly, greater computational power) that might help. More importantly, however, I propose a step-by-step framework for evaluating new types of data other than lexical cognates in linguistic tree inference and advocate for a more careful linkage between real-world diachronic processes and the statistical architecture of these methods.
