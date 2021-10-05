# LS_BMP180

                    BMP180气压传感器
BMP180主要特点
压力范围：3001100hPa（海拔9000米-500米）
电源电压：1.8V3.6V（VDDA），1.62V3.6V（VDDD） VIN需要5V
LCC8封装：无铅陶瓷载体封装（LCC）
低功耗：5μA，在标准模式
高精度：低功耗模式下，分辨率为0.06hPa（0.5米）
高线性模式下，分辨率为0.03hPa（0.25米）
含温度输出
I2C接口
温度补偿
无铅，符合RoHS规范
MSL 1反应时间：7.5ms
待机电流：0.1μA
无需外部时钟电路
BMP180技术数据
压力范围300……1100 hPa
均方根噪声中表达压力0.06 hPa typ。(超低功耗模式)
0.02 hPa typ。(超高分辨率模式)
均方根噪声中表达高度0.5 m,typ。(超低功耗模式)
0.17米,typ。(超高分辨率模式)
相对精度的压力
VDD = 3.3 v 950……1050 hPa / hPa±0.12
@ 25°C / m±1.0
700年……900 hPa / hPa±0.12
25…40°C / m±1.0
绝对精度
p = 300…1100 hpa
(温度= 0…+ 65°C,VDD = 3.3。-4.0 V)压力:……+ 2.0 hPa
温度:±1°C,typ。
平均电流消耗(1 Hz刷新率数据)
峰值电流3μA典型(超低功耗模式)
32μA,典型的(高级模式)
650μA,典型的
待机电流1.62……3.6 V
电源电压vddio 1.62……3.6 V
电源电压vdd 1.8……3.6 V
操作温度。
范围全面准确”40…+ 85°C
0…+ 65°C
conv压力。5毫秒,典型的(标准模式)
I2C传输速率3.4 MHz,马克斯。
BMP180典型应用
GPS精准导航（航位推算，上下桥检测等）
室内室外导航
休闲、体育和医疗健康等监测
天气预报
垂直速度指示（上升/下沉速度）
风扇功率控制
体育设备，如高度剖面
BMP180气压模块是一款高精度、小体积、低能耗的压力传感器，可以应用在移动设备中，它的性能卓越，绝对精度最低可以达到0.03hPa，并且耗电极低，只有3μA。BMP180采用强大的8-pin陶瓷无引线芯片承载（LCC）超薄封装，可以通过I2C总线直接与各种微处理器相连。
模块接线方式
1.先连接芯片与单片机（通过I2C接口），按照如下方式连接
5V—VIN
GND–GND
A5—SCL
A4—SDA
2.然后UNO通过usb与PC电脑连接
3.运行上面的代码

驱动及软件下载：
1：安装CH34X串口驱动
2：安装Arduino IDE软件：
Windows版：https://downloads.arduino.cc/arduino-1.8.16-windows.exe
Mac版：https://downloads.arduino.cc/arduino-1.8.16-macosx.zip
Linux 64位：https://downloads.arduino.cc/arduino-1.8.16-linux64.tar.xz
Linux 64位M1芯片：https://downloads.arduino.cc/arduino-1.8.16-linuxaarch64.tar.xz
Linux 32位：https://downloads.arduino.cc/arduino-1.8.16-linux32.tar.xz
Linux 32位M1芯片：https://downloads.arduino.cc/arduino-1.8.16-linuxarm.tar.xz
Windows zip file：https://downloads.arduino.cc/arduino-1.8.16-windows.zip
不用付钱直接下载即可
Arduino 1.9 beta：https://www.arduino.cc/en/Main/OldSoftwareReleases#1.9.x
