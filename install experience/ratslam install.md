# cmake
## ATTENTION  
> `find_package`在查找包的时候如果不指定版本，如果计算机中存在不同版本的`package`，会具有不确定性，故加上版本号，减少错误。  
> 如果已经安装了该文件，`cmake` 的 `find_package`查找不到该包，将该包的`config.cmake`目录添加进宏定义`-D`或直接引入`include( $ENV{OpenCV3_DIR}/OpenCVConfig.cmake )`
