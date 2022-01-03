# zliao555.github.io


目前我们使用的模板是just-the-docs. 模板在读取markdown文件后会自动生成html。所以更改内容时还是只需更改学校的markdown文件就行

---

飞跃手册的内容都在my-site的文件夹里

我已经把涵东的目录copy到index里了

希望大家做的就是把每个学校都建立一个page。
建立成mit.markdown
然后page的开头都是例如

---

layout: page
title: Massachusetts Institute of Technology (MIT)
permalink: /my-site/mit‘

---

# Massachusetts Institute of Technology

---

需要大家更改的就是permalink. 改成学校相应的缩写就行。比如/mit，uiuc, ucb等

每个page的markdown怎么写其实很简单，请参考mit.markdown. 其他的功能可以自行搜索markdown cheatsheet

大家完成好每个学校的page之后，不用改index.markdown，以免出现需要merge 不同版本的情况。通知我然后我update index就行。


