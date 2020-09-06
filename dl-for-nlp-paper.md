# 深度学习下的自然语言处理推荐阅读
------------
（点击题目直达论文链接）

## Tutorials
### NLP课程
- Stanford cs224n：Natural Language Processing with Deep Learning
    - 课程主页：http://web.stanford.edu/class/cs224n/index.html#schedule
    - 课程视频：https://www.youtube.com/playlist?list=PLoROMvodv4rOhcuXMZkNm7j3fVwBBY42z
### 深度学习&神经网络基础知识

深度学习教程：

- 李宏毅：http://speech.ee.ntu.edu.tw/~tlkagk/courses.html
- 邱锡鹏：https://nndl.github.io/ 

神经网络

- 理解LSTM：http://colah.github.io/posts/2015-08-Understanding-LSTMs/
- 理解Transformer：
    - http://nlp.seas.harvard.edu/2018/04/03/attention.html
    - http://jalammar.github.io/illustrated-transformer/

## Language Models

- [A Neural Probabilistic Language Model](http://www.jmlr.org/papers/volume3/bengio03a/bengio03a.pdf)
- [A Scalable Hierarchical Distributed Language Model](http://www.cs.toronto.edu/~fritz/absps/andriytree.pdf)
- [Recurrent neural network based language model](https://www.researchgate.net/publication/221489926_Recurrent_neural_network_based_language_model) 
- [Recurrent Neural Network Regularization](https://arxiv.org/abs/1409.2329)
- GPT
- ELMo
- BERT
- XLNet
- RoBERTa

## 分布式表示(词向量)

- [Efficient Estimation of Word Representations in Vector Space](https://arxiv.org/abs/1301.3781)
- [Distributed Representations of Words and Phrases and their Compositionality](https://arxiv.org/abs/1310.4546)
- [How to Generate a Good Word Embedding?](https://arxiv.org/abs/1507.05523)
- 推荐读物：
    - [Word2vec中的数学原理详解](http://blog.csdn.net/itplus/article/details/37969519)
    - [Deep Learning in NLP （一）词向量和语言模型](http://licstar.net/archives/328#s23)


## Seq2Seq框架

- [Sequence to Sequence Learning with Neural Networks](https://papers.nips.cc/paper/5346-sequence-to-sequence-learning-with-neural-networks.pdf)
- [Learning Phrase Representations using RNN Encoder-Decoder for Statistical Machine Translation](https://arxiv.org/pdf/1406.1078.pdf)
- [Neural Machine Translation by Jointly Learning to Align and Translate](https://arxiv.org/abs/1409.0473)

## Neural Machine Translation


- 华为诺亚方舟实验室神经机器翻译“三部曲”：
    - [Modeling Coverage for Neural Machine Translation](https://arxiv.org/abs/1601.04811)
        - 覆盖率（Coverage）机制：通过记录哪些词已经被翻译了，鼓励系统翻译未被翻译的词。这个方法可以显著减少遗漏翻译和过度翻译的错误数量。
    - [Context Gates for Neural Machine Translation](https://arxiv.org/abs/1608.06043) 
        - 上下文门（Context Gate）方法：在译文生成过程中，实词和虚词对原文信息的依赖是不一样的。该方法通过自动控制原文信息参与生成不同类型译文词的程度，使原文信息更有序、更完整地传输到译文中。
   - [Neural Machine Translation with Reconstruction](https://arxiv.org/abs/1611.01874)
        - 基于重构（Reconstruction）的忠实度指标：以译文重新翻译成原文的程度来衡量译文的忠实度。通过将重构指标引入训练过程，系统可生成更忠于原文的译文。 

