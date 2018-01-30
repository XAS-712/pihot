# pihot
How hot your RPi is? Git clone this and test!

有时候不使用官方的Raspbian，这个情况下原厂的`vcgencmd measure_temp`就不能用了：（

还想看看CPU温度，咋办？

把本仓库`git clone`到你的RPi，然后执行`python3 pihot.py`。
CPU温度会打印到控制台。同时，其他的一些数据（例如RAM、磁盘）也会打印到控制台。

### 啥？你说`python3 pihot.py`太麻烦？？？
执行`echo alias hot=\'python3 ~/pihot/pihot.py\' >> .bashrc`

(前提是你已经把代码仓库放在了用户主目录下面，即`pihot.py`就在`~/pihot/pihot.py`的位置)
