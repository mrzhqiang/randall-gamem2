# MirServer
这是一个【2.5D 传奇服务端】仓库，包括：客户端、引擎、服务端版本。

- 客户端

基于 AppleM2 源码编译的兰达尔登录器，支持单机测试。

- 引擎

基于 AppleM2 源码编译的兰达尔引擎，正在逐渐重构代码。

- 服务端版本

算不上完整版本，但在逐步开发中。

## 快速启动
介绍如何快速开启你的第一个传奇版本。

### 1. 安装数据库

目前依旧使用 DBC 2000 数据库，安装文件位于 ./Tools/ 文件夹下，区分 32 位和 64 位，通常不需要汉化，一直点击【next】就行。

### 2. 创建数据库实例

在你电脑的【控制面板】中打开【BDE Administrator(32 位)】，依次点击【Object】|【New】|【OK】，得到【Databases】下全新的数据库实例。修改实例名字为【randall】，在右侧栏中编辑【PATH】目录指向服务端目录下的数据库源目录，比如【D:\mir-server\MirServer\Mud2\DB】。

### 3. 替换服务端引擎

选择【Engine】文件夹下的最新引擎解压，将解压出来的文件复制到【MirServer】目录下，当询问覆盖时，选择全部覆盖。

### 4. 配置服务端参数（可选）

启动【MirServer】目录下的【GameCenter.exe】文件，切换到【配置向导】子菜单，根据实际情况调整每一步，一共九个步骤，配置完成后点击保存即可。需要注意的是，服务端版本目录，数据库名字，以及 IP 地址，必须保证符合实际情况。如果需要运行多个版本，建议分配不同的端口给每个版本。

### 5. 运行服务端

在以上条件都满足的前提下，点击【开始启动】，等待窗口弹出。

### 6. 解压补丁

找到 ./Tools/ 文件夹下的 【Resource】 压缩文件，解压到【热血传奇】根目录。

### 6. 启动登录器

将【mir2.exe】放到【热血传奇】根目录下，双击启动。


# 声明
本仓库仅供学习交流使用，不得用作任何商业用途。

