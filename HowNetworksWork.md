## chapter2 用电信号传输TCP/IP数据
## chapter3 从网线到网络设备
网卡中的PHY(MAU)模块负责将包转换成电信号，信号通过RJ-45接口进入双绞线。
双绞线，用于减少信号传输中噪声的影响，例如减弱电磁波的影响。在双绞线中，单纯的电信号的传输，直至第一个节点--集线器。
当信号达到集线器之后，会被广播到所有连接在它上面的电路(集线器中的中继电路)。其他设备根据信号中的MAC地址，确认是否需要接受。
网卡可以和集线器连接，集线器之间可以连接，网卡和网卡直接可以连接。基本原理都一致，有MDI直连和MDI-X交叉连接的差异。
