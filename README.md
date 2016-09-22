# -
回到顶部，慕课学习的小demo

该demo实现效果为：当窗口内容下拉至一个屏幕的高度之外，右下角显现回到顶部按钮，鼠标移至按钮点击后滚动条自动滚动至网页顶端，
如果中途触发滚动条，回到顶部指令停止。在实现置顶上相对使用锚链接更优化，滚动更加平滑。

    documentElenment.clientHeight获取内容可视区域的高度
    
    window.onscroll为页面滑动触发事件
        
        为了兼容，使用var top = document.documentElement.scrollTop || document.body.scrollTop;获得页面距离顶部的距离。
        
    setInterval() 方法可按照指定的周期（以毫秒计）来调用函数或计算表达式。
    setInterval() 方法会不停地调用函数，直到 clearInterval() 被调用或窗口被关闭。
    
    Math.floor(x)，对一个数进行下取整。
    
    Math.ceil(x)，对一个数进行上取整。
    
    Math.round(x)，四舍五入取整。
    
