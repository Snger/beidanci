# beidanci
    背单词神器，可以在命令行里背单词，伪装成工作：），内涵考研词汇本这个
    脚本是本人在考MBA期间为了快速熟悉单词而开发的。希望能够给其他人带来帮助，所以在github上分享

#功能特点
    程序是使用js开发，在nodejs命令行中可以执行。
    原理是载入词库文本，进行解析，分析出词库中的单词和解释，分析原理是，如果遇到一行中顶格书写的词汇即认为是单词
    如果是后面用空格分割的内容则认为是描述，支持换行，换行的内容如果前面有空格或者制表符，则不会解析成单词，而解析成内容
    学习英语过程中最终要的一个环节是背单词，而背单词过程中质量的好坏很重要的因素就是是否专注，逐个背诵出词考意，是提高专注度的很号的方法。
    另外一个方法就是重复率，考验过程中有幸结识北京有名的英语名师指导，在此感谢太奇的邵宁，马洁等诸多恩师。他们经常提醒我们背单词最重要的就是你和它的见面次数，
    次数多了，自然就记住了。所以该软件的特点也是如此，核心思想是把词库先自如到内存中。你把会的单词扔掉，那么逐渐内存中的不认识的词汇越来越少。见面频率也越来越高
    等什么时候，使用者把所有词汇都熟悉了，词库清空，则会对词库中的单词有一个深层次的记忆。
    另外还有一个特点是词库就是一个文本文件，很容易编写和切割，可以根据使用者的需求，自己编写词库，也可以决定词库的大小，这样一开始背起来也不会干到压力那么大，利用这个特点也可以自己编写其他要背诵的东西，不一定非得是单词。

