# AR-unity-install

## unity 软件安装步骤

一. 准备相应的软件。如图

![one](https://github.com/NFUNM056/AR-unity-install/blob/master/1.png "第一张")


二. 首先按照顺序安装以下安装包与资源包
- UnitySetup64-5.6.2f1
- UnityStandardAssetsSetup-5.6.2f1
- UnitySetup-Android-Support-for-Editor-5.6.2f1.exe
- 安装步骤较为简单，一直是下一步下一步等，时间也较少
- 如下图

![two](https://github.com/NFUNM056/AR-unity-install/blob/master/2.png "第二张")


三. 安装JAVA开放平台
- 安装包： jdk-8u144-windows-i586_8.0.1440.1
- 在安装时记得安装放置位置。
- 安装完成后设置环境变量
- 如何环境变量？
1. 右击“我的电脑”后点击属性，在控制面板中找到“高级系统设置”，后点击环境变量。（如图1）
2. 点击新建可增加环境变量，后添加内容为，变量名"JAVA_HOME"，变量值f:jdk（即JDK的安装路径）（如图2）
3. 编辑变量名"Path"，在原变量值的最后面加上 %JAVA_HOME%\bin之后点击确定。（如图3）
![three](https://github.com/NFUNM056/AR-unity-install/blob/master/3.png "第三张")

![four](https://github.com/NFUNM056/AR-unity-install/blob/master/4.png "第四张")


![five](https://github.com/NFUNM056/AR-unity-install/blob/master/5.png "第五张")


四.验证是否成功安装JAVA
1. 在我的电脑的搜索框中输入“CMD”后，输入Java-version，出现如图所示即为安装成功

![six](https://github.com/NFUNM056/AR-unity-install/blob/master/6.png "第六张")

五.安装安装sdk开发包
- 安装包：android-sdk_r24.4.1-windows
- 安装时需要更新安装包，可能需要的时间比较长。

![seven](https://github.com/NFUNM056/AR-unity-install/blob/master/7.png "第七张")

六. 配置Unity3d的Android运行环境
- 打开unity软件，在浏览框上找到edit-->Preferences
- 点击Browse，选择路径文件夹，jdk地址：d:\ jdk（你jdk安装的位置），sdk选对应的你的电脑所在的位置

![eight](https://github.com/NFUNM056/AR-unity-install/blob/master/8.png "第八张")

七. 设置安装完成。




