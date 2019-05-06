#### 没有账号的网友，请先前往 https://www.vultr.com 注册

### 步骤如下：

#### 1. 获取启动脚本
&nbsp;&nbsp; 下载 [onekey_ssr.sh](https://raw.githubusercontent.com/gfw-breaker/gadgets/master/onekey_ssr.sh)

#### 2. 添加启动脚本
按下图所示添加 startup script。可按个人需要修改脚本中ss配置参数, 其中ss配置参数含义如下：

|参数| 含义 |
|---|---|
|ss_port    |ss服务器端口 |
|ss_password  |   ss密码 |
|ss_method   |    加密方法 |
|ss_protocol |     协议  |
|ss_obfs     |     混淆  |

[<img src="../blob/master/resources/vultr/01.png?raw=true" width="600px"/>](../blob/master/resources/vultr/01.png?raw=true)
--
[<img src="../blob/master/resources/vultr/02.png?raw=true" width="600px"/>](../blob/master/resources/vultr/02.png?raw=true) 

#### 3. 部署VPS
1. 点击右上角的“+”号图标，进入创建VPS页面
2. 选择 Server Location。 推荐使用 Tokyo，延时小
3. 选择 Server Type，使用 CentOS 6 x64
4. 选择 Server Size，最低配置 $5/mo 即可
5. 选择 Startup Script，点击刚创建的脚本 onekey-ssr
6. 填写 Server Hostname & Label，点击 Deploy Now <br/>

[<img src="../blob/master/resources/vultr/03.png?raw=true" width="600px"/>](../blob/master/resources/vultr/03.png?raw=true)
--
[<img src="../blob/master/resources/vultr/04.png?raw=true" width="600px"/>](../blob/master/resources/vultr/04.png?raw=true) 

#### 4. 检查网络
1. 等待，服务器创建大概需要2~5分钟
2. 创建完成后，进入VPS列表页面，复制VPS的IP地址，用浏览器打开
3. 若能打开页面，说明服务器可用；若5分钟内打不开，请删掉VPS，重新尝试创建新的VPS <br/>

[<img src="../blob/master/resources/vultr/05.png?raw=true" width="600px"/>](../blob/master/resources/vultr/05.png?raw=true)
--
[<img src="../blob/master/resources/vultr/06.png?raw=true" width="600px"/>](../blob/master/resources/vultr/06.png?raw=true) 

