# tip
个人的第一个自我封装的jquyer tips插件
基本使用：
$(..).JSTips();
参数配置：
$(..).JSTips({
    ...
});
background:"#000",//tips的背景颜色
color:"white",//字体颜色
position:"r",//出现的位置 l--左边， r--右边  t--顶部  b--底部
tipsP:"20px",//tips的居中位置偏移量
padding:"10px",//文字提示内边距
txt:"helloWorld",//文字
IconPos:"10px",//小箭头居中位置偏移量
speed:"200",//tips出现的速度延迟
show:true//是否出现；
