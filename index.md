##   Welcome to GitHub Pages.

##   This is the personal page of Brother Zha. 
##   My WeChat:yueqidps
##   My email: 63343761@qq.com
##   这是渣哥哥的个人页面
##   我的微信：yueqidps
##   我的邮箱：63343761@qq.com 
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>Insert title here</title>
</head>
<body>
<div id="playercontainer"></div>
<script type="text/javascript" src="js/cyberplayer.js"></script>
<script type="text/javascript">
    var player = cyberplayer("playercontainer").setup({
        width: 680,
        height: 448,
        file: "http://cctvtxyh5ca.liveplay.myqcloud.com/live/cctv1_2/index.m3u8",
        autostart: true,
        stretching: "uniform",
        volume: 100,
        controls: over,
        rtmp: {
            reconnecttime: 5, // rtmp直播的重连次数
            bufferlength: 1 // 缓冲多少秒之后开始播放 默认1秒
        },
        ak: "gC4c68fZAyFKhKgjjFWIhyeNDC0V9x2n"
    });
</script>
</body>
</html>
————————————————
版权声明：本文为CSDN博主「夜慬凉」的原创文章，遵循 CC 4.0 BY-SA 版权协议，转载请附上原文出处链接及本声明。
原文链接：https://blog.csdn.net/qq_27933251/java/article/details/100934296
