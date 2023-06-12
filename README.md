## WIFI 破解器

基于 python，使用 pywifi 包完成对 wifi 的连接、扫描等操作，使用 pyqt 完成 gui 的开发。  
使用方式：

### 1 纯代码方式

eazy_code.py  
直接运行，替换其中的密码文件即可不断尝试破解。

### 2 GUI 程序

ui_tool
执行`python run_mainWindow.py`，会打开一个 gui 程序供选择

### 3 exe 程序

需要先使用 pyinstaller 打包 python 程序，我这里也有打包好的，公众号【走神研究所】，发送“wifi 破解”获取百度网盘链接

pip install PyQt5-tools -i https://pypi.douban.com/simple
pip install comtypes -i https://pypi.douban.com/simple
Pyinstaller -F ui_tool/run_mainWindow.py
