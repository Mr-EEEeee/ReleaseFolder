# ReleaseFolder
right click a folder,create an option to release the folder

由于有时解压文件或安装文件的路径设置冗余，在电脑中添加此功能键一步删除重复层的文件夹，简化操作。

预览：

![image](https://github.com/Mr-EEEeee/ReleaseFolder/assets/82107297/b9be3bcf-86c7-46f1-a605-808859745c85)


功能
---
对文件夹单击右键，出现MoveContentsToParent选项，点击后将内层所有文件夹移至当前目录，如果源文件夹已空则将其删除，否则保留源文件夹。

具体应用场景及演示
---
![image](https://github.com/Mr-EEEeee/ReleaseFolder/assets/82107297/4644f599-535b-4a0b-8c56-16449747dd2c)
![image](https://github.com/Mr-EEEeee/ReleaseFolder/assets/82107297/f944eec5-d2d7-444f-8b35-0d7fea9020cf)
![image](https://github.com/Mr-EEEeee/ReleaseFolder/assets/82107297/66995b9d-7e62-48d8-ab1c-b321c0e37db0)
![image](https://github.com/Mr-EEEeee/ReleaseFolder/assets/82107297/aa1d26ad-2f1a-4250-a99a-6c4c2bd582ce)

其中点击释放文件夹后移出的文件夹在当前目录最底下，刷新后回到排列位置，而源文件因为为空所以自动删除。



自定义
---
在注册表编辑器中的“计算机\HKEY_CLASSES_ROOT\Directory\shell\”路径下自行重命名命令选项。

![image](https://github.com/Mr-EEEeee/ReleaseFolder/assets/82107297/c090753e-7dcd-4334-8596-185088e93244)
