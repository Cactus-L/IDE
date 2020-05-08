## 安装idea编辑器
- 官网下载mac版本，我的是2.3 https://www.jetbrains.com/idea/download/#section=mac
- 利用补丁将idea 2019.2及以下版本激活到2089年了，而且还“不用改hosts”
## 注册破解包
下载破解文件 https://github.com/cody-gao/article/tree/master/idea
包括jetbrains-agent.jar 和激活码.txt
## 步骤
1. 启动idea，在启动后的欢迎界面，点击Configure菜单，选择Edit Custom VM Options,在最后添加jetbrains-agent.jar的绝对路径
-javaagent:/Users/didi/Downloads/idea/jetbrains-agent.jar
2. 进入help/Register...，选择Activation code模式，输入激活码.txt中的激活码进行激活，点击ok保存
3. 重新启动,点击Register...进入后发现注册日期到2089年，完成破解。
4. 备注：若之前安装过，可能或导致失败
> 在Activation code模式下，在输入激活码之前，先有 Remove License按钮则点击删除之前的code。
若提示 Key is invalid,重新卸载idea后再安装，重新安装若无法打开idea，可以双击 /Applications/IntelliJ IDEA.app/Contents/MacOS/idea，查看错误，一般是之前导入的jetbrains-agent.jar无效导致，删除这项配置即可。
## 说明
此编辑器仅供学习使用，正常使用请使用正版授权。
