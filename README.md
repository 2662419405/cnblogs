# 欢迎来到残梦博客园

> 首先声明一点: 样式并不是本人所写,是我个人整合(感觉每个人的博客都喜欢一点,所以自己整合了一下)

* 博客园网址 : ------>  [博客园网址](https://www.cnblogs.com/sunhang32)



## 如果感觉勉强可以看几眼的话,可以按照一起来配置一下

* 首先你要有一个博客园(估计会`github`的都应该知道了)
* 在[博客园](https://www.cnblogs.com)的官网左上角开通博客园
* 博客园的个人配置页面->先申请js权限

![Snipaste_2019-11-13_14-41-38](/img/Snipaste_2019-11-13_14-41-38.png)

* 禁用页面的css样式

![Snipaste_2019-11-13_14-42-25](/img/Snipaste_2019-11-13_14-42-25.png)

* 粘贴一下代码到定制页面css代码中 [css](/css/sh.css)

* 粘贴博客侧面公告代码[侧面html](/html/left.html)

* 粘贴页首代码 [页面html](/html/header.html)

* 粘贴页脚代码 [页脚html](/html/footer.html)

## 功能

* :construction_worker_man: 键盘按下效果

* :apple: 鼠标指针改变
* :tangerine: 导航栏自定义
* :cherries: 恶搞标题
* :banana: 看板娘-猫
* :peach: 音乐-网易云
* :pineapple: 左侧点击弹出
* :watermelon: 页面顶部滚动进度
* :grapes: 点击页面跳动可爱的文字
* :lemon: 评论增加聊天表情
* :tomato: 随笔背景特效
* :pear: 响应式开发
* :book: 网站运行时间
* :shaved_ice: 动态线条背景
* :strawberry: 背景线条特效
* :baby:代码雨

### 电脑效果图展示
![电脑效果图1](/img/show.jpg)
![电脑效果图2](/img/show1.jpg)

### 手机效果图展示

<img src="/img/show2.jpg" height="700px" />



*--------------如果你对你的代码不满意的话,可以接下来自定义设置----------------*

### 下面是DIV定制

* 背景线条特效
```js
<script type="text/javascript"
color="220,220,220" opacity='0.7' zIndex="-2" count="500" src="//cdn.bootcss.com/canvas-nest.js/1.0.0/canvas-nest.min.js">
</script>
//color 颜色
//opacity 透明度
//zIndex 层级(一般为负数)
//count数量
```

* 背景音乐(页面加载会收到影响)
```js
<link rel="stylesheet" href="https://blog-static.cnblogs.com/files/elkyo/APlayer.min.css">
  <div id="player" class="aplayer aplayer-withlist aplayer-fixed" data-id="3025663508" data-server="netease" data-type="playlist" data-order="random" data-fixed="true" data-listfolded="true" data-theme="#2D8CF0"></div>
  <script src="https://blog-static.cnblogs.com/files/elkyo/APlayer.min.js"></script>
  <script src="https://blog-static.cnblogs.com/files/elkyo/Meting.min.js"></script>
// 更改data-id可以改变歌曲  
// 如果想让歌曲在页面加载完播放可以设置
<script>
$(".aplayer-play").click()
</script>
```

* 猫(也是影响页面加载的一个因素)
```js
 <script src="https://eqcn.ajz.miesnfu.com/wp-content/plugins/wp-3d-pony/live2dw/lib/L2Dwidget.min.js"></script>
<script>
      L2Dwidget.init({
          "model": {
              jsonPath: "https://unpkg.com/live2d-widget-model-hijiki/assets/hijiki.model.json",<!--这里改模型，前面后面都要改-->
              "scale": 1
          },
          "display": {
              "position": "left",<!--设置看板娘的上下左右位置-->
              "width": 100,
              "height": 200,
              "hOffset": 70,
              "vOffset": 0
          },
          "mobile": {
              "show": true,
              "scale": 0.5
          },
          "react": {
              "opacityDefault": 0.7,<!--设置透明度-->
              "opacityOnHover": 0.2
          }
      });
window.onload=function(){
       $("#live2dcanvas").attr("style","display:block;position: fixed; opacity: 0.7; left: 70px; bottom: 0px; z-index: 1; pointer-events: none;")
}
```

* 网站运行时间
```html
<!-- 网站运行时间 -->
<p style="text-align:center;"><span id="timeDate">载入天数...</span><span id="times">载入时分秒...</span></p>
<script>
    var now = new Date(); 
    function createtime() { 
        var grt= new Date("11/06/2019 17:38:00");//在此处修改你的建站时间
        now.setTime(now.getTime()+250); 
        days = (now - grt ) / 1000 / 60 / 60 / 24; dnum = Math.floor(days); 
        hours = (now - grt ) / 1000 / 60 / 60 - (24 * dnum); hnum = Math.floor(hours); 
        if(String(hnum).length ==1 ){hnum = "0" + hnum;} minutes = (now - grt ) / 1000 /60 - (24 * 60 * dnum) - (60 * hnum); 
        mnum = Math.floor(minutes); if(String(mnum).length ==1 ){mnum = "0" + mnum;} 
        seconds = (now - grt ) / 1000 - (24 * 60 * 60 * dnum) - (60 * 60 * hnum) - (60 * mnum); 
        snum = Math.round(seconds); if(String(snum).length ==1 ){snum = "0" + snum;} 
        document.getElementById("timeDate").innerHTML = "本站勉强运行 "+dnum+" 天 "; 
        document.getElementById("times").innerHTML = hnum + " 小时 " + mnum + " 分 " + snum + " 秒"; 
    } 
setInterval("createtime()",250);
</script>
```

* 配置代码雨 <font color=red>这个没有卸载默认里面</font>
1. 追加css
```css
#content_canvas {
  position: fixed;
  right: 0px;
  bottom: 0px;
  min-width: 100%;
  min-height: 100%;
  height: auto;
  width: auto;
  z-index: -1;
}
```

2. 页首html代码追加
```html
<canvas id="content_canvas" width="1440" height="900" ></canvas>
```

3. 页面底部追加代码
```js
<script>
window.onload = function(){
    //获取画布对象
    var canvas = document.getElementById("content_canvas");
    //获取画布的上下文
    var context =canvas.getContext("2d");
    var s = window.screen;
    var W = canvas.width = s.width;
    var H = canvas.height;
    //获取浏览器屏幕的宽度和高度
    //var W = window.innerWidth;
    //var H = window.innerHeight;
    //设置canvas的宽度和高度
    canvas.width = W;
    canvas.height = H;
    //每个文字的字体大小
    var fontSize = 12;
    //计算列
    var colunms = Math.floor(W /fontSize);	
    //记录每列文字的y轴坐标
    var drops = [];
    //给每一个文字初始化一个起始点的位置
    for(var i=0;i<colunms;i++){
        drops.push(0);
    }
    //运动的文字
    var str ="sh";
    //4:fillText(str,x,y);原理就是去更改y的坐标位置
    //绘画的函数
    function draw(){
        context.fillStyle = "rgba(238,238,238,.08)";//遮盖层
        context.fillRect(0,0,W,H);
        //给字体设置样式
        context.font = "600 "+fontSize+"px  Georgia";
        //给字体添加颜色
        context.fillStyle = ["#33B5E5", "#0099CC", "#AA66CC", "#9933CC", "#99CC00", "#669900", "#FFBB33", "#FF8800", "#FF4444", "#CC0000"][parseInt(Math.random() * 10)];//randColor();可以rgb,hsl, 标准色，十六进制颜色
        //写入画布中
        for(var i=0;i<colunms;i++){
            var index = Math.floor(Math.random() * str.length);
            var x = i*fontSize;
            var y = drops[i] *fontSize;
            context.fillText(str[index],x,y);
            //如果要改变时间，肯定就是改变每次他的起点
            if(y >= canvas.height && Math.random() > 0.99){
                drops[i] = 0;
            }
            drops[i]++;
        }
    };
    function randColor(){//随机颜色
        var r = Math.floor(Math.random() * 256);
        var g = Math.floor(Math.random() * 256);
        var b = Math.floor(Math.random() * 256);
        return "rgb("+r+","+g+","+b+")";
    }
    draw();
    setInterval(draw,35);
};
</script>
```