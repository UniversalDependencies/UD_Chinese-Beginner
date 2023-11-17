# Summary
A treebank of Chinese sentences adapted for learner of level A1 to C1 (HSK1 to 5) collected on the [Chinese Grammar Wiki](https://resources.allsetlearning.com/chinese/grammar/) (CC BY-NC-SA 3.0 License) website. The treebank was manually annotated by researchers of Paris Nanterre University (Modyco) in the mSUD annotation schema (morpheme level Surface Universal Dependencies).  


# Introduction
The syntactic analysis is originally done in SUD on the character level under the name SUD_Chinese-PatentChar. See SUD Guidelines : https://surfacesyntacticud.github.io/guidelines/u/

## Structure of the Treebank
The Treebank is partitioned in 5 parts A1, A2, B1, B2 and C1 that represents different level of difficulty (from easiest to hardest). 

/!\ At the day of October 12th of 2023, 2295 sentences have been hand annotated (around 20k tokens in total). But below is the complete distribution of the corpus when it will be finished. 

The corpus is made of around 4300 sentences, with the following distribution : 
- A1 : 382 sentences (3456 tokens , ~ 9.05 tokens per sentences)
- A2 : 1103 sentences (11920 tokens, ~ 10.80 tokens per sentences)
- B1 : 1347 sentences (18236 tokens, ~ 15.54 tokens per sentences)
- B2 : 1441 sentences (24419 tokens, ~ 16.95 tokens per sentences)
- C1 : 300 sentences (5482 tokens, ~ 18.27 tokens per sentences)

## Data Split
The treebank is still being annotated and around 40% of the sentences are yet to be annotated or validated. Therefore, the current version is not representative of the final distribution which prevent us for doing a representative data split that would be stable across release ([see UD data split guidelines](https://universaldependencies.org/release_checklist.html#data-split)). Until the treebank is fully annotated, we will not split the data and release all sentences in a single test folder. Please perform 10 fold cross validation if you are using this treebank for any machine learning task.

 

## Structure of a sentence
Here an example of the meta data that each sentences contains : 
```
# sent_id = 1
# structure = 没 + 有 (+ Obj.)
# text = 我没有问题。
# level = A1
# structure_verbose = Negation of "you" with "mei"
# url = https://resources.allsetlearning.com/chinese/grammar/ASGPNV3Q
# text_en = I don't have any questions.
# translit = Wǒ méiyǒu wèntí.
# text_orig = 我 没有 问题。
```

# Acknowledgments
This annotation work is supported by the [Autogramm project](https://autogramm.github.io/) and rely on the extensive work done by AllSetLearning contributors to the Chinese Grammar wiki.

## References

* Please cite any of this github repo, the original mSUD repo or the SUD conversion as well as the original content [Chinese Grammar Wiki](https://resources.allsetlearning.com/chinese/grammar/\).


# Changelog

* 2023-11-15 v2.13
  * Initial release in Universal Dependencies.


<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v2.13
License: CC BY-NC-SA 3.0 
Includes text: yes
Genre: grammar-examples
Lemmas: manual native
UPOS: manual native
XPOS: not available
Features: manual native
Relations: manual native
Contributors: Guiller, Kirian; Huang, Yidi; Li, Yixuan; Wu, Qishen; Guillaume, Bruno; Kahane, Sylvain; Gerdes, Kim
Contributing: here
Contact: kiriangui@gmail.com
===============================================================================
</pre>
