# dontpatronizme-NLP
Patronizing and Condescending Language Detection for [SemEval 2022](https://sites.google.com/view/pcl-detection-semeval2022/)

The Patronizing and Condescending Language Detection Task is based on the paper [Don't Patronize Me! An annotated Dataset with Patronizing and Condescending Language Towards Vulnerable Communities](https://aclanthology.org/2020.coling-main.518/) (Perez-Almendros et al., 2020).

## Objectives

- Identify PCL (Patronizing and Condescending Language) and categorize the linguistic techniques used to express it specifically when referring to communities identified as being vulnerable to unfrair treatment in the media

## Dataset

- Paragraphs extracted from news articles in English
- Given a paragraph, generate a system capable of predicting whether it contains PCL or not
- And, whether it contains any of the 7 categoories identified in the PCL taxonomy introduced in the original paper
- [Original dataset Github repo](https://github.com/Perez-AlmendrosC/dontpatronizeme)

## Main SemEval 2022 tasks

1. Binary classification:
	- Given a paragraph, a system must predict whether or not it contains any form of PCL

2. Multi-label classification::
	- Given a paragraph, a system must identify which PCL categories express the condescension.
	- PCL taxonomy categories:
		- Unbalanced power relations
		- Shallow solution
		- Presupposition
		- Authority voice
		- Metaphor
		- Compassion
		- The poorer, the merrier

## PCL

PCL (Patronizing and Condescending Language) is a type of language that denotes a superior attitude
towards others, talks down to them, or describes them or their situation in a charitable way, raising
a feeling of pity and compassion. 

This type of language is often involuntary and unconscious, and the authors using such langauge are
usually trying to help communities in need by raising awareness, moving audiences to action or 
standing for the rights of the under-represented. PCL cam potentially be very harmful, as it feeds stereotypes,
routinizes discrimination and drices to a greater exclusion.

PCL detection is hard both for humans and NLP system, due to its subtle nature, its subjectivity and
the fair amount of knowledge and commonsense reasoing required to understand this kind of language.


- [Source of info](https://competitions.codalab.org/competitions/34344)
