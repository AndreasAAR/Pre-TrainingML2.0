# Pre-TrainingML2.0

## Summary

A follow-up on my Bachelor Thesis Neural Network Project: https://github.com/AndreasAAR/ExamThesis
The purpose of the original Thesis was to pre-train a neural network and differentiate cancer types by investigating duplication of genes. 
This project will apply data-enrichment, with a focus on border-line-SMOTE http://ousar.lib.okayama-u.ac.jp/en/19617

### Pre-training explained with animals:

![image](https://user-images.githubusercontent.com/5594363/115984130-c3513c80-a5a5-11eb-842e-2fb06c40e0bd.png)



## Background

Why improve this thesis?
* The data structure is simple and compact, it could speed-up detection and differentiation of different cancer types.
* Identifying the correct combination of mutations can improve understanding of the etiology(causation) of cancer types.
* The previous model did not use border-line SMOTE, or data-enrichment outside of what the pre-training provided.  


## How is it used?

I will continue to use Python as my environment.
The neural network will be used for classifying cancers on gene duplication in patient data.
An earlier limitation was also using regular hard-ware, this time I will either rely on Uppmax: https://www.uppmax.uu.se/
Or, Google Collab: https://colab.research.google.com/notebooks/intro.ipynb#recent=true


## Data sources and AI methods

###Methods
<em>Smote:</em>
http://ousar.lib.okayama-u.ac.jp/en/19617
<em>Pre-Training:</em>
http://www.ecmlpkdd2018.org/wp-content/uploads/2018/09/295.pdf
<em>Data-Enrichment:</em>
Potentially: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2958744/
###Data
https://pubmed.ncbi.nlm.nih.gov/16751803/

## Challenges

A clear challenge is the binary nature of the data-set. The amplification data is either 1 for duplicated, or 0 for not duplicated.
This will make enrichment and also pre-training more difficult.

## What next?

A good idea would be to try to apply this to other types of genetical data.


## Acknowledgments

* list here the sources of inspiration 
* do not use code, images, data etc. from others without permission
* when you have permission to use other people's materials, always mention the original creator and the open source / Creative Commons licence they've used
  <br>For example: [Sleeping Cat on Her Back by Umberto Salvagnin](https://commons.wikimedia.org/wiki/File:Sleeping_cat_on_her_back.jpg#filelinks) / [CC BY 2.0](https://creativecommons.org/licenses/by/2.0)
* etc
