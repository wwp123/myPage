 
<a href="https://wwp123.github.io/myPage/" target="_blank">可直接戳我进行预览哦~</a>

## 技术栈

juqery + foundation + less

## 说明

1. 此项目是响应式项目，使用foundation框架
2. 大中屏（> 640px）有4种布局可以切换，小屏（<= 640px）有2种布局可以切换，主要是利用masonry这个组件。
3. 可进行背景图片和主页色调的切换。variable.less文件用来定义整个项目的色调、背景、字体、间距、边框等less变量，themes.less通过@import "variable.less";并调用这些变量，所以只要改变这些变量的值就能改变整个项目的展示效果了。我正是通过js去改变各个色调的值，包括背景色、主色、面板色、字体颜色，去进行页面色调的切换的。（ps.没有精心去配色，只是随意拉取几个颜色，所以配色可能有点丑~）
