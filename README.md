# Hachintosh-CLEVO-NHSERIES

支持黑苹果 Hackintosh Catalina 10.15.7 / Big Sur 11.0.1 / Catalina10.15.7 无痛升级至 Big Sur 11.0.1
Support Version : Catalina 10.15.7 / Big Sur 11.0.1 ; Update to Big Sur 11.0.1 From Catalina 10.15.7

支持蓝天（CLEVO）模具 ： NH5xRD_RC_RA_RH(Q)/NH70RD_RC_RA_RH(Q)

理论上支持的机型：

* 神舟 Z7-CT5NA
* 神舟 Z7-CT7NA
* 神舟 Z7-CT7NK
* 神舟 Z8-CT7NA （经过测试支持）
* 神舟 G7-CT7NA
* 神舟 G8-CT7NA
* 神舟 G8-CT7NK

---

基于  [[lyj0309](https://github.com/lyj0309)/**[Hackintosh-CLEVO-H](https://github.com/lyj0309/Hackintosh-CLEVO-H)**] 进行维护
Maintaining and based on [ [lyj0309](https://github.com/lyj0309)/**[Hackintosh-CLEVO-H](https://github.com/lyj0309/Hackintosh-CLEVO-H)**]

---

**注意**：小搞怡情，大搞伤心，强搞灰飞烟灭，请在进行升级前做好备份。

Notice: Remember to BACKUP!

- 引导使用 [OpenCore](https://github.com/acidanthera/OpenCorePkg) 无图形界面；
- 无线网卡完美驱动 Dell Wireless 1820A (可能需要修改 PCI 注册地址)；
- 强烈建议更换三码；
- HDMI 无法使用（独显直接输出）
- 读卡器无法使用 （USB2.0 外置线路）
- MiniDP 完美使用
- Type-c 完美使用
- USB 接口完美使用
- 原机 Intel 无线网卡支持使用 [OpenIntelWireless/itlwm](https://github.com/OpenIntelWireless/itlwm) 进行驱动（需要自行安装）
- 睡眠不完美
- 需要禁用 CFG Lock
- 需要关闭 VT-d
-