## 任务目的

在这一题中，你将学会导入外部模型。

## 任务描述

* 学习《Three.js 入门指南》第 7 章外部模型；
* 加载不同格式的小车模型（在网上找资源），需要导入模型的材质纹理；
* 如果感兴趣，可以在 [blender](href="https://www.blender.org/") 中创建一个简单的小车模型，了解从建模到导入模型的整个流程。



## 问题解决

* 多个坐标系问题 [(译)三维空间中的几种坐标系](http://www.cnblogs.com/silent-stranger/p/6307372.html)
    Threejs中采用了多个坐标系，{世界坐标系，物体坐标系}，这两个是确定存在的，至于相机坐标系有没有，不能确定。AxisHelper显示的是世界坐标系，当对某一物体做旋转、移动变换时，依据的是物体自身的坐标系即物体坐标系
* camera.lookAt 方法无效问题 [ThreeJS camera.lookAt() has no effect, is there something I'm doing wrong?](https://stackoverflow.com/questions/10325095/threejs-camera-lookat-has-no-effect-is-there-something-im-doing-wrong)




