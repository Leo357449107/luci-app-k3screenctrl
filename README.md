# luci-app-k3screenctrl
根据 [K3 openwrt18.06.02](https://www.right.com.cn/forum/thread-466672-1-1.html) 固件的LuCi文件而来

Leo357449107: 添加了心知天气公钥签名验证的支持，在填写了公钥的情况下使用签名验证方式认证（V3）。 TODO: 心知天气API v4

个人编译的时候搭配的是:

[Leo357449107/k3screenctrl](https://github.com/Leo357449107/k3screenctrl)

[lwz322/k3screenctrl_build](https://github.com/lwz322/k3screenctrl_build)

# From Hill-98
## 简介 

本软件包是 [k3screenctrl](https://github.com/updateing/k3screenctrl) 的 Luci 控制界面，方便用户控制 k3screenctrl 和一些附加功能。  

使用本界面推荐配合 [k3screenctrl_sh](https://github.com/Hill-98/k3screenctrl_sh) 优化脚本使用。

本人第一次写 Luci 界面，不是很完美，欢迎指正不足。

## 已实现功能

亮屏时间  
刷新间隔  
隐藏无线密码  
显示 CPU 温度  
设备自定义
