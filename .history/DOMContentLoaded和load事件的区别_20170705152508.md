# 区别
- load 是等待dom节点且dom节点中的资源全部加载完毕之后架子啊
- DOMContentLoaded 是dom节点加载完毕之后就开始执行
# DOMContentLoaded 受defer和async的影响
- 是defer则需等待defer执行结束之后再出发,期中包含html文档解析,CSSOM 构建完毕
- 是