# 第一课 Hello World

### 1 快速实现

第一课目标：**实现在公众号中自定义菜单中嵌入我们自己的网页（需要认证的公众号）。**

如下图所示，点击试验区后即跳转至填入的页面地址。

这个静态页面我们通过 Github Pages 来实现。

<img src="/Users/liaohua/Library/Application Support/typora-user-images/image-20200111202219137.png" alt="image-20200111202219137" style="zoom:50%;" />

- STEP1 注册一个 Github 账号
- STEP2 新建一个名字为「你的账户名.github.io」的仓库，记得勾选「Initialize the repository with a README」：

![image-20200111203339218](https://tva1.sinaimg.cn/large/006tNbRwly1gaswfde003j30ud0u0n23.jpg)

- 进入新建的仓库，「Create new file」：

<img src="https://tva1.sinaimg.cn/large/006tNbRwly1gaswj0vohtj318m0mg41i.jpg" alt="image-20200111203710861" style="zoom:50%;" />

- 文件命名为「index.html」，内容为：

  ```html
  <html>
    
    <head>
      <title>
      	hello world
      </title>      
    </head>
    
    <body>
      <h1>Hello World!</h1>
    </body>
    
  </html>
  ```

- 点击 Settings，拉到最下面，Github 自动识别后已经将站点发布了！

  <img src="https://tva1.sinaimg.cn/large/006tNbRwly1gaswmkut2gj31ae0fuwi8.jpg" alt="image-20200111204035491" style="zoom:50%;" />

  <img src="https://tva1.sinaimg.cn/large/006tNbRwly1gaswpnt1zpj30u70u00xu.jpg" alt="image-20200111204333460" style="zoom:50%;" />

- 用电脑访问看看

  ![image-20200111204705233](https://tva1.sinaimg.cn/large/006tNbRwly1gaswtg0bybj30oc07mdg9.jpg)

- 在公众号里发布

  <img src="https://tva1.sinaimg.cn/large/006tNbRwly1gaswxwk0phj30wf0u0dl9.jpg" alt="image-20200111205128704" style="zoom:50%;" />

- 现在可以进公众号看下成果了！

### 2 背后的原理

HTML是一门「标记性语言」，也就是我们通过标记来告诉浏览器如何去渲染页面。其中`<sth>`表示标记的开始，`</sth`表示标记的结尾。

因此，上面的代码我们就很好理解了。

```html
<html> # 网页从这里开始
  
  <head> # head 标签对内的是「头」部内容
    <title> # title 标签对内的是网页的标题
    	hello world
    </title>
  </head>
  
  <body> # body 标签对内的是网页正文
    <h1>Hello World!</h1> # 用字号1显示 Hello World!
  </body>
  
</html> # 网页到这里结束
```

### 3 小题目

1）复现上述内容，做第一个自己的网站。

2）通过阅读菜鸟教程，学习如何在网页中嵌入一张图像：

https://www.runoob.com/
