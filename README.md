## flex
flex布局,每个属性的demo集合在index.html里面
HeaderFooterDynamic.html符合大多数后台的框架布局，急用的可以直接看这个页面，根据情况删减
喜欢用sass的应用sass，不喜欢的直接用css也是可以的

## grid
网格布局（Grid）是最强大的 CSS 布局方案。
Grid 布局与 Flex 布局有一定的相似性，都可以指定容器内部多个项目的位置。但是，它们也存在重大区别。

Flex 布局是轴线布局，只能指定"项目"针对轴线的位置，可以看作是一维布局。Grid 布局则是将容器划分成"行"和"列"，产生单元格，然后指定"项目所在"的单元格，可以看作是二维布局。Grid 布局远比 Flex 布局强大。

## 参考
[阮一峰关于flex的博客](http://www.ruanyifeng.com/blog/2015/07/flex-grammar.html)  
[sass入门](https://www.sass.hk/guide/)  
[windows tree目录命令](https://docs.microsoft.com/en-us/windows-server/administration/windows-commands/tree)  
[grid布局](https://www.ruanyifeng.com/blog/2019/03/grid-layout-tutorial.html)  
## tips
sass编译命令
```
sass --watch scss/flex.scss:css/flex.css scss/layout.scss:css/layout.css 
--style compact --sourcemap=none --no-cache
```

tree目录 
```
tree c:\ /f | more   或 tree  D:\repository\flex /f >tree.txt
```
## 目录
```
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
```