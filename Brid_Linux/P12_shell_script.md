# shell脚本

## 12.1 什么是shell脚本

shell编写的过程中主要注意点：

* 命令自上而下，从左向右
* 如何一行的命令太多，可以使用【\ Enter】来扩展到下一行
* 执行shell文件必须具备可读可写权限（rx）
* 直接路径或者相对路径执行shell文件
* 将shell文件写入到变量**PATH**指定的目录`~/bin/`，则可以直接执行shell文件（不加绝对路径或相对路径）

* shell脚本第一行`#！/bin/bash` 称为 shebang 行