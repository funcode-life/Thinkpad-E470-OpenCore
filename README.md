# 联想ThinkPad E470黑苹果OpenCore文件

因为github上现有的OC文件中ACPI的EC路径为`_SB.PCI0.LPCB.EC`，而自己的机器EC路径为`_SB.PCI0.LPC.EC`，无法显示电池，故自己制作了电池补丁，可完美显示。

## 现有问题

  - 无线网卡无解，需自行更换

  - 睡眠唤醒后，蓝牙可能无法使用，网上白苹果也有相同问题，应该是系统问题，重启`bluetoothd`服务即可

## 测试环境

  - 系统版本（System Version）：MacOS Catalina 10.15.7

  - OC版本（OpenCore Version）：0.6.6

  - 硬件信息（Hardware Info）：

    - CPU：Intel i5 7200U

    - GPU：NVIDIA Geforce 920 + Intel GMA HD 620

    - Audio：Intel HD Audio（Layout ID 15）

    - LAN：RTL8111/8168/8411 Gigabit Ethernet Controller

    - WIFI：QCA9377 802.11ac Wireless Network Adapter

