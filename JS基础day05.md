# webAPIs 第一天测试题-pink老师



1. 可以说出什么是webapi ？（C）

- A. webapi 是 一套 操作网页内容(DOM) 的 对象
- B. webapi 是 一套 操作网页内容(DOM) 的 函数
- C. webapi 是一套 操作网页内容(DOM) 与 浏览器窗口(BOM) 的对象
- D.webapi 是一套 操作网页内容(DOM) 与 浏览器窗口(BOM) 的函数
- 

2.以下属于JS三个组成部分的是（ABC） 【多选题】

- A. ECMAScript
- B. DOM
- C. BOM
- D. document
- E. object
- 

3.如果我想获取第一个类名为box的元素，该使用哪一个方法？（C）

- A. document.querySelector('box')
- B. document.querySelectorAll('box')
- C. document.querySelector('.box')
- D. document.querySelectorAll('.box')
- 

4.如果我想获取所有类名为box的元素，该使用哪一个方法？（D）

- A. document.querySelector('box')
- B. document.querySelectorAll('box')
- C. document.querySelector('.box')
- D. document.querySelectorAll('.box')
- 

5.假设页面有两个类名为box的元素，以下哪一个语法会报错？（AC） 【多选题】

- A. document.querySelector('box').style.backgroundColor = 'red'
- B. document.querySelector('.box').style.backgroundColor = 'red'
- C. document.querySelectorAll('.box').style.backgroundColor = 'red'
- D. document.querySelectorAll('.box')[0].style.backgroundColor = 'red'
- 

6.关于innerText与innerHTML的区别，下列说法错误的是? （D）

- A. innerText只能获取元素文本，无法获取标签
- B. innerHTML可以获取文本 + 标签
- C. innerText在获取文本的时候，包含子元素的文本
- D. innerText与innerHTML在设置的时候，作用一致。都可以解析文本中的标签样式
- 

7.关于元素HTML常用属性操作，下列说法错误的是? （D）

- A. 元素HTML属性指的是HTML标签本身的属性，比如 title ， alt等等
- B. 修改img标签的图片语法是: 元素.src = '图片路径'
- C. 修改a标签的链接语法是: 元素.href = '链接'
- D. 获取元素的类名语法是： 元素.class
- 

8.关于元素css属性操作，下列说法错误的是？（B）

- A. 我们可以通过style属性来修改常见样式
- B. 我们可以通过类名来修改常见样式，格式是： 元素.class
- C. 我们可以使用classList 来增加删除类名， 比如 add()等等
- D. classList的优点是可以不影响原先类名
- 

9.下列设置元素css样式语法，哪些是错误的? （CDF） 【多选题】

- A. 元素.style.backgroundColor = 'red'
- B. 元素.style.backgroundColor = 'rgb(255,0,0)'
- C. 元素.style.background-color = 'red'
- D. 元素.style.width = 100
- E. 元素.style.width = '100px'
- F. 元素.style.src = '路径'
- 

10.关于classList语法，下列说法正确的是（ABCDE） 【多选题】

- A. classList的作用是操作元素的类名，包含新增、移除、切换类名等操作
- B. 新增类名： 元素.classList.add('类名')
- C. 移除类名： 元素.classList.remove('类名')
- D. 切换类名： 元素.classList.toggle('类名')
- E. classList 相比较 className的优点是可以不影响原先类名，一般是不覆盖原有类名
- 

11.关于表单属性语法，下列说法正确的是（BCE） 【多选题】

- A. 元素.innerText 属性也可以用于获取表单输入框的文本
- B. 输入框的文本必须要使用 元素.value
- C. 设置表单禁用状态的语法是： 元素.style.disabled= true
- D. 设置表单选中状态的语法是： 元素.checkd = true
- E. 设置表单选中状态的语法是： 元素.checked = true
- 

12.关于自定义属性说法错误的是？（D）

- A. 在html5中推出来了专门的data-自定义属性
- B. 在标签上一律以data-开头， 比如 data-id=“10”
- C. 在DOM对象上一律以dataset对象方式获取
- D. 自定义属性以后使用较少
- 

13. 关于间歇函数说法正确的是?（ABC） 【多选题】

- A. 间歇函数返回的值是数字型，而且间歇函数可以停止和开启，我们应该使用 let 声明
- B. 语法: setInterval(间歇函数, 间隔时间)，其中间隔时间的单位是 ms 毫秒
- C. 间歇函数可以根据时间自动重复执行某些代码
- D. 停止间歇函数的语法: clearInterval(间歇函数, 间隔时间)

# 作业

- 网页时钟
- 焦点图案例









