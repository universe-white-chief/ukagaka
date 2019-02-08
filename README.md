ukagaka
=======
來自 http://www.lmyoaoa.com/inn/archives/4504/ 的僞春菜  
原作者 [油饼小明猪](http://www.lmyoaoa.com/inn/)  
该项目原先为 php 的程序，在问过原作者的后，我把它拔下来，改成了纯静态的项目。  

##### 修改内容如下：  

1. 封装成对象  
2. 将原项目分开成 wcc 和 ghost 两部分，以方便以后添加 ghost  
3. 封装进一个 js 文件中  

2016.8.18  
在发现这个项目之后   
我会对角色和语言进行自定义的二次开发主要自用  
By sddtc.

#### 如何在自己的网站中使用
由于 `rawgit` 已经停止运营，那么该项目主要需要的两个文件: `css/style.css` 和 `js/common.js` 需要找到一个可用的链接放到你的网站或者博客中  
现阶段我们可以用这两个链接引用：  
```
https://cdn.jsdelivr.net/gh/universe-white-chief/ukagaka/css/style.css
https://cdn.jsdelivr.net/gh/universe-white-chief/ukagaka/js/common.js
```

如果你新 `fork` 了自己的项目，那么链接怎么生成呢？
请参考这个链接的第一个答案: https://stackoverflow.com/questions/17341122/link-and-execute-external-javascript-file-hosted-on-github  
```
https://cdn.jsdelivr.net/gh/<username>/<repo>/path/to/file.js
```
