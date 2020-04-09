EFI for Dell OptiPlex 9020 Mini Tower at macOS catalina(10.15.4), base on clover 5070

![系统信息](https://github.com/Cheers0606/EFI-for-dell-OptiPlex-7040/blob/master/systemInfo.png)


# 硬件信息
+ 处理器              英特尔 Core i7-6700 @ 3.40GHz 四核
+ 主板                戴尔 0Y7WYT ( 100 Series/C230 Series 芯片组 Family - A146 )
+ 显卡                AMD Radeon R5 340X ( 戴尔 )
+ 内存                16 GB ( 十铨 DDR4 2133MHz / 海力士 DDR4 2133MHz )
+ 主硬盘              西数 WDC WD10EZEX-75WN4A0 ( 1 TB / 7200 转/分 )
+ 显示器              飞利浦 PHLC184 PHL 247E9Q ( 24 英寸  )
+ 光驱                PLDS DVD+-RW DU-8A5LH DVD刻录机
+ 声卡                瑞昱  @ 英特尔 High Definition Audio 控制器
+ 网卡                英特尔 Ethernet Connection  I219-LM / 戴尔

配置详情看鲁大师的报告吧

# work
+ 核显（hd4600）
+ 网卡
+ 声卡（ALC255，使用AppleALC驱动，layoutId为11）
+ 传感器
+ ...

# not work
+ 独显 R5 340x（还没弄，好像10.15已经不支持驱动了，目前屏蔽掉）
