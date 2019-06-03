# 一、 标题

  Markdown共有六级标题
  
  1. 用’#‘表示第一级标题
  1. 用’##‘表示第二级标题
  1. 用’###‘表示第三级标题
  * 用’####‘表示第四级标题
  * 用’######‘表示第五级标题
  * 用‘######’表示第六级标题

    # 标题一级
    ## 标题二级
    ### 标题三级
    #### 标题四级
    ##### 标题五级
    ###### 标题六级
    ####### 7个#也被解析为文本

# 二、列表

  有时候你可能需要带数字的列表：

  1. One
  2. Two
  3. Three

  有时候你可能需要带小圆点的列表：

  * Start a line with a star
  * Profit!

  或者：

  - Dashes work just as well
  - And if you have sub points, put two spaces before the dash or star:
    - Like this
    - And this
    
# 三、图片

  如果你希望嵌入一张图片，可以这么做</br>
  ![Yaktocat 的图片](https://github.com/longpang/markdown/blob/master/testimage.png)
  
# 四、表格和文本样式

  |文本样式|符合|输出模式|
  -:|:-:|:-
  |加粗| ** ** 或__ __ |**加粗** |
  |斜体| * * 或_ _ |*斜体*|
  |删除线| ~~ ~~ |~~删除线~~|
  
# 五、代码  

 Markdown 语法：
 
   * 有很多不同的方式来使用 GitHub 的 markdown 来编写代码。如果你有内联代码块，用反引号包裹起来：`var example = true`。如果你有一个更长的代码块，你可以缩进四个空格：
 
    if (isAwesome){
    return true
    }
 
  * GitHub 还支持称为代码篱笆的功能，它允许多行没有缩进：

  ```
  if (isAwesome){
  return true
  }
  ```
 
  * 如果你想使用对应语言的语法高亮：

  ```javascript
  if (isAwesome){
    return true
  }
  ```

