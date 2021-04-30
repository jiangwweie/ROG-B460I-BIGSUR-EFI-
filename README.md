
# i7 10700-ROG-B460I-UHD630 for macOS BigSur（11.1-11.2.1）

## 硬件配置

| 硬件      | 型号                                              |
| --------- | ------------------------------------------------- |
| CPU       | i7 10700                                          |
| 主板      | Asus ROG Strix B460-i                             |
| 内存      | 阿斯加特（Asgard）16GB 3000频率 DDR4 * 2          |
| 固态      | 铠侠（Kioxia）RC10 500GB SSD ,西数黑盘SN750 250GB |
| 显示器    | AOC Q24P2C 23.8英寸2K                             |
| 电源      | 益横450W 1u电源                                   |
| 散热      | AXP90                                             |
| 机箱      | 六水 loli1s铝合金机箱                             |
| 线材      | 显示器附带DP线                                    |
| 网卡&蓝牙 | BCM943602CS                                       |

## BIOS设置：

- CFGLock=>Disabled
- VT-d=>Disabled
- 大于4G地址空间解码=>Enabled
- DVMTPre-Allocated=>128M
- Systemtime and Alarm Source =>Legacy RTC
- SATA模式选择 =>AHCI 必须设置
- legacyUSB支持 =>Enabled
- XHCIHand-off =>Enabled
- 快速启动 =>Disabled
- 开启CSM =>Disabled
- 安全启动状态 =>关闭
- 操作系统类型 =>其他操作系统
- 另外在BIOS设置中，cpu选项下注意开启英特尔虚拟化技术,否则mac下面启动docker会报错

## 工作情况

- 板载有线网卡
-  板载声卡
-  核显
-  USB
-  Wi-Fi
-  Bluetooth
-  CPU温度
-  AirDrop(隔空投递)
-  Handoff(接力)
-  睡眠 唤醒 关机 重启

## 跑分
-  R20 多核最高4880，温度90+，功耗满载150W，4.6GHz


