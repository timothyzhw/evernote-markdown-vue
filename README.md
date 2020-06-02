# evernote-markdown-vue-theme


> Evernote印象笔记Markdown自定义主题，基于[typora-vue-theme](https://github.com/blinkfox/typora-vue-theme) 修改。

## 简介

[Evernote 印象笔记](https://www.yinxiang.com/)是一款超好用的笔记软件，尤其最近新增的[Markdown](https://help.yinxiang.com/hc/articles/69276?preview=hctop)笔记更是满足了更多笔记的需求。但相对于专业的Markdown编辑器Typora，还是有很大差距。尤其是样式一般，目前还不能更换自定义主题。

在macOS中，Markdow的显示使用了安装包中的`/Applications/印象笔记.app/Contents/Resources/common-markdown-mac/index.html`文件，在这个文件中添加新的css引用<link href="/Users/xxx/github/evernote-markdown-vue/vue.css" rel="stylesheet">，覆盖原有样式表，便可以随心修改样式。

本主题的样式是在[typora-vue-theme](https://github.com/blinkfox/typora-vue-theme)的基础上，做了简单修改，并添加了代码样式[github-gist](https://github.com/highlightjs/highlight.js/blob/master/src/styles/github-gist.css)。

## 使用方法

1. 下载本主题中的`vue.css`文件和包含字体的`vue`文件夹；
2. 修改印象笔记的文件 vi /Applications/印象笔记.app/Contents/Resources/common-markdown-mac/index.html，在最后一行`</html>`前插入
```
<link href="/Users/xxx/github/evernote-markdown-vue/vue.css" rel="stylesheet">
```
3. 重新打开印象笔记

## 效果图

![效果图](https://github.com/timothyzhw/evernote-markdown-vue/blob/master/snapshot.jpg)

## 示例文件
我整理了一个[Makdown文件](https://raw.githubusercontent.com/timothyzhw/evernote-markdown-vue/master/Markdown.md)，包含了Evernote支持的大部分样式，如果想要调整样式查看整体的显示效果，用这个文件做示例是个不错的选择。