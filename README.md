# CCAlert

> CocosCreator 一个弹窗插件。

# 前言
> 刚接触 CocosCreator、JavaScript，写了一个游戏的弹窗插件，记录笔记的同时也分享给和我一样在学习道路上的小伙伴。代码规范包括逻辑等都欢迎新老客户提出宝贵意见。

## 效果图
![效果图.gif](http://upload-images.jianshu.io/upload_images/1874013-fa04cc7c848c9a53.gif?imageMogr2/auto-orient/strip)

## 使用方法
> **这里注意：**
> **1.** **Alert** 的 `prefab` 文件一定要放到 **assets/resources** 目录下，因为 **cc.loader.loadRes** 方法加载的需放在 **resources**。
> **2.** **Alert** 的 `js` 文件勾选 `导入为插件的复选框，这样才能全局访问。不勾选的话可以在想使用的地方引用也可。

> **代码使用：**`Alert.show("文字内容", 确定按钮点击回调函数,  true/false(是否显示取消按钮),  动画速度)`。

![QQ20170804-154530.png](http://upload-images.jianshu.io/upload_images/1874013-17c886ee6179def7.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/600)

## 总结
> 欢迎评论吐槽！
