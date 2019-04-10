# ionic 常用命令行

> 进入项目目录

```
cd ionic-app
```

> 添加对应的框架

```
ionic platform add ios
ionic platform add android
```

> 创建页面

```
ionic g page NewPage
```

> 编译

```
ionic build ios
ionic build android
```

> 模拟器中运行：

```
ionic emulate ios
ionic emulate android
```

> 生成 android apk

```
ionic cordova build android --prod --release -- -- --keystore=/Users/psy/Desktop/android.keystore --alias=android --storePassword=kkkkk09 --password=kkkkk09
```

> 安卓线上调试（打开 chrome）

```
chrome://inspect/#devices
```

> 生成 ICON 和启动页

```
ionic cordova resources
```

# 插件相关

> 新建插件

```
plugman create --name 插件名称 --plugin_id 插件ID（com.xxx.xxx） --plugin_version 插件版本
```

> 新建 package.json 文件

```
npm init
```

> 新建平台

```
plugman platform add --platform_name ios
```

> 删除平台

```
plugman platform remove --platform_name ios
```

> 查看插件列表

```
cordova plugin ls
```

> 删除插件

```
Cordova plugin rm 插件名称（可以根据列表中的名称来）
```
