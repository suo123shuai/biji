# 在 IDEA 中配置一个工程启动多个实例
## 步骤一
点击 Run -> Edit Configurations...
![](https://note.youdao.com/yws/public/resource/64aa017b48e3414b16c7fada51cb5c51/xmlnote/5737200DE71A42189FEBC926ECB69FAA/172)
## 步骤二
选择需要启动多实例的项目并去掉 Single instance only 前面的勾
![](https://note.youdao.com/yws/public/resource/64aa017b48e3414b16c7fada51cb5c51/xmlnote/71A8FD6813C24859B3D97D70DB2D815D/174)
## 步骤三
通过修改 application.yml 配置文件的 server.port 的端口，启动多个实例，需要多个端口，分别进行启动即可。