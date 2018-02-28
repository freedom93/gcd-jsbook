### 3.1 jQuery是什么

jQuery 是一个跨浏览器的 JavaScript 函数 库，它包含以下特性：

* HTML 元素选取

* HTML 元素操作

* CSS 操作

* HTML 事件函数

* JavaScript 特效和动画

* HTML DOM 遍历和修改

* AJAX

* Utilities

**jQuery极大地简化了 JavaScript 编程。**

例如JavaScript 访问某个 HTML 元素，以下是JavaScript原生实现代码：

```
<!DOCTYPE html>
<html>
<body>

<h1></h1>

<p id="demo">My First Paragraph.</p>

<script>
// 通过指定的 id 来访问 HTML 元素，并改变其内容
document.getElementById("demo").innerHTML="My First JavaScript";
</script>

</body>
</html>
```

[在线试一试](http://www.w3school.com.cn/tiy/t.asp?f=js_dom)

JavaScript 访问某个 HTML 元素，以下是JQuery实现代码：

**jQuery 库可以通过一行简单的标记（&lt;script src="**\[[https://cdnjs.cloudflare.com/ajax/libs/jquery/3.3.1/jquery.js"&gt;&lt;/script&gt;）被添加到网页中。\]\(https://cdnjs.cloudflare.com/ajax/libs/jquery/3.3.1/jquery.js"&gt;](https://cdnjs.cloudflare.com/ajax/libs/jquery/3.3.1/jquery.js"></script>）被添加到网页中。]%28https://cdnjs.cloudflare.com/ajax/libs/jquery/3.3.1/jquery.js">)&lt;/script&gt;）被添加到网页中。\)

```
<!DOCTYPE html>
<html>
<head>
<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.3.1/jquery.js"></script>
</head>
<body>

<h1></h1>

<p id="demo">My First Paragraph.</p>

<script>
// 通过指定的 id 来访问 HTML 元素，并改变其内容
$('#demo').html('My First JavaScript');
</script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.3.1/jquery.js"></script>
</body>
</html>
```

**jQuery 是一个“写的更少，但做的更多”的轻量级 JavaScript 库。**

基本上，您将学习到如何选取 HTML 元素，以及如何对它们执行类似隐藏、移动以及操作其内容等任务。

**学习需要对以下知识有基本的了解：**

* HTML
* CSS
* JavaScript



