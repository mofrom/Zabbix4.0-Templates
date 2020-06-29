# Zabbix 模板

> zabbix 4.0



# Template Linux OS



* 该模板下的监控项

  * system info
    * Host Boot Time
    * Host Local Time
    * Host Name
    * Maximum Number Of Processes
    * System Info
    * System Uptime
  * Services
    * SSH Service is running
  * Memory
    * Available Memory
    * Free Swap Space
    * Total Memory
    * Total Swap Space
  * Logged in users
    * Number Of Logged In Users
  * Disk info
    * Disk Free
    * Disk Free %
    * Disk Total
  * CPU
    * CPU IO wait time
    * CPU Load Time



# Template Windows OS

* OS

  * HostCheck
    * 状态监控
  * 系统主机名
  * 线程数

* Network

  * Windows Traffic In
    * 网络传入监控
  * Windows Traffic Out
    * 网络传出监控
  * Memory
    * Memory Used Percent
    * 总交换空间
    * 总内存
    * 有效内存
    * 有效虚拟内存
  * Host Status
    * HostCheck
      * 主机状态监控
    * Disk Info
      * C盘空闲量
        * 磁盘剩余空间监控
      * C盘空限量占比
      * D盘空闲量
        * 磁盘剩余空间监控
      * D盘空限量占比
      * E盘空闲量
        * 磁盘剩余空间监控
      * E盘空限量占比
    * CPU
      * CPU占用率
      * 处理器负荷1min
      * 处理器负荷15min



# Template Printer SNMP



## Canon Printer

> 适用于 Canon iR-ADV C5560/3530/3520等彩色打印机

* Color Print

  * 碳粉余量，有监控项

* Counter

  * 打印机的计数器

* Host Status

  * 主机状态监控，有监控项

* Info

  * 打印机的SN，型号，IP地址



  ## KONICA Printer

> 测试打印机：KONICA MINOLTA bizhub C221

* Color Print
  * 打印机碳粉余量。有监控项
* Counter
  * 计数器
* Info
  * 主机型号



## Ricoh Printer



* Color Print

  * 碳粉余量

* Counter

  * 计数器

* 其他

  * 监控的内容全的1p




# Template Net Huawei VRP SNMPv2

> 测试机型：
>
> ​	HuaWei S7703 核心交换机



# SendMailScript

> Python的邮件脚本
