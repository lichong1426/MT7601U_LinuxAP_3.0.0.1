基于MT7601U_LinuxAP_3.0.0.1_20130802源码修改，适配内核5.4.0

编译并安装加载
```
sudo make
sudo make install
sudo modprobe mt7601Uap
```

卸载
```
sudo rmmod mt7601Uap
sudo make uninstall
sudo clean
```