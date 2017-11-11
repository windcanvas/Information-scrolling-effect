# Information-scrolling-effect
HTML+CSS+JavaScript实现信息滚动展示效果
- innerHTML

innerHTML属性设置或返回表格行的开始和结束标签之间的 HTML。

- scrollTop

scrollTop设置或获取位于对象最顶端和窗口中可见内容的最顶端之间的距离 (即网页被卷去的高)

- offsetHeight


## setInterval()与setTimeout

**1.setTimeout(表达式,延迟时间)**

在执行时，是在载入后延迟指定时间后，去执行一次表达式，仅执行一次

- setTimeout(code,ms) 方法用于在指定的毫秒数后调用函数或计算表达式。
- 注意：setTimeout() 只执行 code 一次。如果要多次调用，请使用 setInterval() 或者让code 自身再次调用 setTimeout()。

**2.setInterval(表达式,交互时间)**

在执行时，它从载入后，每隔指定的事件就执行一次表达式

- setInterval() 方法可按照指定的周期（以毫秒计）来调用函数或计算表达式。

- setInterval() 方法会不停地调用函数，直到 clearInterval() 被调用或窗口被关闭。由 setInterval() 返回的 ID 值可用作 clearInterval() 方法的参数。

## clearTimeout()与clearInterval()

**1.clearTimeout()**

clearTimeout()方法可取消由 setTimeout() 方法设置的 timeout。

**2.clearInterval()** 

- clearInterval()方法可取消由 setInterval() 设置的 timeout。

- clearInterval() 方法的参数必须是由 setInterval() 返回的 ID 值。



