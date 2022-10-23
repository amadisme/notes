记录hyperledger fabric学习过程中的踩坑
======================
talk is cheap show me the code

# 环境搭建
基本流程
1. git拉下来fabric的代码后
2. 下载对应版本的ca和二进制文件压缩包，具体连接可以进入bootstrap.sh文件查看
3. 进入fabric-samples文件解压以上两个压缩包
4. 修改Bootstrap.sh文件，将ca和二进制文件下载由true修改为false
5. 执行./Bootstrap.sh下载docker images


避坑点
1. 自己下载两个压缩包，不要用命令下载。因为官方的release里面删除了很多东西，不能通过命令自动下载二进制文件和ca文件
2. 下载好的.tar.gz压缩包要在fabric-samples的文件夹中解压，这样才能在他的bin目录下生成二进制文件

something changes

/test new changes

19点13分的update

second changes !note!