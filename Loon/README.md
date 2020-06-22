1. 从URL下载配置文件

   <https://raw.githubusercontent.com/lhldegit/LRules/master/Loon/LLoon123.conf>

2. 继续编辑，将配置文本`[Remote Proxy]`中的`https://www.example.com/example1.txt`替换为您的订阅链接

3. 将配置文本`[Remote Filter]`中的两个`关键词`（各两处）替换为您所需的

4. 打开Loon的MITM开关 - 证书管理 - 安装CA证书；然后到系统设置 - 已下载描述文件 - 安装；最后系统设置 - 通用 - 关于本机 - 证书信任设置，信任刚才安装的证书

