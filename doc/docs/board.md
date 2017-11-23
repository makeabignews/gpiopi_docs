###树梅派

分为rs和e14两个版本，rs是英国版的供应商，e14是中国厂商购买的e洛联授权而生产的。为了方便理解，可以把e14当作中国版的，把rs当作英国版的。两个版本没有显著的区别，甚至中国版的有些比英国版的芯片还高级。

![raspberrypi](images/board/raspberrypi/raspberrypi.png)

raspbian = raspberry pi + debian

[下载 桌面版 RASPBIAN STRETCH WITH DESKTOP](https://downloads.raspberrypi.org/raspbian_latest)

[下载 终端版 RASPBIAN STRETCH LITE](https://downloads.raspberrypi.org/raspbian_lite_latest)

```
sudo dd if=2017-09-07-raspbian-stretch.img of=/dev/sdb
```

sdb需要用fdisk -l列出磁盘确认，不要弄错了。

ubuntu-mate

[ubuntu-mate-16.04](https://ubuntu-mate.org/raspberry-pi/ubuntu-mate-16.04.2-desktop-armhf-raspberry-pi.img.xz)

```
sudo apt-get install gddrescue xz-utils
unxz ubuntu-mate-16.04.2-desktop-armhf-raspberry-pi.img.xz
sudo ddrescue -D --force ubuntu-mate-16.04.2-desktop-armhf-raspberry-pi.img /dev/sdx
```

GPIO

nodegpio

[https://www.npmjs.com/package/nodegpio](https://www.npmjs.com/package/nodegpio)

nodejs、shell、python

[https://github.com/makeabignews/gpiopi](https://github.com/makeabignews/gpiopi)

###android things

[https://developer.android.com/things/preview/download.html](https://developer.android.com/things/preview/download.html)

###c-sky

![c-sky](images/board/c-sky/TB2KMiwXX6.F1JjSZFpXXcZjXXa_!!2771760402.jpg)

c-sky是国产自主指令集的CPU，能使用python开发。

[taobao](https://item.taobao.com/item.htm?spm=a230r.1.14.16.59a45c7e8Swe89&id=556322544984&ns=1&abbucket=1#detail)

[https://c-sky.github.io](https://c-sky.github.io)

###香橙派

![](images/board/orangepi/TB2Yu4JgxhmpuFjSZFyXXcLdFXa_!!734650578.jpg)

[legacy](https://dl.armbian.com/orangepizero/Ubuntu_xenial_default.7z)
[mainline](https://dl.armbian.com/orangepizero/Ubuntu_xenial_next.7z)

root/1234

###香蕉派

有些小贵的香蕉派，是高端品牌，配置也很高。

###NodeMCU

esp8266低成本的开发板，广泛用于IOT。

###micro：bit

面向小朋友的开发板，可以使用python和block积木语言来编程。

![](images/board/microbit/TB2uYAiaoyfF1Jjy0FbXXXSupXa-63891318.jpg_400x400.jpg_.webp)

![](images/board/microbit/TB2xtDAaHdvt1JjSZFuXXXG0FXa_!!740676578.jpg)

[microbit官方网站](http://www.microbit.org/)

[microbit课程](http://www.microbit.org/en/2017-03-07-javascript-block-resources/)

[microbitPython课程](http://microbit-micropython.readthedocs.io/en/latest/tutorials/hello.html)

[microbit项目](https://makecode.microbit.org/projects)

##其他开发板

###Udoo quad

![Udoo quad](images/board/other/udoo.png)

###NanoPi Duo

![NanoPi Duo](images/board/other/nanopiduo.png)

###Le Potato

![Le Potato](images/board/other/lepotato.png)

###Odroid HC1

![Odroid HC1](images/board/other/odroidhc1.png)

###Tinkerboard

![Tinkerboard](images/board/other/tinkerboard.png)

###SoPine64

![SoPine64](images/board/other/sopine64.png)

###MiQi

![MiQi](images/board/other/miqi.png)

###pcDuino2
![pcDuino2](images/board/other/pcduino2.png)