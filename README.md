
# IDEA

## 快捷键
- Alt + Enter : 结合上下文，显示error的fix信息；代码补全； lambda表达式生成
- Alt + 1 : 打开/关闭项目窗口
- F2 : 快速定位报错行
- Alt + 1: 快速定位到项目窗口
- Ctrl + E : 显示最近修改的文件，最近打开的窗口区域
- Ctrl + B  ｜ Ctrl + Alt + B: 快速导航至类定义，接口实现定义
- Alt + F7 ： 定位类、方法在哪里用到了
- Ctrl + Ctrl : 快速运行命令
- Ctrl + / ｜ Ctrl + Shift + /  : 注释
- Ctrl + Shift + Enter  : 自动定位到降到写代码的地方
- Ctrl + Alt + L: 格式化代码
- Ctrl + Shift + Alt + T  : 重构代码
- Ctrl + Shift + A : 查找action操作
- Shift + Shift : 查找
- Ctrl + Shift + I : 显示当前CSS选择器或者JS函数的详细信息
- Ctrl + Shift + 空格 : 代码提示
- CTRL+D : 比较两个文件或文件夹，在项目窗口中选中，再按CTRL+D

- Esc : 在任何工具窗口中按Esc都会将焦点移至编辑器。
- Shift + Esc : 按 Shift+Esc 可将焦点移至编辑器，并隐藏当前或最后一个活动工具窗口。
- F12: 按 F12 可将焦点从编辑器移至上次聚焦的工具窗口。

## 必装插件
- IdeaVIm ： Vim模式
- Alibaba Java Coding Guidelines : 代码规范
- CodeGlance : 在右侧生成一个代码缩略图
- Grep Console: 控制台log带颜色输出
- Key Promoter X：快捷键提示工具，当你忘记快捷键而在IDE内的按钮上使用鼠标时，Key Promoter X会显示您应该使用的键盘快捷键。并在右下角提示；
- MyBatis Log Plugin：MyBatis日志插件，强烈推荐，将mybatis sql日志还原到原始的整个可执行sql，可以直接复制使用执行；
- JRebel and XRebel for IntelliJ：热部署插件，非常强大好用，但是要破解或者购买
- Code With Me
- Maven Helper

收费的Jrebel(热部署)、
MyBatisCodeHelperPro(联想生成mapper.xml、逆向工程)、
MybatisLogPlugin(控制台拼接SQL语句)
免费的CamelCase(大小写和下划线单词互相转换)、
POJO to JSON(实体类转JSON)、
RestfulToolKit(查询项目url)、
jclasslib bytecode viewer(字节码查看工具)






# WebStorm配置

