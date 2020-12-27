# JS30學習筆記

##  01

### 使用 JavaScript 判斷 keydown 的事件
*	addEventListener(event, function, useCapture)
*	type -> [監聽的 event type 名稱](https://developer.mozilla.org/zh-TW/docs/Web/Events)
*	function -> 函式

### data-key
* TODO

### qeurySelector() v.s. querySelectorAll()
.qeurySelector() 只會針對元素的第一筆資料，其他並不會被選入。這時候可以使用.querySelectorAll()。 [ref](https://ithelp.ithome.com.tw/articles/10211614)

### Event.target v.s. Event.currentTarget
event.currentTarget 屬性總會指向目前於冒泡或捕捉階段正在處理該事件之事件處理器所註冊的 DOM 物件，而 event.target 屬性則是永遠指向觸發事件的 DOM 物件。

