# 互联网暴露面探测之WEB探测
- 通过Masscan进行全端口扫描
- 通过Httpx对Masscan的端口扫描结果发起请求来发现http服务
- 输出并解析相对人性化的CSV文件
- 将本次探测结果通过邮件发送给指定收件人
- httpx版本为1.1.4,可以用项目内的httpx也能自行下载对应版本httpx


### 完善了个新版本，直接把探测结果推送到企业微信机器人，有空再同步到github上吧
