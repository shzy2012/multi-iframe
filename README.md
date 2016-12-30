# multi-iframe
包含有 iframe 的页面的加载顺序：
初始化index.html-->iframe--iframe onload-->index.html onload

所以 iframe 会阻塞主页面的onload事件
