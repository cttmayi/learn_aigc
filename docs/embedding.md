当前主流的推荐系统中，embedding 无处不在，从一定意义上可以说，把 embedding 做好了，整个推荐系统的一个关键难题就攻克了。因此，本文总结了移动腾讯网推荐系统中的 embedding 技术实践，力图达到娱人娱己的目的。

# 什么是 embedding
embedding 其实就是一种稠密向量的表示形式。在 embedding 大行其道之前 onehot 才是最靓的仔。如果和我们比较熟悉的 oneHot 对比起来理解，顿时会发现 embedding 这个玄里玄乎的概念，实际上 so easy。
直观上看 embedding 相当于是对 oneHot 做了平滑，而 oneHot 相当于是对 embedding 做了 max pooling