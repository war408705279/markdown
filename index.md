1. 标题：
    
    markdown中有两种标明标题的方法

    第一种方法只能表示第1和第2两级的标题，书写方式如下所示：

    ```
    这里是一级标题
    ===

    这里是二级标题
    ---
    ```

    最终的显示效果如下所示：

    这里是一级标题
    ===

    这里是二级标题
    ---

    第二种方法能表示从1-6共六级标题，书写方式如下所示：

    ```
    # 这里是一级标题
    ## 这里是二级标题
    ### 这里是三级标题
    #### 这里是四级标题
    ##### 这里是五级标题
    ###### 这里是六级标题
    ```

    最终的显示效果如下所示：

    # 这里是一级标题
    ## 这里是二级标题
    ### 这里是三级标题
    #### 这里是四级标题
    ##### 这里是五级标题
    ###### 这里是六级标题

2. 换行：

    markdown中的换行方法是连续输入两个回车，如下所示：

    这里是第一行（在这里回一次车）

    （在这里再回一次车）

    这里是第二行

3. 区块引用

    markdown中的区块引用使用\>进行标识，多层嵌套就用多个\>进行标识，书写方式如下所示：

    ```
    > 区块引用1

    >> 嵌套引用1-1

    >>> 嵌套引用1-1-1

    >> 嵌套引用1-2

    >>> 嵌套引用1-2-1

    > 区块引用2

    >> 嵌套引用2-1

    >>> 嵌套引用2-1-1

    >> 嵌套引用2-2

    >>> 嵌套引用2-2-1
    ```

    最终的显示效果如下所示：

    > 区块引用1

    >> 嵌套引用1-1

    >>> 嵌套引用1-1-1

    >> 嵌套引用1-2

    >>> 嵌套引用1-2-1

    > 区块引用2

    >> 嵌套引用2-1

    >>> 嵌套引用2-1-1

    >> 嵌套引用2-2

    >>> 嵌套引用2-2-1

    当然，在引用中也可以使用markdown的其他语法，例如如下所示：

    ```
    > 区块引用*markdown*（在区块中使用斜体）
    ```

    最终的显示效果如下所示：

    > 区块引用*markdown*

