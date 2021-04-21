# cloudflareDDNS
群晖和Openert使用cloudflare的DDNS脚本
## 使用方法
分别修改以下参数
### 你的Global API Key
### Cloudflare登录邮箱
### 主域名，即二级域名
### 需解析的子的域名
### 记录类型
其他参数可以不修改，如果有特殊要求，也可能根据参数注释修改
修改完成后上传到群晖或者openwrt的任意目录下面，例如/root
给文件可执行权限：chmod 755 文件名；或者 chmod +x 文件名
测试域名服务商cloudflare是否被墙：ping api.cloudflare.com ，如果能ping同才能正常解析
然后运行脚本：bash 文件名
如果运行成功，再创建一个任务计划定时执行

