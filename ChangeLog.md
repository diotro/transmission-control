## 2013-09-13 ##
  * 添加“法语”语言包，感谢Amaury Aubry
  * Add "French" language pack

### 移动UI ###
  * 修复种子列表操作完成时，不能取消选择的BUG；
  * 修复当前语言包中未翻译的内容不能显示的BUG；
  * 添加种子列表删除功能；
  * 添加显示种子列表已选中的种子数量；

### Mobile UI ###
  * Add "Remove torrent" feature
  * Add shows the number of torrent has been selected
  * Fix some bug

## 2013-09-09 ##
  * 修复 en.js 中 lang 对象写成 defaultLang 的BUG

### 桌面UI ###
  * 添加扩展功能按钮；
  * 添加“数据目录自动匹配”功能，可以简单的进行目录匹配
  * 优化系统调用对话框方式，将原来每个创建对话框的代码统一为调用通用函数来创建对话框；
  * 修复参数设置时，无法修改“加密方式”的BUG；
  * 修复检测移动设备时脚本拼写错误；
  * 修改页面布局，将其他UI按钮移动到右上方；

### 移动UI ###
  * 修改页面框架结构，添加右边导航条；
  * 添加“种子增加”功能；
  * 添加是否自动刷新功能控制；
  * 修改种子列表操作方式，当选中时，不刷新列表；
  * 增加“原版UI”切换连接；
  * jQuery 移动基础库升级为 1.9.1，移动框架升级为 1.3.2；

### Desktop UI ###
  * Add "Automatically matches data directory"
  * Fix some bug

### Mobile UI ###
  * Add "Navigation"
  * Add "Add torrent" feature
  * Add "Auto reload" switch
  * Fix some bug

## 2013-08-30 ##
  * 修复上传种子文件完成时，没有自动关闭窗口的BUG ([issue 49](https://code.google.com/p/transmission-control/issues/detail?id=49))；
  * 修改原来设置RPC路径的方式；
  * 删除种子提示对话框从每次从服务器读到改为只读取一次模板数据；
  * 添加 Brazilian Portuguese 葡萄牙语（巴西） 语言包，感谢 Dudu Maroja
  * 添加荷兰语语言包，感谢Alwin Hummels；

  * Fix some bug

## 2013-07-31 ##
  * 添加队列功能；
  * 在种子变更目录功能中添加“完成后重新校验”选项；
  * 修复删除种子时，列表无法刷新的BUG；
  * 修复RPC版本在15以上，无法显示空间大小的BUG；
  * 修复多次删除、添加种子时，导致显示不正常的BUG；

  * Add Queue
  * Fix RPC version 15(or higher) can not display free space bug
  * Fix some bug

## 2013-07-18 ##
  * 参数设置增加“blocklist”更新功能；
  * 添加默认语言本地保存参数配置；
  * 种子上传时，添加按钮等待状态图标；
  * 调整配置窗口的时段限速的设置；
  * 更新种子详情加载方式，文件列表、服务器列表、用户列表不重新清空刷新，而改为更新的方式；
  * 将语言设置移到“参数设置”里；
  * 将版本号调整到“状态栏”显示；

  * Add update "blocklist" button
  * "Language Settings" has been adjusted to the "Config Dialog"
  * Fix some bug

## 2013-04-23 ##
  * 优化种子列表数据加载方式，仅更新当前有变化的数据，以减少对页面的操作。

  * Optimize torrent list loading mode (see [issue 28](https://code.google.com/p/transmission-control/issues/detail?id=28))

## 2013-04-22 ##
### 增加 Added ###
  * 增加自动检查是否可用的新版本程序
  * 增加是否自动展开种子属性的选项，以便更好的操作
  * 增加语言默认配置，用于其他语言未更新时，程序不会执行错误

  * Automatically check for new program
  * Add "Auto expand attribute" option
  * Add default language configuration

### 修复/更新 Fix/Updated ###
  * 更新种子右键菜单的操作方式，允许在当前行上右击时，直接选中当前行操作
  * 修复种子状态显示方式，未开始下载的种子，不在显示到警告状态中
  * 更新种子状态进度条颜色，修改为和当前状态文本颜色相同

  * Right-click to checked current row (see [issue 25](https://code.google.com/p/transmission-control/issues/detail?id=25) & [issue 27](https://code.google.com/p/transmission-control/issues/detail?id=27))
  * Fix progress bar color display error

## 2013-04-02 ##
### 增加 Added ###
  * 在种子列表添加右键菜单

  * Add ContextMenu to torrent list (see [issue 22](https://code.google.com/p/transmission-control/issues/detail?id=22))

### 修复 Fix ###
  * 修复端口测试时，开放和关闭的错误文字描述
  * 修复RPC 15 获取可用空间大小错误的BUG

  * Fix spelling mistake for "Test Port" (see [issue 23](https://code.google.com/p/transmission-control/issues/detail?id=23))
  * Fix free space size display error for RPC 15 (see [issue 24](https://code.google.com/p/transmission-control/issues/detail?id=24))