# Chromebox3CN65-Sequoia-EFI
ASUS Chromebox3CN65 Sequoia EFI文件

# 机器情况

- 型号: Asus Chromebox3 CN65
- 处理器: Intel Core i7-8550U
-  显卡: Intel UHD 620
- 内存: 32GB DDR4 (自行升级)
- 存储: NVMe SSD (自行升级，或者原厂 SATA SSD)
- 声卡: 不知道什么型号
-  无线网卡: 博通 BCM94360CS2 （苹果拆机网卡）
-  引导器: OpenCore 1.0.2
-  macOS 版本: Sequoia 15.0.1

# 已实现功能

- [x] Intel UHD 620 显卡 (支持硬件加速)      
- [x] WiFi 和蓝牙、隔空投送
- [x]  USB 接口 (Type-A 和 Type-C)
- [x] HDMI 输出（也可以使用全功能Type-C连接显 器）
- [x] 亮度控制
- [x] 有线以太网
- [x] macOS 电源管理 (包括 CPU 电源状态)
 
 # 不工作/存在问题
 
- [ ] SD 卡读卡器
- [ ] 3.5MM耳机接口（因为不知道声卡型号，未驱动）
- [ ] 睡眠后无法唤醒
# 注意事项
- 1、博通 BCM94360CS2虽然是苹果拆机网卡，在Ventura以前是免驱的，但自从Sonoma后，需要另行驱动，可参照以下文章
https://heipg.cn/tutorial/patch-brcm-wireless-card-macos-sonoma.html
