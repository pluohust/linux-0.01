# linux-0.01
已修改好，可在Centos6x上编译通过。

# 在虚拟机上引导
1. make后会生成Image文件，直接用虚拟机引导不了
2. 先用biximage生产一个空虚拟软盘a.img
3. 再用dd命令复制到a.img中
```
dd if=Image of=a.img conv=notrunc
```
直接用如上命令VirtualBox引导不了
