### 2.4.7-8
- 修改流量上报接口端口号

### 2.4.6
- 增加节点流量上报功能
- 修正速度统计的bug

### 2.4.5
- 优化调度算法，显著提高下载速度
- 解决不传入opts报错的bug

### 2.4.4
- 修复种子服务器的bug
- 请求http节点接口出错时启用纯WebRTC模式

### 2.4.3
- 修复在qq浏览器和搜狗浏览器等无法兼容的bug

### 2.4.2
- 修复2.4.1运行错误的bug
- 将默认分片大小由1M改成512K

### 2.4.1
- 新增isMSESupported和isWebRTCSupported两个API，去掉isSupported
- 新增“fallback”回调函数


### 2.4.0
- 增加新的API：PearPlayer.isSupported()

### 2.3.10
- 在PearDownloader模块中添加自定义HTML标签功能，具体可参看PearDownloader.js
- 修复一些bug

### 2.3.9
- 修复下载完成后data channel没有关闭的bug
- 优化调度算法