[ WebStorm“奇技淫巧” ](https://github.com/YutHelloWorld/Blog/issues/8)


## 必装插件
- AceJump ：跳转到指定代码位置
- IdeaVIm ： Vim模式
- IdeaVimExtension : 为ieadvim插件自动切换英文输入法的功能, 设置模式 `set keep-english-in-normal`
- Codota : 快速的编写Nodejs代码。

## 其他插件
- CodeGlance : 在右侧生成一个代码缩略图
- Rainbow Brackets : 实现括号配对 (慎用，安装后打开项目后会一直加载，很慢)
- Json Parser : 直接在IDE中进行格式化JSON
- Material Theme UI
- IDE Features Trainer : 会对IDE中的一些快捷键


## 快捷键
### 导航
- alt + 向下箭头 ： 跳转下一个函数
- alt + 向上箭头 ： 跳转上一个函数
- alt + 向左箭头 ： 跳转左边标签
- alt + 向右箭头 ： 跳转右边标签
- ctrl + alt + 向左箭头 ： 光标跳转到上一次的位置
- ctrl + alt + 向右箭头 ： 光标跳转到下一次的位置

### TOP 5 IntelliJ IDEA Navigation Shortcuts
- 2x Shift -> search everywhere
- Ctrl + E -> recent files
- Alt + F7 -> find usages
- Ctrl + Alt + B -> Go to implementation(s)
- Ctrl + Shift + T -> navigate to test
- 鼠标选中文本后，按住Ctrl +Shift + U 大小写转换
- 多点选中， 鼠标选中文本后，按住Alt + J可以同时选中相同的文本进行编辑，按住Alt +Shift+ J可以取消选中。
      这个快捷键的名字叫：Add Selection for Next Occurrence，可以在file>Settings中进行搜索，修改成其他快捷键。


### 折叠
- 可以通过 ctrl+F12直接显示一个弹出层，里面只有这个类的属性和方法，点击就能快速定位了。
- `Ctrl`+`Shift`+`-`，折叠所有代码
- `Ctrl`+`Shift`+`+`，展开所有代码。

### 文件
- ctrl + shift + F12 关闭/打开左侧导航和底部窗口
- Ctrl + E  最近打开的文件
- ctrl + alt + 12 文件路径

### 查找替换
 - ctrl + f: 查找
 - ctrl + shift + f: 全局查找
 - ctrl + R: 替换
 - ctrl + shift + r: 全局替换

### 代码定位
 - 选中文本，按 Ctrl + Shift + F7 高亮显示所有该文本，按Esc高亮消失。
 - F2 或 Shift+F2	高亮错误或警告快速定位
 - Alt + Up/Down	Go to previous/next method 跳转到上一个/下一个方法
 - ctrl + []: 匹配 {}[]
 - Ctrl + B: 快速打开光标处的类或方法 或 Ctrl + 鼠标左键单击
 - Ctrl + Alt + B -> Go to implementation(s) 跳转方法实现处

### 代码预览
 - ctrl + P	方法参数提示
 - Ctrl + Shift + I	Open quick definition lookup 打开定义快速查找,小窗口预览定义
 - ctrl + F12 文件结构



 - ctrl + shift + n: 打开工程中的文件，目的是打开当前工程下任意目录的文件。
 - ctrl + j: 插入代码片段(Code Snippet)，输出模板
 - ctrl + alt + T: 围绕包裹代码(包括zencoding的Wrap with Abbreviation)
 - ctrl + F12: Outline, 可以显示当前文件的结构
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

 - Ctrl+/ 或 Ctrl+Shift+/	注释（// 或者/*…*/ ）
 - Shift+F6	重构-重命名
 - Ctrl+X	删除行
 - Ctrl+D	复制行
 - Ctrl+G	查找行
 - Ctrl+Shift+Up/Down	代码向上/下移动。
 - F2 或Shift+F2	高亮错误或警告快速定位
 - 写代码，按Tab	生成代码
 - 选中文本，按Ctrl+Shift+F7	高亮显示所有该文本，按Esc高亮消失。(因为这个功能我就可以发放心的放弃sublime了)
 - Ctrl+B或Ctrl+鼠标左键单击	快速打开光标处的类或方法，（NB的功能）
 - Ctrl + Alt + B	Go to implementation(s) 跳转方法实现处
 - Ctrl + Shift + I	Open quick definition lookup 打开定义快速查找
 - Alt + Up/Down	Go to previous/next method 跳转到上一个/下一个方法
 - Ctrl+E	最近打开的文件
 - Alt+F1	查找代码所在位置
 - Ctrl+Alt+L	格式化代码
 - Ctrl+R	替换文本
 - Ctrl+F	查找文本
 - Ctrl+P	方法参数提示
 - F3	查找下一个
 - Shift+F3	查找上一个
 - alt+Shift+F	将当前文件加入收藏夹
 - ctrl+alt+s	打开配置窗口
 - ctrl+Shift+N	通过文件名快速查找工程内的文件（必记）
 - ctrl+Shift+alt+N	通过一个字符快速查找位置（必记）
 - Shift+enter	重新开始一行（无论光标在哪个位置）
 - Ctrl + Alt + T 	with…（if, else, try, catch, for, etc）用 * 来围绕选中的代码行，（ * 包括 if 、 while 、 try catch 等）
 - Ctrl + Shift + U	Toggle case for word at caret or selected block 光标所在位置大小写
 - Ctrl + Delete	Delete to word end 删除文字结束
 - Ctrl + Backspace	Delete to word start 删除文字开始
 - Ctrl + E	Recent files popup 弹出最近打开的文件
 - F11	Toggle bookmark 切换标记，我觉得叫书签更好，就是sublime text 的F2
 - Ctrl + Shift + F12	Toggle maximizing editor 切换最大化编辑器
 - Alt + Shift + F	Add to Favorites 添至收藏夹


### Webstorm debugger for node.js doesn't connect for executed node.js process

解决： Must be https://youtrack.jetbrains.com/issue/WEB-40496; please try disabling js.debugger.use.node.options key in Registry (Help | Find action, type Registry to locate it) - does it make things any better?


[详解配置Visual Studio/Webstorm来调试JavaScript](https://cloud.tencent.com/developer/article/1563419)


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
 - Vetur: vue支持、Vue格式化工具
 - eslint 
 - IntelliSense for CSS class names in HTML : css提示
 - Path Intellisense： 路径提示
 - npm Intellisense
 - wxml: 微信小程序wxml格式化及高亮组件
 - minapp ： 微信小程序标签、属性的智能补全（同时支持原生小程序、mpvue 和 wepy 框架，并提供 snippets）
 - 微信小程序开发工具
 - Rem rpx px -Converter
 - 小程序助手
 - DotEnv : 支持dotenv文件，语法高亮
 - Multiple Cursor : 代码自动生成

 
 - Javascript Snippet
 - HTML Snippets
 - wechat-snippet
 - vue 2 Snippets
 
## Cursor

 - Tab 代码补全功能：生成，修复，重构代码
 - 提示框（cmd + k）: 生成 or 修改局部（当前文件）代码
 - 聊天（cmd + L / option + command + B）：新增功能 ，更广泛代码问题对话的地方
 - @ 符号：它是用来引用一些东西，算是通过关联更重要的上下文来得到更准确的回复

作者：幸运蜗牛
链接：https://juejin.cn/post/7440482461762601010
来源：稀土掘金
著作权归作者所有。商业转载请联系作者获得授权，非商业转载请注明出处。


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


