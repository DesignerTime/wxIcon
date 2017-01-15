# wxIcon
微信小程序-图标颜色自定义

![mahua](img/sp20170115_123112.jpg)
##使用
####在wxss文件中引入样式
```css
<!-- 引入样式 -->
@import "/wxIcon/wxIcon.wxss";
```
####wxml
```xml
<!-- 引入模板文件 -->
<import src="/wxIcon/wxIcon.wxml" />

<!-- 填入相关属性即可使用组件 -->
<template is="wxIcon" data="{{width:'24px',height:'24px',url:'ic_thumb_up_black_24dp.png',color:'#CC3366'}}" />
```