# AdbTool

## 基础配置

1. 点击Select adb按钮，在打开文件窗口选中本地的adb.exe
2. 在Package Name文本框中输入要调试的包名
3. 连上手机，在左上角的设备选择中选中要调试的手机

## 安装

1. 在URL中输入安装包本地或网络下载路径。例如http://www.aaa.com/1.apk
2. 点击Install

## 调试Lua上传(Lua Upload) 需配合https://github.com/yuyang158/Unity-Extend

1. 在Lua Root Path中输入客户端Lua跟路径。例如：C:\Svn\AA\Lua
2. 点击Apply
3. 在出现的树形结构中选中需要上传调试的文件或文件夹，再右键点击。选择Upload即可

## 日志查看 (Log View)

## 截图

## 安装IPA(IPA Install)

1. 需要安装Python3.6以上版本
2. 安装pip3 install -U "tidevice[openssl]"


## 依赖
1. [tidevice](https://github.com/alibaba/taobao-iphone-device)
2. [madb](https://github.com/quamotion/madb) [LICENSE](https://github.com/quamotion/madb/blob/master/LICENSE)
