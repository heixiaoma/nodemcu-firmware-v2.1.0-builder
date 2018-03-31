# 可直接编译的nodemcu-firmware v2.1.0 

|必要步骤|可选步骤|
|-------------|-------------|
|清理工程，执行`./nodemcu make clean`| 合并二进制文件，执行`./nodemcu combine <输出文件名>`|
|编译，执行`./nodemcu make`|

###### 注意
编译出的二进制文件在nodemcu-firmware/bin目录中，文件名对应烧录地址。  
如果未自定义合并输出文件名，则目录nodemcu-firmware/bin中的nodemcu_firmware.bin为合并后文件，烧录地址为0x0。
