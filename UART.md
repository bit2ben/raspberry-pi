## raspberry pi 的UART通信
* GPIO中的UART通信引脚
  * 6：GND、8：TX、10:RX。
* 连接USB转TTL设备
  * GND to GND,TX to RX，RX to TX。
* 配置pi系统的UART通信功能
  * 编辑/boot/config.txt文件
  * 加入enable_uart=1(打开uart通信功能）（参考pi官方文档）
* linux系统端用minicom
  * 设置波特率为11520（参考pi官方文档）
* 开机。
