## Markdown中的jump

### 生成目录的方法

在markdown中生成目录的书写方式如下所示：

```
[目录标题](#目录跳转对应的id)
例如：
[1.第一章](#1)
```

最终的显示效果如下所示：

- [1 第一章](#1)

  - [1.1 第一章第一节](#1-1)

  - [1.2 第一章第二节](#1-2)

    - [1.2.1 第二节第一部分](#1-2-1)

- [2 第二章](#2)

- [3 第三章](#3)

  - [3.1 第三章第一节](#3-1)

### 生成页内锚点

在正文部分，只要用对应标签的id与目录中的id对应即可，具体书写方法如下所示：

```
<h2 id="1">第一章</h2>

<h3 id="1-1">第一章第一节</h3>

<h3 id="1-2">第一章第二节</h3>

<h4 id="1-2-1">第二节第一部分</h4>

<h2 id="2">第二章</h2>

<h2 id="3">第三章</h2>

<h3 id="3-1">第三章第一节</h3>
```

最终显示效果如下所示：

<h2 id="1">第一章</h2>

<h3 id="1-1">第一章第一节</h3>

<h3 id="1-2">第一章第二节</h3>

<h4 id="1-2-1">第二节第一部分</h4>

<h2 id="2">第二章</h2>

<h2 id="3">第三章</h2>

<h3 id="3-1">第三章第一节</h3>

这样通过页内的锚点就可以实现页内的跳转