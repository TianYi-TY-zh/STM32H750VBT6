小孩子不懂事画着玩的 属于是人菜瘾大 画的乱 布局不合理

不知道为什么工程名字改不了 可能我铸币没找到 所以工程名字是F22

六爷上次说的东西已经不记得了（悲）

主控：STM32H750VBT6/H7430VIT6

//其实想做个飞控

外设：

 	DBUS * 1 
 	CAN1 * 4 
	CAN2 * 4 
	USART * 3(含DBUS) 
	PWM * 4 
	XT30电源输入 
	SWD接口 
	OLED IIC 
	ICM20948 IIC 
	预留IIC * 2 
	RST键 
	LED(RGB)各一个 
	USB-C 
	按键*2 
	3.3V输出 
	TF * 1 

实现：

	STM32电路 
	电源 
	BUCK电路 
	CAN模块 
	USB模块 
	传感器模块 
	TF卡 
 
附加功能：

	防反接 
