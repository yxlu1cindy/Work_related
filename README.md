# Work_related

1. Anaconda 装python3.6，兼容性会更好
2. Python,需要安装Microsoft Visual C++ 14.0 is required的包:Scrapy,pyltp
3. 设置环境变量：计算机->右键属性->高级系统设置->环境变量
4. nlp 相关的包：nltk,jieba,thulac,pyltp,gensim。pyltp支持中文断句，gensim可训中文的word2vec
5. pycharm最好一个项目一个虚拟环境
6. Windows平台处理doc可以用pywin32,非Windows平台可以用comtypes(速度会慢一点)--然而linux/unix并不能用，要转的话参照https://vinta.ws/code/converting-doc-to-pdf-using-unoconv-and-python.html
7. Pandoc 提供格式转换，但是转pdf要用latex，操作繁琐。。。，不支持.doc
8. Tensorflow 一些例子 ： https://nbviewer.jupyter.org/github/aymericdamien/TensorFlow-Examples/blob/master/notebooks/2_BasicModels/word2vec.ipynb
9. Python内置库:https://www.liaoxuefeng.com/wiki/897692888725344/973805065315456
  - Collections:Counter;deque->类似队列，可双边插入;OrderedDict-永远保持插入顺序
  - hashlib：MD5摘要—>加密
  - openrator: itemgetter，按顺序取
  - itertool: product('abc', [1, 2])   # 多个循环器集合的笛卡尔积。相当于嵌套循环;permutations('abc', 2)   # 从'abcd'中挑选两个元素，比如ab, bc, ... 将所有结果排序，返回为新的循环器。注意，上面的组合分顺序，即ab, ba都返回。;combinations('abc', 2)   # 从'abcd'中挑选两个元素，比如ab, bc, ... 将所有结果排序，返回为新的循环器。注意，上面的组合不分顺序，即ab, ba的话，只返回一个ab。;combinations_with_replacement('abc', 2) # 与上面类似，但允许两次选出的元素重复。即多了aa, bb, cc
10. 封装时可以用一些魔法方法 https://www.cnblogs.com/seablog/p/7173107.html
11. http://data.stats.gov.cn/[统计局数据]
12. from pyglmnet import GLM  => 可以调用GroupLasso =>Group原因：多个dummy variable一起进入/删减出模型
13. pd.get_dummys()  -- dummy variable; df.columns.difference(['col1']) -- 选除col1以外的所有列
