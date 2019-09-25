softethervpn
===========================

softethervpn


SoftEther VPN Manual
-----------------

`softethervpn`_


.. _softethervpn: https://www.softether.org/4-docs/1-manual


SoftEther VPN Bridge FAQs
-----------------

关于SoftEther VPN Bridge的使用有以下几个方面的问题需要注意：

* LOG 关闭Log保存选项，包含server或者secureNAT,可以参考 ``3.10 Logging Service``。
* DNS 域名可以动态解析；softether本身提供了动态DNS功能，可以参考 ``Dynamic DNS and NAT Traversal``
* Routing 在 ``10.11 Exploit SecureNAT for Remote Access into Firewall without Any Permission`` 中，SecureNAT会将本机所有流量发往server或者bridge，需要注意这一点。可以参考 ``10.11.5 Using Remote Access``
* Error 可以禁止显示连接错误信息，参考 ``4.4 Making Connection to VPN Server`` 中的 ``4.4.10 Connection Status and Error Message Displays``
* 开机自启动 客户端连接自动启动可以参考 ``4.4 Making Connection to VPN Server`` 中的 ``4.4.19 Startup Connection``
* 关闭自动软件升级
* 关闭自动发送给softether的包，服务端的加密通信中可以设置
* 停止bridge监听 在设置完成后，停止所有监听端口，如果需要则需要在配置文件中修改，并且重启服务。可以参考 ``3.3 VPN Server Administration``中的 ``3.3.7 Configuration File``
* 进程启动关闭 可以使用 net start/stop sevpnbridge 操作，参考 ``5.2 Operating Modes`` 中的 ``5.2.1 Service Modes``
* bridge重连 重连次数和重连间隔设置，参考 ``4.4 Making Connection to VPN Server`` 的 ``4.4.9 Automatic Reconnection Funtion`` 和 ``2.1 VPN Communication Protocol`` 的 ``2.1.3 Communication Efficiency and Stability``。配置文件中变量名为NumRetry和RetryInterval。







