# 基于批处理的快速设置电脑IP地址程序
台式机，笔记本，Windows系统，一般网卡通用  
  
1.使用前，要把 set NAME="本地连接 2" 双引号内部改为需要被修改IP地址的网卡名称，修改保存后再运行  
2.在文本中可以修改为喜好的IP地址/掩码/网关：IP1~IP4等等  
3.本程序不能超过9个可选项，所以不要设置IP5  
4.少数情况下，若出现选择菜单头部显示IP/掩码/网关刷新慢，或显示不出的情况，请在对应操作增加延时的时长：  
如：choice /t 5 /d y /n >nul  
增加里面的数字5，直到头部IP信息显示跟得上刷新速度即可！  
  
注意：每次修改程序后要使修改生效，必须保存退出后再运行！！！  
注意：每次修改程序后要使修改生效，必须保存退出后再运行！！！  
注意：每次修改程序后要使修改生效，必须保存退出后再运行！！！  
