# 这是由三人小团队合作完成的基于UE4蓝图开发的智慧城市三维可视化平台
## 本人完成的部分：
     1、射线检测来绘制线、面和立方体
     2、跳转视点动态生成布告板（布告板生成在视点范围内，指定公司的信息），离开该视点则销毁该处的布告板
     3、动态修改布告板的文字内容、字体、颜色和大小，设置布告板大小随视口大小而变换
     4、使用cesium for unreal插件将三维倾斜摄影数据导入UE4中
     5、使用Pixel Streaming插件实现前端网页与UE4端的通信
     6、编写JavaScript代码，将UE4中的功能集成到前端网页中
## 说明：demo展示并非项目最终实现效果

### 动态修改布告板字体、文字内容和颜色
https://user-images.githubusercontent.com/90737354/196335309-ae8871d7-c839-4909-9f03-9123905814cd.mp4

### 在指定经纬度高度动态生成布告板，隐藏布告板
https://user-images.githubusercontent.com/90737354/196352636-dd88a26c-f737-4d49-a1f3-47d27ed1cabc.mp4

### 视点漫游、随视点改变生成和销毁布告板
https://user-images.githubusercontent.com/90737354/196363808-21d8e205-d20f-41e5-8780-2ef665acda1b.mp4

### 线面绘制和销毁
https://user-images.githubusercontent.com/90737354/196380876-c448b859-14a1-4a98-9b98-3e28bc2c5758.mp4
