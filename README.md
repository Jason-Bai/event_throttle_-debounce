# Event_Throttle_Debounce

前端开发中，我们将这些scroll，resize、鼠标事件（比如 mousemove、mouseover 等）、键盘事件（keyup、keydown 等）进行绑定时，当用户频繁触发
这些事件时，绑定的函数被多次执行，那我没有办法防止绑定的函数被多次执行呢，其实是有的，主要有节流(throttle)和防抖(debounce)两种。

## Throttle

throttle约定了以第一次执行时的时间为开始时间，到了一定时间后的那一刻执行。

## Debounce

debounce约定了已最后一次执行时的时间为开始时间，到了一定时间后的那一刻执行。

注意：这里为什么不说必须执行，因为我们的例子中使用setTimeout，大家知道setTimeout在前端中并不是一定会在一定时间后的那一刻执行。