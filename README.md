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
		- **Unbalanced power relations**. By means of the language, the author distances themselves from the community or the situation they are talking about and expresses the will, capacity or responsibility to help them. It is also present when the author entitles themselves to give something positive to others in a more vulnerable situation, especially when what the author concedes is a right which they do not have any authority to decide to give.

		- **Shallow solution**. A simple and superficial charitable action by the privileged community is presented either as life-saving/life-changing for the unprivileged one or as a solution for a deep-rooted problem.

		- **Presupposition** when the author assumes a situation as certain without having all the information or generalises their or somebody else’s experience as a categorical truth without presenting a valid, trustworthy source for it (e.g. a research work or survey). The use of stereotypes or clichés is also considered to be examples of presupposition.

		- **Authority voicev** when the author stands themselves as a spokesperson of the group, or ex-plains or advises the members of a community about the community itself or a specific situation they are living.

		- **Metaphor**. They can conceal PCL, as they cast an idea in another light, making a comparison between unrelated concepts, often with the objective of depicting a certain situation in a softer way. For the annotation of this dataset, euphemisms are considered as an example of metaphors.

		- **Compassion**. The author presents the vulnerable individual or community as needy, raising a feeling of pity and compassion from the audience towards them. It is commonly characterized by the use of flowery wording that does not provide information, but the author enjoys the detailed and poetic description of the vulnerability.

		- **The poorer, the merrier**. The text is focused on the community, especially on how the vulnerability makes them better (e.g. stronger, happier or more resilient) or how they share a positive attribute just for being part of a vulnerable community. People living in vulnerable situations have values to admire and learn from. The message expresses the idea of vulnerability as something beautiful o or poetic. We can think of the typical example of ‘poor people are happier because they don’t have material goods’.

## PCL

PCL (Patronizing and Condescending Language) is a type of language that denotes a superior attitude towards others, talks down to them, or describes them or their situation in a charitable way, raising a feeling of pity and compassion. 

This type of language is often involuntary and unconscious, and the authors using such langauge are usually trying to help communities in need by raising awareness, moving audiences to action or  standing for the rights of the under-represented. PCL cam potentially be very harmful, as it feeds stereotypes, routinizes discrimination and drices to a greater exclusion.

PCL detection is hard both for humans and NLP system, due to its subtle nature, its subjectivity and the fair amount of knowledge and commonsense reasoing required to understand this kind of language.


- [Source of info](https://competitions.codalab.org/competitions/34344)
