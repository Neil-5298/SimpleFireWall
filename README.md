# SimpleFireWall
一个简单的防火墙
第一步：实现网络抓包
  借鉴arkime系统中capture模块的抓包方法
  
第二步：将抓取的网络数据包保存到本地pcap文件中
  借鉴arkime系统中capture模块的数据留存方法
  
第三步：标记每次网络连接的会话(session)信息
  借鉴arkime系统中capture模块的会话解析方法,简单裁剪。将会话信息写入sqlite3数据库。
  
第四步：显示sqlite3数据库中的会话信息
  使用qt来完成展示界面，读取sqlite3数据库信息，可对信息进行过滤、筛选、标记操作

第五步：借鉴iptables和netfilter功能完成简单的防火墙功能
 

  
 
