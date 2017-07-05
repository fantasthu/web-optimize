# script中defer和async的区别
- ``<script src="test.js"></script>``
- 如果没有defer 和 async关键字,浏览器会立即加载并执行
- ``<script defer src="test.js"></script>``
- 有defer,加载后续文档元素的过程将和script.js的加载并行加载(异步),但是script.js的执行要在所有元素解析完成之后,DOMContentLoaded事件触发之前完成