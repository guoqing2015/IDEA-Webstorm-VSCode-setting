
# WebStorm配置

[ WebStorm“奇技淫巧” ](https://github.com/YutHelloWorld/Blog/issues/8)


## 必装插件
- AceJump ：跳转到指定代码位置
- IdeaVIm ： Vim模式
- IdeaVimExtension : 为ieadvim插件自动切换英文输入法的功能
- CodeGlance : 在右侧生成一个代码缩略图
- Rainbow Brackets : 实现括号配对
- Json Parser : 直接在IDE中进行格式化JSON
- Material Theme UI
- IDE Features Trainer : 会对IDE中的一些快捷键
- Codota : 快速的编写Nodejs代码。

## 快捷键
### navigate
- alt + 向下箭头 ： 跳转下一个函数
- alt + 向上箭头 ： 跳转上一个函数
- alt + 向左箭头 ： 跳转左边标签
- alt + 向右箭头 ： 跳转右边标签

### Top 5 IntelliJ IDEA Navigation Shortcuts
- 2x Shift -> search everywhere
- Ctrl + E -> recent files
- Ctrl + Alt + B -> navigate to implementation
- Alt + F7 -> find usages
- Ctrl + Shift + T -> navigate to test

##
- ctrl + shift + F12 关闭/打开左侧导航
- ctrl + F12 文件结构
- ctrl + alt + 12 文件路径

### 
 - ctrl + f: 查找
 - ctrl + shift + f: 全局查找
 - ctrl + r: 替换
 -  ctrl + shift + r: 全局替换

 - ctrl + shift + n: 打开工程中的文件，目的是打开当前工程下任意目录的文件。
 - ctrl + j: 输出模板
 - ctrl + b: 跳到变量申明处
 - ctrl + alt + T: 围绕包裹代码(包括zencoding的Wrap with Abbreviation)
 - ctrl + []: 匹配 {}[]
 - ctrl + F12: 可以显示当前文件的结构

 - ctrl + shift + up: 行移动
 - shift + alt + up: 块移动(if(){},while(){}语句块的移动)
 - ctrl + shift + ]/[: 选中块代码
 - ctrl + / : 单行注释
 - ctrl + shift + / : 块注释
 - ctrl + shift + i : 显示当前CSS选择器或者JS函数的详细信息
 - ctrl + '-/+': 可以折叠项目中的任何代码块，它不是选中折叠，而是自动识别折叠。
 - ctrl + '.': 折叠选中的代码的代码。
 - shift + esc: 当前激活的任意小窗口最小化，也可以是alt+数字键，数字在小窗口有显示。
 - alt + '7': 显示当前的函数结构。
 - 如果是*.html页面，则在文件名下的导航栏某DOM结构上右键，可以全选当前DOM结构。

# VScode 的配置

## 配置文件

- keybinding.json
- snippets

## 快捷键

 multiline editing： 
	1. On Windows, you hold Ctrl+Alt while pressing the up ↑ or down ↓ arrow keys to add cursors. On Mac and Linux, the equivalents are ? Opt+? Cmd+↑/↓ and Shift+Alt+↑/↓, respectively.

   2. 按住alt键，在你想要的位置上点击一下，即可增加的一个光标。

   3. Ctrl + F, 输入你想要查找的单词，按下Alt + Enter, 即可全局编辑

- Shift + Alt + F 格式化代码   

## 必装插件
 - vim
 - Code Outline : 查看代码结构
 - vscode-icos ：让文件类型一目了然
 - Project Manager ：管理项目
 - Beautify ： 格式化代码
 - vue-beautify
 - Debugger for Chrome
 - eslint 
 - IntelliSense for CSS class names in HTML : css提示
 - Path Intellisense： 路径提示
 - npm Intellisense
 - Vetur : vue 支持
 - wxml: 微信小程序wxml格式化及高亮组件
 - minapp ： 微信小程序标签、属性的智能补全（同时支持原生小程序、mpvue 和 wepy 框架，并提供 snippets）
 - 微信小程序开发工具
 - Rem rpx px -Converter
 - 小程序助手
 - DotEnv : 支持dotenv文件，语法高亮
 - koroFileHeader ： 自动注释插件设置
 
 - Javascript Snippet
 - HTML Snippets
 - wechat-snippet
 - vue 2 Snippets
 

## 排除文件设定
搜索期间需要忽略的一些文件夹 `.vscode/setting.json`,

```
{
    // ...
   "search.exclude": {
       "**/.git": true,
       "**/node_modules": true,
       "**/bower_components": true,
       "**/tmp": true
    },
    // ...
}
```


