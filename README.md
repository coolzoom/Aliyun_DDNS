# Aliyun_DDNS
<h3>Run with Python2.7</h3>
<h4>贡献者：@AndroidOL</h4>
依赖urllib,aliyunsdkcore，请使用pip安装<br />
利用Aliyun的修改解析记录API写的DDNS脚本<br />
请自行修改程序中的设置变量<br />
<h2>为啥要写这么个玩意</h2>
真相是这样的，我自己搞了台小服务器在家里跑着自动查图书馆的书是否超期等脚本，偶尔也要连上去看看，或者当个bridge使连RDP到台式机，网络环境是动态公网IP，一直用oray的DDNS。可惜这家现在越做越坑，还限制子域名数量，后来发现阿里云是个好东西，于是就有了这个脚本。
<h2>这个玩意怎么玩</h2>
把配置信息写好，把它写进crontab里，五分钟一次。
