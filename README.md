# Papers about Causal Inference and Language

A collection of papers and codebases about influence, causality, and language. 

_Pull requests welcome!_

TODO - should we double-count papers? 


# Datasets and Simulations

| Title | Description | Code |
|-------|-------------|------|
|       |             |      |
|       |             |      |

# Learning resources and blog posts

| Title | Description | Code |
|-------|-------------|------|
| [Text and Causal Inference: A Review of Using Text to Remove Confounding from Causal Estimates](https://arxiv.org/pdf/2005.00649.pdf) <br> Katherine A. Keith, David Jensen, and Brendan O’Connor   |  Survey paper about text as confounder studies.   |      |
|  [Text Feature Selection for Causal Inference](http://ai.stanford.edu/blog/text-causal-inference/) <br> Reid Pryzant and Dan Jurafsky    |   Blog post about text as treatment (operationalized through lexicons)        |      |


# Causal  Inference with Text Variables

## Text as treatment


| Title | Description | Code |
|-------|-------------|------|
|  [Challenges of Using Text Classifiers for Causal Inference](https://arxiv.org/pdf/1810.00956.pdf) <br> Zach Wood-Doughty, Ilya Shpitser, Mark Dredze     |    Looks at different errors that can stem from estimating treatment labels with classifiers, proposes adjustments to account for said errors    |   [git](https://github.com/zachwooddoughty/emnlp2018-causal)   |
|  [Deconfounded Lexicon Induction for Interpretable Social Science](https://nlp.stanford.edu/pubs/pryzant2018lexicon.pdf) <br>  Reid Pryzant, Kelly Shen, Dan Jurafsky, Stefan Wager    |  Looks at effect of text as manifested in lexicons or individual words, proposes algorithms for estimating effects and evaluating lexicons      |   [git](https://github.com/rpryzant/causal_attribution)   |
|  [How to Make Causal Inferences Using Texts](https://arxiv.org/pdf/1802.02163.pdf) <br> Naoki Egami, Christian J. Fong, Justin Grimmer, Margaret E. Roberts, and Brandon M. Stewart     |     Covers assumptions needed for text as treatment and concludes that you should use a train/test set.        |      |

## Text as mediator


| Title | Description | Code |
|-------|-------------|------|
| [Adapting Text Embeddings for Causal Inference](https://arxiv.org/pdf/1905.12741.pdf) <br> Victor Veitch, Dhanya Sridhar, and David Blei      |  (also text as confounder) Adapts BERT embeddings for causal inference by predicting propensity scores and potential outcomes alongside masked language modeling objective.      |  [tensorflow](https://github.com/blei-lab/causal-text-embeddings) <br> [pytorch](https://github.com/rpryzant/causal-bert-pytorch)    |
|       |             |      |

## Text as outcome


| Title | Description | Code |
|-------|-------------|------|
|  [Estimating Causal Effects of Tone in Online Debates](https://arxiv.org/pdf/1906.04177.pdf) <br> Dhanya Sridhar and Lise Getoor    |  Looks at effect of reply tone on the sentiment of subsiquent responses in online debates.         | [git](https://github.com/dsridhar91/debate-causal-effects)     |
|       |             |      |

## Text as confounder

| Title | Description | Code |
|-------|-------------|------|
|       |             |      |
|       |             |      |


# Causality to Improve NLP

## Causal interpretations and explanations 

| Title | Description | Code |
|-------|-------------|------|
| [CausaLM: Causal Model Explanation Through Counterfactual Language Models](https://arxiv.org/pdf/2005.13407.pdf) <br> Amir Feder, Nadav Oved, Uri Shalit and Roi Reichart     |  Suggested a method for generating causal explanations through counterfactual language representations.     |  [git](https://github.com/amirfeder/CausaLM)    |
| [Causal Mediation Analysis for Interpreting Neural NLP: The Case of Gender Bias](https://arxiv.org/pdf/2004.12265.pdf) <br> Jesse Vig, Sebastian Gehrmann, Yonatan Belinkov, Sharon Qian, Daniel Nevo, Yaron Singer and Stuart Shieber     |  Uses causal mediation analysis to interpret NLP models.     |  [git](https://github.com/sebastianGehrmann/CausalMediationAnalysis)    |


## Sensitivity and Robustness

| Title | Description | Code |
|-------|-------------|------|
|       |             |      |
|       |             |      |


# Social Sciences

## Marketing 


| Title | Description | Code |
|-------|-------------|------|
| [Predicting Sales from the Language of Product Descriptions](https://nlp.stanford.edu/pubs/pryzant2017sigir.pdf) <br> Reid Pryzant, Young-Joo Chung, and Dan Jurafsky     |  Found features of product descriptions most predictive of sales while controlling for brand & price.     |  [git](https://github.com/rpryzant/causal_attribution)    |
| [Interpretable Neural Architectures for Attributing an Ad’s Performance to its Writing Style](https://nlp.stanford.edu/pubs/pryzant2018emnlp.pdf) <br> Reid Pryzant, Kazoo Sone, and Sugato Basu     |   Found features of ad copy most predictive of high CTR while controlling for advertiser and targeting.    |  [git](https://github.com/rpryzant/deconfounded_lexicon_induction/tree/master/text-performance-attribution)    |



## Persuasion & Argumentation

| Title | Description | Code |
|-------|-------------|------|
| [Let’s Make Your Request More Persuasive: Modeling Persuasive Strategies via Semi-Supervised Neural Nets on Crowdfunding Platforms](https://www.aclweb.org/anthology/N19-1364.pdf) <br> Diyi Yang, Jiaao Chen, Zichao Yang, Dan Jurafsky, and Eduard Hovy      |   Found persuasive strategies that cause higher crowdfunding donation rates.     |   [git](https://github.com/jiaaoc/Persuasion_Strategy)   |
|       |             |      |

## Mental Health / Social Good 

| Title | Description | Code |
|-------|-------------|------|
| [Quantifying the Causal Efects of Conversational Tendencies](https://www.cs.cornell.edu/~cristian/Causal_effects_of_conversational_tendencies_files/causality_conversations.pdf) <br> Zhang, Justine, Sendhil Mullainathan, and Cristian Danescu-Niculescu-Mizil     |   Studied the effects of "conversational tendencies" (meta attributes like message length, response time, etc) on crisis counseling outcomes (whether the conversation was helpful or not to the client).       |      |
|       |             |      |

## Psychology


| Title | Description | Code |
|-------|-------------|------|
|  [Five-Star Prices, Appealing Healthy Item Descriptions? Expensive Restaurants’ Descriptive Menu Language](https://psycnet.apa.org/fulltext/2020-68187-001.html)  <br> Bradley Turnwald, Kathryn Anderson, Dan Jurafsky, Alia Crum  |   Did RCT on cafeteria food labels, observing effect on how much of those foods students took.     |      |
|       |             |      |

## Political Science


| Title | Description | Code |
|-------|-------------|------|
| [Tweetment Effects on the Tweeted: Experimentally Reducing Racist Harassment](https://link.springer.com/article/10.1007/s11109-016-9373-5)    <br> Kevin Munger  |   Did RCT sending de-escalation messages to racist twitter users, changing the "from" user and observing effects on downstream behavior.     |      |
|       |             |      |

EXAMPLE

https://github.com/rguo12/awesome-causality-algorithms
