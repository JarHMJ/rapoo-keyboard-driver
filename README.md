# rapoo-keyboard-driver
Some bugfix for rapoo keyboard where some keys are invalid.

# Quick Usage
Compile the driver module with make, make install and run ./install-rapoo-keyboard-driver.sh.

Job done! Then enjoy typing!

# Notice
After installing new kernel(contains compile and install kernel),
you must reinstall hid-rapoo module again by "make install".

# 个人记录
重新安装时必须先得把之前的make文件清除一下，`git clean -xfd`，然后再执行之前的命令！！
