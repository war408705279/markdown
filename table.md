## Table的使用

### 基本使用

在markdown中是用|来分隔不同的单元格，使用-来分隔表头和其他行，表格基本的书写方法如下所示：

```
| name | age |
| ---- | --- |
| jiayizhen | 26 |
| macco | 26 |
```

最终的显示效果如下所示：

| name | age |
| ---- | --- |
| jiayizhen | 26 |
| macco | 26 |

为了看上去美观一些，可以使用空格将所有的单元格进行对其，书写方法如下所示：

```
|    name   | age |
|    ----   | --- |
| jiayizhen |  26 |
|   macco   |  26 |
```

最终的显示效果如下所示：

|    name   | age |
|    ----   | --- |
| jiayizhen |  26 |
|   macco   |  26 |

为了使表格的表述清晰，|和-之间最好至少有一个空格，这样方便查看也较为美观

### 对齐

在*表头*下方的分隔符（-）中加入:，可以对表格的对齐方式进行编辑，具体内容如下所示：

- :--- 表示左对齐
- :--: 表示居中
- ---: 表示右对齐

具体书写方法如下所示：

```
|    name   |  age |   sex   |
|    :---   | :--: |   ---:  |
| jiayizhen |  26  |   male  |
|   macco   |  26  |   male  |
|    lily   |  26  |  female |
```

最终的显示效果如下所示：

|    name   |  age |   sex   |
|    :---   | :--: |   ---:  |
| jiayizhen |  26  |   male  |
|   macco   |  26  |   male  |
|    lily   |  26  |  female |

### 插入其他内容

markdown的table中也允许包含其他的语法标记，例如斜体、粗体、链接等等，具体书写方法如下所示：

```
|     name    |   type   |                link                  |
|     :--:    |   :--:   |                :--:                  |
|   __百度__   |  search  |    [百度](https://www.baidu.com)      |
|   *Google*  |  search  |    [Google](https://www.google.com)  |
|    ZEALER   |   tech   |    [ZEALER](http://www.zealer.com)   |
```

最终的显示效果如下所示：

|     name    |   type   |                link                  |
|     :--:    |   :--:   |                :--:                  |
|   __百度__   |  search  |    [百度](https://www.baidu.com)      |
|   *Google*  |  search  |    [Google](https://www.google.com)  |
|    ZEALER   |   tech   |    [ZEALER](http://www.zealer.com)   |