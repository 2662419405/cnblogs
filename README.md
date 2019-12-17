



# 欢迎来到残梦博客园

> 首先声明一点: 样式并不是本人所写,是我个人整合(感觉每个人的博客都喜欢一点,所以自己整合了一下!!!!)
>

* 博客园网址 : ----->  [博客园网址](https://www.cnblogs.com/sunhang32)


<p align="center" style="margin:50px 0;">
	<img src="https://img.shields.io/badge/language-html-blue" />
    <img src="https://img.shields.io/badge/build-passing-green"  />
    <img src="https://img.shields.io/badge/version-v1.2.0-informational" />
    <img src="https://img.shields.io/badge/codecov-25-red" />
    <img src="https://img.shields.io/badge/platform-ios%20%7C%20android%20%7C%20widdow%20%7C%20ipad-inactive"  />
    <img src="https://img.shields.io/badge/weibo-%40SH-blueviolet"  />
</p>

* 自己如何也弄一个? <a href="#使用说明">使用说明</a>
* 目前有哪些功能? <a href="#目前功能">目前功能</a>
* 效果图啥样? <a href="#效果图展示">效果图展示</a>
* 动动小手点个star呗,让我有动力继续更新下去,感谢感谢^-^

## 目前功能

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
* :peach: DaoVoice聊天

##  效果图展示
![电脑效果图4](/img/130.jpg)
<img src="/img/140.jpg" height="700px" />

## 如果感觉勉强可以看几眼的话,那么你也来做一个吧

### 使用说明

* 首先你要有一个[博客园](https://www.cnblogs.com)(估计会`github`的都应该知道了)
* 在[博客园](https://www.cnblogs.com)的官网左上角开通博客园
* 博客园的个人配置页面->先申请js权限

![Snipaste_2019-11-13_14-41-38](/img/Snipaste_2019-11-13_14-41-38.png)

* 禁用页面的css样式

![Snipaste_2019-11-13_14-42-25](/img/Snipaste_2019-11-13_14-42-25.png)

* 选择博客主题

![Snipaste_2019-11-21_08-12-32.png](/img/Snipaste_2019-11-21_08-12-32.png)

* 粘贴代码到定制页面css代码中 [css](/css/sh.css)

* 粘贴博客侧面公告代码
```html
<link rel="stylesheet" type="text/css" href="https://blog-static.cnblogs.com/files/sunhang32/pio.css" />
<script type="text/javascript">
    window.cnblogsConfig = {
        GhVersions    : 'v1.2.0', // 版本
        blogUser      : "残梦", // 用户名
        essayCodeHighlightingType: "highlightjs",
        essayCodeHighlighting: "vs2015",
        homeTopImg: [
           "https://cdn.jsdelivr.net/gh/2662419405/imgPlus/o_o_wallhaven-698904.jpg"
        ],
         menuUserInfoBgImg: 'https://bndong.github.io/images/menu_bg.gif',
         menuNavList: [ // 列表数据 ['导航名称', '链接']
             ['github', 'https://github.com/2662419405'],
             ['CSDN', 'https://blog.csdn.net/qq_43268396'],
             ['技能树', 'https://shtodream.cn/about/'],
             ['留言板', 'https://shtodream.cn/message/'],
        ],
        fontIconExtend: "//at.alicdn.com/t/font_543384_ezv3l7gd9r7.css",  //字体图标扩展
        webpageTitleOnblur        : "(◍´꒳`◍)你为何狠心离去 ", // 当前页失去焦点，页面title显示文字
        webpageTitleOnblurTimeOut : 500, // 当前页失去焦点，页面title变化，延时时间，单位毫秒
        webpageTitleFocus         : "(*´∇｀*) 帅的人回来了！", // 当前页获取焦点，页面title显示文字，显示后延时恢复原title
        webpageTitleFocusTimeOut  : 2000, // 当前页获取焦点，页面title变化，延时时间，单位毫秒
        blogAvatar    : "https://cdn.jsdelivr.net/gh/2662419405/CDN@1.0/sh.jpg", // 用户头像
        blogStartDate : "2019-11-07", // 入园时间，年-月-日。入园时间查看方法：鼠标停留园龄时间上，会显示入园时间
    }
</script>
<script src="https://cdn.jsdelivr.net/gh/BNDong/Cnblogs-Theme-SimpleMemory@v1.2.0/src/script/simpleMemory.min.js"></script>
<script>(function(i,s,o,g,r,a,m){i["DaoVoiceObject"]=r;i[r]=i[r]||function(){(i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;a.charset="utf-8";m.parentNode.insertBefore(a,m)})(window,document,"script",('https:' == document.location.protocol ? 'https:' : 'http:') + "//widget.daovoice.io/widget/bd4254a0.js","daovoice")</script>
<script>
daovoice('init', {
  app_id: "bd4254a0"
});
daovoice('update');
</script>
<link rel="stylesheet" type="text/css" href="https://cdn.jsdelivr.net/gh/2662419405/CDN/pio.css" />
```

* 粘贴页首代码 
```html
<div class="pio-container" style="left: 50px; bottom: 50px;">
	<div class="pio-action"></div>
	<canvas id="pio" style="opacity: 0.6;" width="200px" height="200px"></canvas>
</div>
```

* 粘贴页脚代码 
```html
<!-- 滚动进度 -->
<div id="bottomProgressBar"></div>
<!-- 音乐菜单 -->
<link rel="stylesheet" href="https://blog-static.cnblogs.com/files/elkyo/APlayer.min.css">
<div id="player" class="aplayer aplayer-withlist aplayer-fixed" data-id="3025663508" data-server="netease" data-type="playlist" data-order="random" data-fixed="true" data-listfolded="true" data-theme="#2D8CF0"></div>
<script src="https://blog-static.cnblogs.com/files/elkyo/APlayer.min.js"></script>
<script src="https://blog-static.cnblogs.com/files/elkyo/Meting.min.js"></script>
<!-- 网站运行时间 -->
<p style="text-align:center;"><span id="timeDate">载入天数...</span><span id="times">载入时分秒...</span></p>
<script>
	var now = new Date();
	function createtime() {
		var grt = new Date("11/06/2019 17:38:00"); //在此处修改你的建站时间
		now.setTime(now.getTime() + 250);
		days = (now - grt) / 1000 / 60 / 60 / 24;
		dnum = Math.floor(days);
		hours = (now - grt) / 1000 / 60 / 60 - (24 * dnum);
		hnum = Math.floor(hours);
		if(String(hnum).length == 1) {
			hnum = "0" + hnum;
		}
		minutes = (now - grt) / 1000 / 60 - (24 * 60 * dnum) - (60 * hnum);
		mnum = Math.floor(minutes);
		if(String(mnum).length == 1) {
			mnum = "0" + mnum;
		}
		seconds = (now - grt) / 1000 - (24 * 60 * 60 * dnum) - (60 * 60 * hnum) - (60 * mnum);
		snum = Math.round(seconds);
		if(String(snum).length == 1) {
			snum = "0" + snum;
		}
		document.getElementById("timeDate").innerHTML = "本站勉强运行 " + dnum + " 天 ";
		document.getElementById("times").innerHTML = hnum + " 小时 " + mnum + " 分 " + snum + " 秒";
	}
	setInterval("createtime()", 250);
</script>
<!-- 右下角菜单 -->
<div id="rightMenu"></div>
<!--看板娘 - 猫-->
<script src="https://cdn.jsdelivr.net/gh/2662419405/CDN/l2d.js"></script>
<script src="https://cdn.jsdelivr.net/gh/2662419405/CDN/pioPlus.js"></script>
<script src="https://cdn.jsdelivr.net/gh/2662419405/CDN/mao.js"></script>
<!-- 线条效果(推荐关闭这个特效,对于手机端影响过大) -->
<script type="text/javascript" color="220,220,220" opacity='0.9' zIndex="-2" count="100" src="//cdn.bootcss.com/canvas-nest.js/1.0.0/canvas-nest.min.js">
</script>
<script type="text/javascript" src="https://blog-static.cnblogs.com/files/sunhang32/ce.js"></script>
<!-- 文字显示 -->
<script type="text/javascript" src="https://files.cnblogs.com/files/sunhang32/myText.js"></script>
<!-- 输入框特效 -->
<script type="text/javascript" src="https://cdn.jsdelivr.net/gh/2662419405/CDN/blog.js"></script>
<script type="text/javascript" src="https://cdn.jsdelivr.net/gh/2662419405/CDN/POW.js"></script>
```

##### 如果配置成功了,不妨点个赞,咱们一起开心一下,有问题可以发issues^-^

*--------------如果你对你的代码不满意的话,可以接下来自定义设置----------------*

### 下面是DIV定制

* 背景线条特效(这个比较耗费性能,尽量少用,对于手机端影响更大一些)
```js
<script type="text/javascript"
color="220,220,220" opacity='0.7' zIndex="-2" count="500" src="//cdn.bootcss.com/canvas-nest.js/1.0.0/canvas-nest.min.js">
</script>
//color 颜色
//opacity 透明度
//zIndex 层级(一般为负数)
//count数量
```

* 输入框特效

```js
<script type="text/javascript" src="https://cdn.jsdelivr.net/gh/2662419405/CDN/blog.js"></script>
<script type="text/javascript" src="https://cdn.jsdelivr.net/gh/2662419405/CDN/POW.js"></script>
```

* 点击屏幕显示文字特效

```js
<script type="text/javascript" src="https://files.cnblogs.com/files/sunhang32/myText.js"></script>
```

* 背景音乐
```js
<link rel="stylesheet" href="https://blog-static.cnblogs.com/files/elkyo/APlayer.min.css">
  <div id="player" class="aplayer aplayer-withlist aplayer-fixed" data-id="3025663508" data-server="netease" data-type="playlist" data-order="random" data-fixed="true" data-listfolded="true" data-theme="#2D8CF0"></div>
  <script src="https://blog-static.cnblogs.com/files/elkyo/APlayer.min.js"></script>
  <script src="https://blog-static.cnblogs.com/files/elkyo/Meting.min.js"></script>
<script>
$(".aplayer-play").click()   // 如果想让歌曲在页面加载完播放可以设置
</script>
```

> 修改音乐只需要修改data-id即可

<img src="https://cdn.jsdelivr.net/gh/2662419405/imgPlus/Snipaste_2019-12-17_07-59-05.png" />
<img src="https://cdn.jsdelivr.net/gh/2662419405/imgPlus/Snipaste_2019-12-17_07-59-34.png" />

* 猫
```js
<link rel="stylesheet" type="text/css" href="https://cdn.jsdelivr.net/gh/2662419405/CDN/pio.css" />
<script src="https://cdn.jsdelivr.net/gh/2662419405/CDN/l2d.js"></script>
<script src="https://cdn.jsdelivr.net/gh/2662419405/CDN/pioPlus.js"></script>
<script src="https://cdn.jsdelivr.net/gh/2662419405/CDN/mao.js"></script>
```

> 目前猫还存在一点小的bug,但不影响正常使用,我也在不断改进中^-^
* 右侧直接聊天功能

```js
<script>(function(i,s,o,g,r,a,m){i["DaoVoiceObject"]=r;i[r]=i[r]||function(){(i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;a.charset="utf-8";m.parentNode.insertBefore(a,m)})(window,document,"script",('https:' == document.location.protocol ? 'https:' : 'http:') + "//widget.daovoice.io/widget/bd4254a0.js","daovoice")</script>
<script>
daovoice('init', {
  app_id: "bd4254a0"
});
daovoice('update');
</script>
```

这里面的的app_id请到 <a href="http://dashboard.daovoice.io/app/bd4254a0/settings/install">daovoice网站注册获得</a>

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

> 上面的实现修改为自己创建网站的时间,把 p 标签插入到想要显示的区域即可

* 配置代码雨 
<font color=red>这个没有写在默认里面</font>
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

> 更多的本人效果,可以浏览本人-><a href="https://shtodream.cn">学习博客</a>

