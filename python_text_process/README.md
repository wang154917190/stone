案例来源于GitHub上《Python数据预处理实战》一书的代码：https://github.com/bainingchao/PyDataPreprocessing	<br>
chapter4、chapter5、chapter6主要侧重于文本数据预处理，主要包括：	<br>
1、word、pdf文本使用win32com包转化为txt。	<br>
2、循环遍历文件夹中的文件与使用yield生成器遍历文件夹中的文件（生成器速度快、占用内存小）——> FileRead.py。	<br>
3、使用正则表达式处理文本——> REdealText.py。	<br>
4、处理HTML爬取文本。	<br>
5、文本去除停用词	<br>
6、文本切词加载自定义词典	<br>
7、根据词性提取文本相关词	<br>
8、计算文本词频（NLTK与Counter）	<br>
9、HanLP的使用（加载相应的Java包）	<br>
10、计算文本的Tfidf值（使用sklearn 与 gensim分别实现，但是使用sklearn能返回每个文本的词向量，而gensim暂时不能返回）	<br>
11、实际项目：30w文本语料的清洗	<br>
    复旦新闻语料下载链接: https://pan.baidu.com/s/1U3CtXRl-2mH24PNEzTcy8w 提取码: bxtj 	<br>