## 1. 自动安装 (Linux) ##
  * 用SSH工具以管理员的身份登录到 Transmission 的安装服务器；
  * 执行以下命令：
```
cd /
wget https://transmission-control.googlecode.com/files/tr-control-easy-install.sh
sh tr-control-easy-install.sh
```
  * 安装脚本会根据目录列表自动查找 Transmission Web Interface 目录，如果有匹配的目录，则自动安装最新版本的内容到该目录，安装成功后就可以用浏览器重新打开web界面来操作了，如果没有显示为新的内容，你可以强制刷新页面；
  * 如果没有匹配的目录，则提示目录不存在，此时你需要按手工的方式来安装；

## 2. 手动安装 (Windows) ##
  * 下载并安装[WinSCP](http://winscp.net/eng/download.php)
  * 下载最新的 [Transmission Web Control 压缩包](https://transmission-control.googlecode.com/svn/resouces/transmission-control-full.tar.gz)
  * 运行 WinSCP，新建一个 SCP 连接并连接至Transmission服务器（用户名和密码为linux的管理员用户名和密码）
  * 找到 Transmission Web Interface 所在的目录（如：/usr/local/transmission/share/transmission/web/）
  * 将该目录下的 index.html 改名为 index.original.html
  * 然后返回到上级目录（如：/usr/local/transmission/share/transmission/），将之前下载的压缩包上传至该目录
  * 执行解压缩，如下图所示：
![https://lh4.googleusercontent.com/-rZuClBaqFvo/UjfBYMJH3YI/AAAAAAAAAOo/OdPtYxX3DFA/w529-h561-no/%25E6%259C%25AA%25E5%2591%25BD%25E5%2590%258D.jpg](https://lh4.googleusercontent.com/-rZuClBaqFvo/UjfBYMJH3YI/AAAAAAAAAOo/OdPtYxX3DFA/w529-h561-no/%25E6%259C%25AA%25E5%2591%25BD%25E5%2590%258D.jpg)
  * 如果没有意外，安装至此已经完成，重新刷新 Web 页面就可以看到新内容


---

## 1. Automatic Installation (Linux) ##
  * Login to Transmission server;
  * Execute the following command:
```
cd /
wget https://transmission-control.googlecode.com/files/tr-control-easy-install.sh
sh tr-control-easy-install.sh
```
  * This script is based on [the list](https://transmission-control.googlecode.com/svn/resouces/checkfolders.lst) automatically find Transmission Web Interface directory, if a match is found directory, the script will automatically download and install the latest content to the Web Interface directory;
  * If there is no matching directory, you will be prompted installation fails. Please try to manually install

## 2. Manual Installation (Windows) ##
  * Download and install [WinSCP](http://winscp.net/eng/download.php)
  * Download [Transmission  Web Control compressed package](https://transmission-control.googlecode.com/svn/resouces/transmission-control-full.tar.gz)
  * Run WinSCP and connection to Transmission server
  * Find Transmission web interface directory, like this: /usr/local/transmission/share/transmission/web/
  * Rename "index.html" to "index.original.html"
  * Upload compressed package to this parent directory (If you Transmission web interface directory is "/usr/local/transmission/share/transmission/web/", you need to upload the compressed package to "/usr/local/transmission/share/transmission/" directory)
  * UnTar this compressed package to the current directory:
![https://lh4.googleusercontent.com/-rZuClBaqFvo/UjfBYMJH3YI/AAAAAAAAAOo/OdPtYxX3DFA/w529-h561-no/%25E6%259C%25AA%25E5%2591%25BD%25E5%2590%258D.jpg](https://lh4.googleusercontent.com/-rZuClBaqFvo/UjfBYMJH3YI/AAAAAAAAAOo/OdPtYxX3DFA/w529-h561-no/%25E6%259C%25AA%25E5%2591%25BD%25E5%2590%258D.jpg)