# elasticsearch学习
# 1. 安装es：linux和mac
## 1.1下载：
官网：https://www.elastic.co/downloads/elasticsearch
找到对应版本下载
## 1.2解压
## 1.3启动
进入bin目录，执行elasticsearch脚本
## 1.4验证
访问localhost:9200

# 2.安装head插件
## 2.1下载head插件https://github.com/mobz/elasticsearch-head
## 2.2没有node先安装node https://www.cnblogs.com/wang-yaz/p/10168862.html
## 2.3npm install          //这个不能少
## 2.4npm install -g grunt -cli
## 2.5grunt server  //进入head目录，启动


    SearchResponse searchResponse = client.prepareSearch().setIndices("index_hello")
