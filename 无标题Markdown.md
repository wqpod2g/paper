## 问题定义
- 实体关系抽取：是指确定实体之间是否存在关系并确定其关系类别的任务，它是信息抽取的一个子任务；
## 研究现状
1. 传统实体关系抽取
2. 开放式实体关系抽取


[Yao et al. 2010]  Their approach is based on the following distant supervision
assumption:
- If two entities participate in a relation, all sentences that mention these
two entities express that relation.
- When the knowledge base is external, entities may just appear in the same
sentence because they are related to the same topic, not necessarily because the
sentence is expressing their relations in our training knowledge base. 


- Zeng et al. (2014) propose the use of **word position embeddings** (position features) which help the CNN
by keeping track of how close words are to the target nouns.

 The space of possible model architectures and
hyperparameter settings is vast. Indeed, the simple
CNN architecture we consider requires, at a minimum,
specifying: input word vector representations;
filter region size(s); the number of feature
maps; the activation function(s); the pooling strategy;
and regularization terms (dropout/l2).

- Following
Collobert and Weston (2008), we can then effectively
treat the sentence matrix as an ‘image’, and
perform convolution on it via linear filters.[A Sensitivity Analysis of (and Practitioners’ Guide to) Convolutional
Neural Networks for Sentence Classification]