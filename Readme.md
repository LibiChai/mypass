# Mypss 

### 一个简单的跨平台文本加密工具

#### 说明
    调用aes加密算法对输入的文本进行加密，加密后的文本可以复制粘贴到任意地方进行保存。只需要记住加密key即可。
    适用于加密各类数字虚拟币的提醒词，密钥；网站登录密码；需要加密的记事本等内容
    
#### 使用方法

使用 ```go build``` 编译代码后执行一下指令即可
```ssh
    ./mypass -e content key //使用key加密content
    ./mypass -d content key //使用key解密content
```
####下载

点击[https://github.com/LibiChai/mypass/releases](下载)各个平台编译好的二进制版本

#### 注意

加密完成后最好解密测试下确定是否加密成功。确保密文正确。

