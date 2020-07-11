# X79-Catalina-ALC662
Hackintosh Clover EFI For X79 ALC662 in MacOS Catalina

华南X79 CLOVER 10.15 配置
HUANAN X79 Clover EFI 10.15

修改了声卡配置 因为cheneyveron大佬的声卡配置似乎在10.15用不了 所以修改了配置文件  使其可以正常使用 但是只能使用后面输出

我的配置 （复制一下大佬的）
	•	主板: 华南金牌 X79 V2.46 ATX
	•	CPU：E5-2660
	•	显卡：RX580
	•	声卡：ALC662 
	•	网卡：Rtl8100/8600

Config我直接使用的amd-plist 如果是n卡的话直接在clover configurator把注入id改为17 或者12 16重启就行

AppleAlc Layout表测试 ALC662
5 无声
7 无声
11 无声
12 有声 只能使用前面
13 无声
15 无声
16 有声 只能使用后面
17 有声 只能使用后面
