### Bandizip更换图标的方法



首先分享一个自制的图标集。
链接：http![img](https://tb2.bdstatic.com/tb/editor/images/face/i_f18.png?t=20140803)://![img](https://tb2.bdstatic.com/tb/editor/images/face/i_f12.png?t=20140803)pan.![img](https://tb2.bdstatic.com/tb/editor/images/face/i_f27.png?t=20140803)baidu.![img](https://tb2.bdstatic.com/tb/editor/images/face/i_f18.png?t=20140803)com/![img](https://tb2.bdstatic.com/tb/editor/images/face/i_f10.png?t=20140803)s/![img](https://tb2.bdstatic.com/tb/editor/images/face/i_f13.png?t=20140803)1nuGiQ7n
密码：6tv2
效果如下：
![img](https://imgsa.baidu.com/forum/w%3D580%3Bcp%3Dtieba%2C10%2C200%3Bap%3Dbandizip%B0%C9%2C90%2C208/sign=83bc1649a844ad342ebf878fe0996f84/0055c1d4b31c8701b31406422e7f9e2f0608ff9e.jpg)

这个图标集是打包成了一个.iconpack的文件的，然而研究发现这玩意儿的制作很简单，就是把你要用的图标命名成“扩展名.ico”，放一起，前面加个ini文件，之后整个压缩成zip，把扩展名zip改为iconpack，就没了、、、

之后说一下这些图标的一些要求和做法。
一共有17个文件格式，它们（以及它们的意义）分别是：
.001( 这是各种压缩文件分卷的第一卷，所以用比较通用化的图标）
.7z（不多讲）
.alz（一种民间小规模流行的高压缩比文件格式）
.bz2（基于bz2算法的压缩文件）
.cab（Windows使用的，常用于各种软件的安装程序）
.egg（不懂这是个啥、、、）
.gz（不懂）
.iso（不多讲）
.lha（一种很老接近淘汰的压缩格式）
.lzh（一种民间小规模流行的压缩文件格式）
.rar（不多讲）
.tar（tar算法的压缩文件，多用于软件封包）
.tbz（tar族压缩文件）
.tbz2（tar族压缩文件）
.tgz（tar族压缩文件）
.zip（不多讲）
.zipx（zip族的另一种压缩文件，好像有一些新特性？）
然后还有一种叫“.bandizip”，是用于软件自有文件的。
集齐18种图标之后你就可以召唤神龙（划掉）制作你的图标集了。





然后这些图标找到了以后，命名成“扩展名.png”就好。
要求是尺寸不小于256x256，正方形版面。放在一起。

接下来是制作图标文件，以及如果你是从网上找的ico文件，要统一化图标尺寸和位深度。
建议使用一个软件叫Greenfish Icon Editor Pro，这是个免费的软件，到处都能下载。





打开这个软件，Ctrl+H，进入批处理功能。
如图：
![img](https://imgsa.baidu.com/forum/w%3D580%3Bcp%3Dtieba%2C10%2C271%3Bap%3Dbandizip%B0%C9%2C90%2C279/sign=2240bfeed3b44aed594ebeec8327e471/42a7ca0a19d8bc3e156dba6e8b8ba61ea9d345d7.jpg)
首先添加所有图片，设置输出成ico，设置输出目录（不能含有中文，日文韩文彻罗基文emoji也统统不行），然后点按钮打开左边这个框，勾选我勾选的这6个，确定x2，等着。
完成之后你获得了一堆ico文件。

  把这些文件扔进一个统一的目录里，这个目录建议为你这个图标集的名字，比如verygood
在这里新建个文本文档，命名“_desc.ini”（注意变扩展名）变成一个配置设置文件。

打开它，输入：
[GENERAL]
name = 图标集的名字，比如verygood
designer = 设计师名
desc = Copyright(C) 版权人名
注意不要有汉字，不要照搬照抄上面的、、、![img](https://tb2.bdstatic.com/tb/editor/images/face/i_f25.png?t=20140803)
保存。  

  然后这些东西都准备完以后，压缩这个目录，变成zip，像上面说的那样改扩展名为iconpack。
![img](https://imgsa.baidu.com/forum/w%3D580/sign=855b428f9416fdfad86cc6e6848e8cea/4d0128d0f703918f8258846e583d269758eec4ab.jpg)

这东西就能双击打开并安装了：
![img](https://imgsa.baidu.com/forum/w%3D580%3Bcp%3Dtieba%2C10%2C119%3Bap%3Dbandizip%B0%C9%2C90%2C127/sign=8ce57f4abd8f8c54e3d3c5270a124e85/4cf6bd03918fa0ec2b4edda92f9759ee3c6ddbab.jpg)

安装完以后应该就已经用上了。  



如果要是没生效、进入控制面板→默认程序→设置默认程序。
![img](https://imgsa.baidu.com/forum/w%3D580%3Bcp%3Dtieba%2C10%2C309%3Bap%3Dbandizip%B0%C9%2C90%2C317/sign=9cab8143982397ddd679980c69b9d1c7/97270090f603738d50e4b486ba1bb051f919ec8b.jpg)
点一下上图中的按钮刷新一下图标缓存就好。



分享个能找到很多图标的网站：
[http://www.easyicon.net/](http://jump2.bdimg.com/safecheck/index?url=x+Z5mMbGPAvyQjgFIr6pyWzzAAz4SLyH+EvlC4YlYSOHh7A3lpev3vbDPBc9W3W7fmQ6z/4guxKUJuVYYURJr5qLgoLgLPHnSmgfeVXWIHlT0sjgIIm+zjA8Zu4mdgY0)



如果要换回原来的图标，这里有原带图标集：
h踢踢劈冒号斜杠斜杠盘点白堵点抗母斜杠s斜杠1eS5NXM6
密码是t0c9
