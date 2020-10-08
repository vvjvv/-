##实验一<br/>
##计192王静薇2019310201<br/>
##实验目的<br/>
1、掌握类的设计<br/>
2、写出程序并初步学会调试<br/>
3、利用github平台写实验报告<br/>

##实验内容<br/>
用类描述计算机中CPU的速度和硬盘的容量。要求Java应用程序有4个类，名字分别是PC、CPU、HardDisk 和Test，其中Test是主类。<br/>
其中，CPU类要求getSpeed()返回speed的值，要求setSpeed(int m)方法将参数m的值赋值给speed; HardDisk类要求getAmount()返回amount的值，要求setAmount(int m)方法将参数m的值赋值给amount;PC类要
求setCPU(CPU c)将参数c的值赋值给cpu，要求setHardDisk (HardDisk h)方法将参数h的值赋值给HD，要求show()方法能显示cpu的速度和硬盘的容量。<br/>
##实验过程<br/>

1、先建立四个类，PC、CPU、HardDisk、Test。<br/>
2、在类中建立公共类。<br/>
3、定义变量CPU的速度和价格、硬盘的容量。<br/>

##核心方法<br/>
1、方法1<br/>
···<br/>
CPU cpu=new CPU()；<br/>
HardDisk disk=new HardDisk();<br/>
PC pc=new PC();<br/>
···<br/>
2、方法2<br/>
···<br/>
cpu.setSpeed(2200);<br/>
disk.setAmount(200);<br/>
cpu.setPrice(5000);<br/>
···<br/>
3、方法3<br/>
···<br/>
void show() {<br/>
System.out.println("CPU的速度为"+ cpu.getSpeed());<br/>
System.out.println("硬盘的容量为"+ HD .getAmount());<br/>
System.out.println("CPU的价格为"+ cpu.getPrice());<br/>
}<br/>
···<br/>

##实验结果<br/>
CPU的速度为2200<br/>
硬盘的容量为200<br/>
CPU的价格为5000<br/>

##实验感想<br/>
在做这次实验的时候，我遇到了不少问题。出现问题后，我积极的向同学们请教，在他们的耐心讲解下，最终完成了此次实验。通过这次实验，我学会了类的设计，并且学会了如何在github平台上写实验报告。令我受
益匪浅。<br/>
