# 区别
- load 是等待dom节点且dom节点中的资源全部加载完毕之后架子啊
- DOMContentLoaded 是dom节点加载完毕之后就开始执行
# DOMContentLoaded 受defer和async的影响
- script标签中加入了defer和async之后, DOMContentLoaded的执行事件不会受影响