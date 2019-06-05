# 新手入坑之系统安装
第一次接触树莓派是在加入实验室的时候，当时还是有点懵的，完全不知到是什么，从那是开始，逐渐接触了树莓派。  
现在看肯定是简单的了，才接触的时候还是碰到了好多问题的。
## 给树莓派烧制系统镜像
### 配件
- 树莓派3b  
树莓派充电接口为Micro USB接口，输出电压为5V/2A，在宿舍或者外面没电的地方，充电宝也是可以供电的。
- 内存卡  
树莓派本身不带硬盘的，在树莓派上有个SD卡插口可以用SD卡来当作树莓派的硬盘。SD卡最小容量为8GB。
- 显示器    
树莓派（3b）的显示器连接口为HDMI接口，可以直接用HDMI线来连接显示器，显示器不支持HDMI的也可以使用VGA-HDMI转接线来连接。  
树莓派一般都用ssh来远程连接操作，一般烧制系统完成后打开ssh就可以在PC端进行连接了。~~（之前看过教程说烧制完成后可以在启动盘里加一个ssh的文件来开启ssh,
不过我没有尝试过。）~~
- 其余配件
鼠标，键盘等设备就不多说了。
### 系统烧制
把SD卡接到电脑上。
#### 下载系统
 [树莓派官网](https://www.raspberrypi.org)  
 [官网下载链接](https://www.raspberrypi.org/downloads/raspbian/)
#### 下载烧录工具
[WIn32DIsklmager](https://pan.baidu.com/s/12Gq_xQKLaxvxUzjFtdYU1g"百度网盘")(提取码：2g4w)    
![win](https://github.com/liytgy/raspberry/blob/master/%E5%85%A5%E5%9D%911%E2%80%94%E2%80%94%E7%B3%BB%E7%BB%9F%E5%AE%89%E8%A3%85/win32.PNG)
#### 格式化SD卡
#### 烧制系统
## 上电开机