4. 代码区块

    markdown中的代码区块使用\`\`\`进行标识，在标识后面加上语言标识，还可以对代码进行高亮处理（例如加入javascript，js标识）书写方式如下所示：

    \`\`\`js

    var testFunc = function() {
        console.log("这是一个测试方法");
    }

    \`\`\`

    最终的显示效果如下所示：

    ```js
    var testFunc = function() {
        console.log("这是一个测试方法");
    }
    ```

5. 强调

    markdown中使用\*和\_来对字符进行强调，在对需要强调的字符前后各加一个\*或者\_表示斜体，各加两个\*或者\_表示粗体，书写方式如下所示：

    ```
    *斜体* _斜体_

    **粗体** __粗体__
    ```
    
    最终的显示效果如下所示：

    这是一段非常正常的文字，突然之间就出现了一个*斜体*（用\*标识的），然后又出现了一个 _斜体_（用\_标识的）。没过多久就出现了一个**粗体**（用\*\*标识的），然后又出现了一个 __粗体__（用\_\_标识的）


6. 列表

    markdown中有4种方法来表示列表，第一种在列表项前面加\-进行表示，书写方式如下所示：

    ```
    注意-和列表项中间有一个空格
    - 这里是第一项
    - 这里是第二项
    - 这里是第三项
    ```

    最终的显示效果如下所示：

    - 这里是第一项
    - 这里是第二项
    - 这里是第三项

    第二种在列表项前面加\*进行表示，书写方式如下所示：

    ```
    注意*和列表项中间有一个空格
    * 这里是第一项
    * 这里是第二项
    * 这里是第三项
    ```

    最终的显示效果如下所示：

    * 这里是第一项
    * 这里是第二项
    * 这里是第三项

    第三种在列表项前面加\+进行表示，书写方式如下所示：

    ```
    注意+和列表项中间有一个空格
    + 这里是第一项
    + 这里是第二项
    + 这里是第三项
    ```

    最终的显示效果如下所示：

    + 这里是第一项
    + 这里是第二项
    + 这里是第三项

    第四种在列表项前加数字进行表示，书写方式如下所示：

    ```
    注意数字和列表项中间有一个.还有一个空格
    1. 这里是第一项
    2. 这里是第二项
    3. 这里是第三项
    ```
    最终的显示效果如下所示

    1. 这里是第一项
    2. 这里是第二项
    3. 这里是第三项

7. 分割线

    markdown中一共有三种方式表示分割线，第一种是连续使用三个\*号进行表示，书写方式如下所示：

    ```
    ***
    ```

    最终的显示效果如下所示：

    ***

    第二种是连续使用三个\-号进行表示，书写方式如下所示：

    ```
    ---
    ```

    最终的显示效果如下所示：

    ---

    第三种是连续使用三个\_号进行表示，书写方式如下所示：

    ```
    ___
    ```

    最终的显示效果如下所示：
    ___

    当然，表示分割线的符号之间可以存在空格，但是不能存在其他符号，否则分割线无效，如下所示：

    ```
    - - -
    ```

    最终显示效果如下所示：

    - - -

8. 链接

    markdown中一共有两种方式可以表示链接，第一种为行内式（链接名称和引用写在同一行内），[]中包含的内容为链接在正文中显示的文本内容，具体对应的链接包含在()中。书写方式如下所示：

    ```
    [百度](https://www.baidu.com)
    ```

    最终的显示效果如下所示：

    [百度](https://www.baidu.com)

    第二种为参考式（像论文引用参考一样，链接名称写在正文内，而引用可以写在其他的地方，一般是写在文末），链接名称部分由两部分组成，第一个[]中包含的是正文中显示的文本内容，第二个[]中包含的是对应的索引（索引编号必须唯一）。引用部分也有两部分组成，第一个[]中包含的是索引编号（和正文中的编号对应），:后面对应的便是引用的地址链接。书写方式如下所示：

    ```
    [百度][1]

    [ZEALER][2]

    [1]: https://www.baidu.com
    [2]: http://www.zealer.com
    ```

    最终的显示效果如下所示：

    [百度][1]
    [ZEALER][2]

    [1]: https://www.baidu.com
    [2]: http://www.zealer.com

9. 图片链接

    markdown中一共有两种方式可以表示图片链接，和上述文字链接一样，也分为行内式和参考式，行内式与文字链接的唯一区别就是在最前面加一个\!，()中的图片链接既可以写http上的图片地址，也可以使用相对路径写本地的图片地址。书写方式如下所示：

    ```
    ![程序狗](./images/coding_dog.jpg "程序狗")
    ```

    *注意*：方括号（[]）中的信息会最终变为图片的 alt 信息，而图片地址后面引号内的部分最终变为图片的 title 信息，这两个参数都是可选的

    最终的显示效果如下所示：

    ![程序狗](./images/coding_dog.jpg "程序狗")

    第二种方式为参考式，大体和文字链接的参考式相同，唯一区别就是在最前面加一个\!。书写方式如下所示：

    ```
    ![程序狗][1]

    [1]: ./images/coding_dog.jpg "程序狗"
    ```

    最终显示效果如下所示：

    ![门][image1]

    [image1]: https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1530160526055&di=c9be9c5499b507e7eb6fc4dc5781a51c&imgtype=0&src=http%3A%2F%2Fg.hiphotos.baidu.com%2Fimage%2Fpic%2Fitem%2Fb8014a90f603738d1f357dacbf1bb051f919ecc5.jpg "门"

10. 反斜杠\

    markdown中使用反斜杠\进行转义的作用，让符号变成普通符号从而在文本中进行显示，书写方式如下所示：

    ```
    \* \- \_ \` 等等......
    ```

    使用效果为：在这句话中，如果不使用反斜杠进行转义，*这些字*就会变成斜体，但是如果使用了转义，就会显示为\*这些字\*

11. 符号'`'

    markdown中使用\`进行标记，书写方式如下所示：

    ```
    `ctrl+a`
    ```

    最终显示效果如下所示：

    `ctrl+a`

12. 删除线

    markdown中使用\~\~表示删除线，需要在添加删除线文本的前后都加上~~，书写方式如下所示：

    ```
    ~~添加删除线~~
    ```

    最终显示效果如下所示：
    
    ~~添加删除线~~

13. Table

    markdown中table的使用请查看[Table](./table.md "markdown table")

14. TaskList

    markdown中tasklist的使用请查看[TaskList](./tasklist.md "markdown tasklist")

15. jump

    如果你使用markdown写了一篇很长的文章，这篇文章拥有复杂的结构目录。如果没有章节索引的跳转功能，那么阅读这篇文章无疑是很费劲的。markdown中就提供了这种跳转功能，具体是用请查看[jump](./jump.md "markdown jump")

16. 下划线

    markdown中并没有加下划线的语法，原因是会和链接的默认样式产生混淆，但是我们可以使用HTML + CSS样式为文字加下划线，示例代码如下所示：

    ```html
    <span style="border-bottom: 1px dashed yellow;">需要加下划线的文字</span>
    ```
    最终效果如下所示：

    <span style="border-bottom: 1px dashed yellow;">需要加下划线的文字</span>


更新中......