# slide.js
## 一套基于jQuery的易用的js轮播图插件,可配置切换动画,间隔时间....
 
### 参数
```
  $('.banner').slide({
      autoPlay: true,                 //  是否自动播放 默认值false  
      fade: "slide",                  //  切换效果 slide(滑动) || fade(渐隐渐现,默认)  
      autoPlaySpeed: 3000,            //  自动切换时间间隔,Number类型,单位毫秒.默认值:3000  
      btn,                            //  是否实现按钮切换功能
      dot: true,                      //  是否实现小圆点逻辑（与图片动态绑定切换）  
      dotColor: "#00ff00              //  你喜欢的小圆点背景颜色
  });
```
