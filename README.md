# BeautyCamera
毕设项目《基于Android平台的美颜相机设计与实现》
Adnroid端采用Camera2 API实现自定义相机，实现了拍照、聚焦、控制闪光灯模式、切换前后置摄像头，访问相册等功能。在实现美颜算法方面，使用基于局部均方差的图像去噪算法实现磨皮功能，log曲线美白算法实现美白功能，采用Android NDK开发优化图片处理算法，同时优化处理逻辑，将图片处理时间从5s提升到1s，显著提升效率。



项目美颜算法系列参考 
http://www.cnblogs.com/Imageshop/p/4679065.html
http://www.cnblogs.com/Imageshop/p/3843635.html
