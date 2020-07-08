# flex
flex布局,每个属性的demo集合在index.html里面
HeaderFooterDynamic.html符合大多数后台的框架布局，急用的可以直接看这个页面，根据情况删减
喜欢用sass的应用sass，不喜欢的直接用css也是可以的
# 参考
[阮一峰关于flex的博客](http://www.ruanyifeng.com/blog/2015/07/flex-grammar.html)  
[sass环境](https://www.sass.hk/install/)  
[sass入门](https://www.sass.hk/guide/)
[windows tree目录命令](https://docs.microsoft.com/en-us/windows-server/administration/windows-commands/tree)
# tips
-sass编译命令
```bash
sass --watch scss/flex.scss:css/flex.css scss/layout.scss:css/layout.css 
--style compact --sourcemap=none --no-cache
```

-tree目录 
```bash
tree c:\ /f | more   或 tree  D:\repository\flex /f >tree.txt
```
# 目录
<pre>
.
│   columnsAllDynamic.html
│   HeaderFooterDynamic.html  //上手用的直接看这个文件
│   index.html
│   menuAndContentDynamic.html
│   menuAndContentDynamic2.html
│   MenuContentHeaderFixed.html
│   menuFixedContentDynamic.html
│   MenuFixedContentHeaderDynamic.html
│   menuFloating.html
│   README.md
│
├───css
│       flex.css
│       layout.css
│
├───imgs
│       cat.jpg  //练习报纸排版文字包围图片的demo，与flex布局无关，可删去
│
└───scss
        flex.scss
        layout.scss
        mixin.scss  //练习sass的个人demo，与flex布局无关，可删去
        _test1.scss //练习sass的个人demo，与flex布局无关，可删去
        </pre>