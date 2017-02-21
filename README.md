# weexpack 操作相关
## android 相关
### weexpack 创建项目

``` bash
$ weexpack create projectname
```
生成目录：
![](http://7xr1vo.com1.z0.glb.clouddn.com/314ED92C-277B-4BA1-BCC4-68CD392F9027.png)

### 进入项目，安装npm

``` bash
$ cd projectname 
$ npm install
```

### 添加运行平台的应用模板（android/ios）

``` bash
$ weexpack platform add android/ios
```
移除也可以：
``` bash
$ weexpack platform move android/ios
```

添加 android 应用模板：
![](http://7xr1vo.com1.z0.glb.clouddn.com/F80C160D-1A29-438F-B750-2C755D5B53CA.png)

也可以查看已添加的应用模板

``` bash
$ weexpack platform list
```
此处我只安装了Android：
![](http://7xr1vo.com1.z0.glb.clouddn.com/356792C8-F399-4265-819F-E8DB46174D55.png)

### 运行app

``` bash
$ weexpack run android
```
gradle 开始 build，并打包，随后会安装至手机
![](http://7xr1vo.com1.z0.glb.clouddn.com/89932233-3AF7-4E41-ADC9-06A45D00C161.png)


### 显示效果
![](http://7xr1vo.com1.z0.glb.clouddn.com/device-2017-02-21-214737.png)

## web平台

``` bash
$ weexpack build web
$ weexpack run web
```
会自动打开浏览器

## 其他
可参照：
https://www.npmjs.com/package/weexpack
https://github.com/dodola/WeexOne
