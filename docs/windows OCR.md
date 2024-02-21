我们大幅升级了内置OCR，现在识别效果已经接近火山、腾讯和百度等第三方OCR引擎，远好于老版本内置OCR。需要注意的是，如果您使用Windows版本进行内置OCR翻译文档，则系统需不低于Windows10并安装对应语言包。

## 第一种方法[相对麻烦点]

1. 按`Windows+R`组合键,打开“`运行`”对话框：输入`regedit`，回车或确定。
2. 依次以下顺序找到键值System：
> HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Policies\System
3. 右键“EnableLUA” 选“修改”，把值改成0，确定。
4. 然后重启一下系统对注册表进行刷新。

## 第二种方法[比较快捷]

1. 在桌面右键新建一个`txt`文本文件
2. 打开`txt`文件，复制下面的文字到新建的`txt`文件中，然后保存：
    ```
    Windows Registry Editor Version 5.00
    [HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Policies\System]
    "EnableLUA"=dword:00000000 
    ```
2. 把这个文件名的后缀`txt`改名为`reg`，比如文件名改成“Win10不能拖拽文件的解决方案.reg”。
3. 双击此修改后的文件，确定导入注册表。
4. 然后重启一下系统对注册表进行刷新。

## 第三种方法[更为方便]

1. 直接点击下载 [Win10不能拖拽文件的解决方案.reg](https://fanyi.qukaa.com/win10不能直接拖拽文件的解决方案.reg) 文件。
2. 双击此下载后的文件，确定导入注册表。
3. 然后重启一下系统对注册表进行刷新。





