# vpn

### file description：
* vpnsetup_centos.sh：bash file, build ss server in form of IPsec/L2TP. After that, we can set vpn in ipad and iphone.
* 

### ipad and iphone setting:
进入设置 -> 通用 -> VPN。
单击 添加VPN配置...。
单击 类型 。选择 L2TP 并返回。
在 描述 字段中输入任意内容。
在 服务器 字段中输入你的 VPN 服务器 IP。
在 帐户 字段中输入你的 VPN 用户名。
在 密码 字段中输入你的 VPN 密码。
在 密钥 字段中输入你的 VPN IPsec PSK。
启用 发送所有流量 选项。
单击右上角的 存储。
启用 VPN 连接。

### reference:
1. CentOS快速搭建一个属于自己的IPsec/L2TP VPN: https://wistbean.github.io/ipsec,l2tp_vpn.html#%E6%90%AD%E5%BB%BAIPsec-L2TP-VPN%E7%9A%84%E5%87%86%E5%A4%87
2. 在服务器上搭建ss：https://github.com/wistbean/vpn
3. 各类ss客户端：https://crifan.github.io/scientific_network_summary/website/server_client_mode/ss_client/
