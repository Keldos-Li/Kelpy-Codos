# Kelpy Codos
为所有遵循 `<pre><code>代码块内容</code></pre>` 写法的网站的代码框增加复制按钮！

<img width="80%" alt="预览效果" src="https://user-images.githubusercontent.com/23137268/226910042-1a112a1f-c4e4-413d-87dd-7265847e7b74.png">

## 安装
1. 请确保您有 油猴脚本 或 Userscripts 等脚本管理器。
2. 点击[该链接](https://raw.githubusercontent.com/Keldos-Li/Kelpy-Codos/main/Kelpy%20Codos.js)。
3. 全选，然后复制。
4. 在您的脚本管理器中，新建用户脚本。如果您使用油猴脚本，效果可能如下图：
   <br /><img width="50%" alt="image" src="https://user-images.githubusercontent.com/23137268/226910804-a9ab738d-c2f9-4347-965d-9198cadd3de7.png"><br />
   删去编辑区中的所有内容，然后粘贴您在第3步中复制的内容。
5. <kbd>Ctrl</kbd>+<kbd>S</kbd>或<kbd>⌘</kbd>+<kbd>S</kbd>保存。

## 自定义
如果你发现脚本在不必要的网站中被启用了，要排除这些网站，请手动修改脚本，加上排除规则，例如：
```js
// @exclude      https://example.com/*
```
当然你也可以在油猴脚本的图像化设置页面中添加包括`@match`和`@include`在内的各种规则。

## 细节
原本的开发目的是给 [川虎Chat](https://github.com/GaiZhenbiao/ChuanhuChatGPT) 增加代码框复制按钮功能，不过，所有遵循 `<pre><code>代码块内容</code></pre>` 写法的网站的代码框也都会被执行该脚本而加上复制按钮。

- 因为已经找到了方法让 gradio 引入 js，该脚本已写入 川虎Chat。本项目将停止更新。

## 感谢
Thanks to [@Chuanhu](https://github.com/GaiZhenbiao) for developing the awesome [ChuanhuChat](https://github.com/GaiZhenbiao/ChuanhuChatGPT) and also inspiring my coding enthusiasm as a good friend~

另外，如果有用，请给我个 ⭐ ~
