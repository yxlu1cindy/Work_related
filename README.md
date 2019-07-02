# Work_related

1. Anaconda 装python3.6，兼容性会更好
2. Python,需要安装Microsoft Visual C++ 14.0 is required的包:Scrapy,pyltp
3. 设置环境变量：计算机->右键属性->高级系统设置->环境变量
4. nlp 相关的包：nltk,jieba,thulac,pyltp,gensim。pyltp支持中文断句，gensim可训中文的word2vec
5. pycharm最好一个项目一个虚拟环境
6. Windows平台处理doc可以用pywin32,非Windows平台可以用comtypes(速度会慢一点)--然而linux/unix并不能用，要转的话参照https://vinta.ws/code/converting-doc-to-pdf-using-unoconv-and-python.html
7. Pandoc 提供格式转换，但是转pdf要用latex，操作繁琐。。。，不支持.doc
8. Tensorflow 一些例子 ： https://nbviewer.jupyter.org/github/aymericdamien/TensorFlow-Examples/blob/master/notebooks/2_BasicModels/word2vec.ipynb
