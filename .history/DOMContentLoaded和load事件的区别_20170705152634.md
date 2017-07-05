# 区别
- load 是等待dom节点且dom节点中的资源全部加载完毕之后架子啊
- DOMContentLoaded 是dom节点加载完毕之后就开始执行
# DOMContentLoaded 受defer和async的影响
- 是defer则需等待defer执行结束之后再触发DOMContentLoaded,期中包含html文档解析,CSSOM 构建完毕
- 是async则html构建解析完成之后就可以触发DOMContentLoaded,不需要等待async脚本执行,样式表加载等