# slide.js
  一套基于jQuery的易用的js轮播图插件,可配置切换动画,间隔时间....
 
### 参数
  $('.banner').slide({
      autoPlay: true,                 //  是否自动播放 默认值false
      fade: "slide",                  //  切换效果 slide(滑动) || fade(渐隐渐现,默认)
      autoPlaySpeed: 3000,            //  自动切换时间间隔,Number类型,单位毫秒.默认值:3000
      dot: true,                      //  Display dot navigation
      dotColor: "#00ff00              //  Support responsive design. May break non-responsive designs
  });
