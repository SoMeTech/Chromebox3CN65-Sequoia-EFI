# Chromebox3CN65-Sequoia-EFI
ASUS Chromebox3CN65 Sequoia EFI文件
### 2024-11-15 更新 
系统升级到Sequoia 15.1 (24B83)
# 机器情况

- 型号: Asus Chromebox3 CN65
- 处理器: Intel Core i7-8550U
-  显卡: Intel UHD 620
- 内存: 32GB DDR4 2400mhz(自行升级)
- 存储: NVMe SSD (自行升级，或者原厂 SATA SSD)
- 声卡: 不知道什么型号
-  无线网卡: 博通 BCM94360CS2 （苹果拆机网卡）
-  引导器: OpenCore 1.0.2
-  macOS 版本: Sequoia 15.1 (24B83)

# 已实现功能

- [x] Intel UHD 620 显卡 (支持硬件加速)      
- [x] WiFi 和蓝牙、隔空投送
- [x]  USB 接口 (Type-A 和 Type-C)
- [x] HDMI 输出（也可以使用全功能Type-C连接显示器）
- [x] 亮度控制
- [x] 有线以太网
- [x] macOS 电源管理 (包括 CPU 电源状态)
 
 # 不工作/存在问题
 
- [ ] SD 卡读卡器
- [ ] 3.5mm耳机接口（因为不知道声卡型号，未驱动。目前使用HDMI 输出到显示器的音频信号接音箱；也可以蓝牙等）
- [ ] 睡眠后无法唤醒（此问题还需要大家出主意想办法解决）
# 注意事项
- 1、博通 BCM94360CS2虽然是苹果拆机网卡，在Ventura以前是免驱的，但自从Sonoma后，需要另行驱动，可参考以下文章
https://heipg.cn/tutorial/patch-brcm-wireless-card-macos-sonoma.html
- ** 本EFI已经驱动，无需重复操作
