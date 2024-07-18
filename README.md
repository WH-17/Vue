使用Vue2完成的初学项目TodoMVC，这是打包后的dist文件。


本地运行方法

1 确认已经安装了Node.js，可以在命令行中执行以下命令，查看版本号。如果还未安装，则需要先安装Node.js。

node -v

2 安装http-server模块。在命令行中执行以下命令：

npm install -g http-server

3 进入到dist目录。在命令行中执行以下命令（/path/dist是自己项目中dist目录所在的路径）：

cd /path/dist

4 启动http-server。在命令行中执行以下命令：

http-server

5 此时，在命令行中会输出完成的URL，在浏览器输入即可访问

6 注意，http-server 模块的默认端口是8080，如果已经被占用，可以使用以下命令来指定端口。此时，服务器会在8081端口上启动。

​​​​​​​http-server -p 8081

