#### 笔记

##### embedding
embedding对权重形状是shape(vocab_size, dim), vocab_size这个维度是索引
输入的张量x的值为vocab_size范围的取值，而其对应的embedding后的值，则为该权重的索引值对应的dim值。
