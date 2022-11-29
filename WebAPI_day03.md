

# WebAPI-day03检测题



1.以下关于事件对象，说法错误的是：（）

- A. 事件对象在事件监听回调函数的第一个参数
- B. 事件对象一般用于获取鼠标坐标信息与键盘按键信息
- C. 事件对象不可以自己命名，必须严格遵循规则来写，比如 必须是event
- D. 事件对象不仅有属性，还有方法

2. 以下关于事件委托，说法错误的是? （）

- A. 事件委托指的是 给父元素注册事件，委托给子元素来处理
- B. 事件委托一般用于解决 ： 给动态新增的元素注册事件
- C. 事件委托可以减少页面注册事件的次数,事件委托其实是利用事件冒泡的特点
- D. 事件委托中的this与e.target指向同一个对象，它们可以随意互换

3. 以下关于事件流，说法错误的是? （）

- A. 事件流三个阶段是：事件捕获、事件目标、事件冒泡
- B. 默认情况下，我们一般注册的事件都是冒泡事件
- C. addEventListener 可以捕获和冒泡，而 btn.onclick= function(){} 只有冒泡
- D. 事件流是浏览器默认现象，我们无法阻止

4.关于js中的事件冒泡与事件捕获，下列说法正确的是？（）

- A： 捕获类型事件，只能使用addEventListener注册，传统注册方法只能是事件冒泡
- B： 事件对象的stopPropagation方法只能阻止冒泡，不能阻止捕获
- C： 事件冒泡是浏览器的默认行为，我们无法阻止
- D： 如果想要阻止事件的冒泡行为，可以使用事件对象的preventDefault()方法

5.在 JavaScript 中，用于阻止默认事件的默认操作的方法是? （）

- A： stopDefault()
- B： stopPropagation()
- C： preventPropagation()
- D： preventDefault()

6.在 JavaScript 中，用于阻止事件冒泡的操作的方法是? （）

- A： stopDefault()
- B： stopPropagation()
- C： preventPropagation()
- D： preventDefault()

7.事件委托中，可以获得真正触发事件的元素的是? （）

- A： 事件对象.target. tagName
- B： target. tagName
- C： 事件对象.target. name
- D： 事件对象.tagName

8.下面关于尺寸说法正确的是？ （） 【多选题】

- A：scrollLeft和scrollTop 是获取被卷去的左侧和头部， 是可读写的
- B： window.scrollTo() 方法可把内容滚动到指定的坐标
- C： clientWidth和clientHeight 获取元素的可见部分宽高(不包含边框，滚动条等)
- D： offsetWidth和offsetHeight 获取元素的自身宽高、包含元素自身设置的宽高、padding、border ，是只读的

9.下面是页面加载事件的是?（）

- A： scroll
- B： load
- C： resize
- D： target

10.下面是页面滚动事件的是?（）

- A： scroll
- B： load
- C： resize
- D： target

11.下面是页面尺寸发生变化触发的事件是?（）

- A： scroll
- B： load
- C： resize
- D： target

 