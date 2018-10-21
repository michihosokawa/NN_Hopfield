# NN_Hopfield

## 概要
[ホップフィールドネットワーク](https://en.wikipedia.org/wiki/Hopfield_network)に基づいた[N-Queen](https://ja.wikipedia.org/wiki/%E3%82%A8%E3%82%A4%E3%83%88%E3%83%BB%E3%82%AF%E3%82%A4%E3%83%BC%E3%83%B3#n-%E3%82%AF%E3%82%A4%E3%83%BC%E3%83%B3)の解法  

主眼は、N-Queenの解を求めることではなく、相互結合型ニューラルネットワークを使うことにある。  
したがって、N-Queenの解を求めるだけであれば、様々な工夫ができるが、それはあえて行わず、エネルギーの減衰を素直に実装した。

