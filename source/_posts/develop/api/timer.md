---
title: 定时器
header: develop
nav: api
sidebar: timer
---
##  clearInterval

**解释**：取消由 setInterval 设置的定时器。

**方法参数**：Number ntervalID

**`intervalID`参数说明：**要取消的定时器的 ID。

##  clearTimeout

**解释**：取消由 setTimeout 设置的定时器。

**方法参数**：Number timeoutID

**`timeoutID`参数说明：**要取消的定时器的 ID。

##  setInterval

**解释**：设定一个定时器。按照指定的周期（以毫秒计）来执行注册的回调函数。

**方法参数**：Function callback, Number delay

**`callback`参数说明：**回调函数

**`delay`参数说明：** 执行回调函数之间的时间间隔，单位 ms。 

**返回值**：

|名称|解释|
|--|--|
|number|定时器的编号。这个值可以传递给 <a href="http://smartprogram.baidu.com/docs/develop/api/timer/#clearTimeout/">clearInterval </a>来取消该定时。|

##  setTimeout

**解释**：设定一个定时器。在定时到期以后执行注册的回调函数

**方法参数**：Function callback, Number delay

**`callback`参数说明：**回调函数

**`delay`参数说明：** 延迟的时间，函数的调用会在该延迟之后发生，单位 ms。


**返回值**：

|名称|解释|
|--|--|
|number|定时器的编号。这个值可以传递给 <a href="http://smartprogram.baidu.com/docs/develop/api/timer/#clearTimeout/">clearTimeout  </a>来取消该定时。|
