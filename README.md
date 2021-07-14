### VScode目前已成为前端开发者中最受欢迎的编辑器之一，依靠其轻型的体量与强大的拓展性，安装适合的插件有助于我们提高我们的开发效率，这里推荐一些我常用的插件
***************************************
1. `Chinese (Simolified) Language Pack for Visual Studio Code` 翻译插件，可以将VScode的语言换为中文，适合英语不好的小伙伴(我在写这篇文章时发现下载最新版VScode后已会提示是否将语言更换为中文，此处就是通过下载该插件来实现语言转换）。
2. `Comment Translate` 基于*Google Translate API*的插件，其功能为：
 (1)识别代码中的注释部分，不干扰阅读，支持不同语言，单行、多行注释。
 (2)支持用户字符串与变量翻译，支持驼峰拆分。
 (3)选择区域翻译-划词翻译。
 (4)翻译并替换选择内容。
 (5)选中最后一次翻译区域命令。
3. `Live Server` 一个具有实时加载功能的小型服务器，可以使用它来破解html/css/javascript，但是不能用于部署最终站点。也就是说我们可以在项目中实时用live-server作为一个实时服务器实时查看开发的网页或项目效果。
4. `open in browser` 将当前文件在浏览器打开(可自己选择打开的浏览器，默认浏览器是系统默认浏览器),不过安装live server后这个插件没有什么必要。
5. `Auto Rename Tag` 一个自动同步修改前后标签名的插件，在实际项目开发中代码量巨大，有些前后标签难以查找，一旦修改标签名想找到对应的后标签，此插件可避免浪费不必要的时间。
6. `Bracket Pair Colorizer 2` 为代码中各对括号提供颜色高亮等功能，具体设置可在拓展商店中查看。
7. `CSS Peak` 安装完成后打开HTML文件，按住ctrl键同时移到鼠标到要查看样式的类上就可以看到该类的定义了。跳转到样式的定义，按住ctrl键同时点击样式类的名称或者在类的名称上按F12键即可跳转到样式的定义。
8. `EmbaddedBrowser` VScode内嵌浏览器，使用方法为在命令面板[^1]输入Open Browser。
9. `HTML CSS Support` 支持HTML id和class属性补全提示。
10. `Markdown Preview Enhanced` 一款超级强大的Markdown插件，快捷键 cmd+k 然后按v，或者cmd+shift+v(cmd对应win下的ctrl)即可打开预览，此插件可以做到自动滚动同步、PDF导出等功能。
11. `Prettier - Code formatter` 一个代码格式化工具，使用方法为打开命令面板[^1]，然后输入Format Document，为确保此扩展用于您可能已安装的其他扩展，请务必在 VS Code 设置中将其设置为默认格式化程序。可以为所有语言或特定语言设置此设置。
```
{
	"editor.defaultFormatter": "esbenp.prettier-vscode",
	"[javascript]": 
	{
		"editor.defaultFormatter": "esbenp.prettier-vscode"
	}
}
```
12. `Vetur` VSCode下强大的Vue开发工具，为Vue提供了语法高亮、语义高亮、片段、格式化等功能。
13. `Volar` Vetur的继任者，是一个专为 Vue 3 构建的语言支持插件，它基于@vue/reactivity按需计算 TypeScript 来优化类似于原生 TypeScript 语言服务的性能。目前还在开发中，未来应该会取代Vetur。
14. `background` 此插件用于更换VScode背景，可以的需求改变背景图片、图片透明度等，更改完重启VScode后顶部会出现“不受支持”的符号。
15. `Fix VSCoode Checksums` 用于解决出现“不受支持”字符的问题，安装后在命令面板[^1]中输入
```
Fix Checksums: Apply
```
[^1]:命令面板的打开方式为cmd/ctrl+shift+p
