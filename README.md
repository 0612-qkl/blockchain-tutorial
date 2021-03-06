# 区块链技术学习前言导读
> 作者:彭劲(Jim.Peng) 时间:2018-10-16 14:18

非常开心能来到火链区块链学院为大家分享相关我对区块链技术学习心得的文章。正当我准备这些教材的时候,我感觉非常有必要跟大家谈谈时下中国我们学习区块链的一些教程资料,目前在国内区块链技术如火如荼,各种教程也遍布互联网,国内很多教程都拥有着很多非常花哨的概念和错误的定义,这并不利于初学者的入门,不过这种状况也符合国情。我非常负责任地告诉大家,站在程序开发人员的角度对区块链进行学习和理解这才是真正正确的学习方向,从技术层面出发去理解区块链技术遇不到太多花哨的概念,并能从真正意义上明白区块链技术底层的原理和应用的方向,对市面上一些说法和理论做到真正的去伪存真。

## 关于比特币的教材
BitCoin是由中本聪使用c++编写的一个数字货币系统,俗称比特币系统。因为比特币系统是区块链技术中的一个应用,很多技术人员学习区块链都是先从比特币系统学习进行入门的。为了便于理解,不同的程序语言方向的技术人员使用不同的语言根据中本聪比特币系统的源码机制从原理上实现了不同语言版本的比特币系统。所以你看到有Java,Python,Golang等各种版本的比特币系统。

> ***注意：你需要明白的一点是只有中本聪的c++版本的比特币系统才是真正的比特币系统,其余任何语言的版本都是在模拟实现比特币系统,目的是使用自己擅长的语言去理解比特币的机制和原理***

我们需要学习比特币系统的机制和原理选择使用的是Golang技术,模拟实现比特币机制的过程又被称为"公链开发"。最为权威的参考教程都来自一个外国开发者Ivan Kuznetsov所编写的7篇文章。

[Ivan Kuznetsov的Blog](https://jeiwan.cc/)中的7篇文章如下所示:

* Building Blockchain in Go. Part 1: Basic Prototype [区块链的基础原型]
* Building Blockchain in Go. Part 2: Proof-of-Work [工作量证明]
* Building Blockchain in Go. Part 3: Persistence and CLI [持久化存储和客户端命令行]]
* Building Blockchain in Go. Part 4: Transactions1 [交易1-实现UTXO交易的机制]
* Building Blockchain in Go. Part 5: Addresses [比特币地址和数字签名]   
* Building Blockchain in Go. Part 6: Transactions2 [交易2-优化UTXO交易]
* Building Blockchain in Go. Part 7: NetWork  [模拟比特币网络]

**以上资料如果你希望查看中文翻译版文档和对应的源代码你可以**[点击这里](https://github.com/pengjim520golang/blockchain-tutorial/tree/master/%E6%AF%94%E7%89%B9%E5%B8%81%E6%9D%83%E5%A8%81%E6%95%99%E6%9D%90/Golang%E5%AE%9E%E7%8E%B0%E6%AF%94%E7%89%B9%E5%B8%81/)

> ***注意:以上文档中的画图和代码存在一定的小问题,但已经能够很好地解释了比特币的机制和原理了,理解了上述的代码再去看其他相关比特币理论书籍你的理解就更深了。***

**在国内我个人认为值得你去看的只有2本关于区块链理论的外文翻译书籍**

* 《精通比特币》,这是世界上的权威,中文版来自于机器翻译,不过我从中纠正和去掉了翻译的错误的地方[点击这里查看](https://github.com/pengjim520golang/blockchain-tutorial/tree/master/%E6%AF%94%E7%89%B9%E5%B8%81%E6%9D%83%E5%A8%81%E6%95%99%E6%9D%90/%E7%B2%BE%E9%80%9A%E6%AF%94%E7%89%B9%E5%B8%81)
* 《区块链技术驱动金融》,京东上的售价为59.30RMB([京东购买地址](https://item.jd.com/12014042.html))