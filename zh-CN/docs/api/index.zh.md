# 主题

&gt;&gt;&gt; python -m ttkbootstrap 任何未在此库中专门定义的小部件或功能都可以在 [其他参考](#other-references) 中找到。

## 颜色
ℹ️ [了解更多关于样式化遗留小部件的信息](legacywidgets.md)。

## 🎨 示例主题
该模块包含各种基本对话框基类（以“Dialog”结尾），可用于为最终用户创建自定义对话框。 这些基类作为 `Messagebox` 和 `Querybox` 容器类中预定义的静态帮助方法的基础，其中包括许多预定义的消息和查询对话框配置。

下面关键字的实际颜色值为 [在每个特定主题中定义](../themes/definitions.md)，但是 下面的描述是您通常可以从每个颜色关键字中获得的内容。

## 🈚 本地化模块
此模块包含为您的应用程序提供表情符号或图像图标的类。 它们可以在文本中用作`图标`或在`PhotoImage`类中用作`图标`。

❯ [表情符号](icons/emoji.md) ❯ [图标](icons/icon.md)

## 📜 滚动模块
该模块包括用于本地化 gui 小部件中的文本的方法和类。 [需要您的帮助](https://github.com/israel-dryer/ttkbootstrap/blob/master/src/ttkbootstrap/localization/msgs/README.md)来添加用于翻译文本的 msg 文件！

## 🎨 样式模块
❯ [ScrolledFrame](scrolled/scrolledframe.md) ❯ [ScrolledText](scrolled/scrolledtext.md)

该模块包含各种滚动小部件，例如 `ScrolledText` 和 `ScrolledFrame`。

## 🪟 [tableview 模块](tableview/tableview.md)
该模块包含构成 ttkbootstrap 主题和样式引擎的类。 根据您使用 ttkbootstrap 的方式，您可能永远不需要直接使用这些类中的任何一个，但话又说回来，您可能会这样做，因此这里的文档供您参考。

您还可以查看 [浅色主题](light.md) 和 [深色主题](dark.md) 的屏幕截图。

## 🛎️ [toast 模块](toast.md)
该模块有一个名为`ToastNotification`的类，它为临时警报或消息提供了一个半透明的弹出窗口。

## 📝 [工具提示模块](tooltip.md)
这个模块包含一个同名的类，它提供了一个半透明的工具提示弹出窗口，当鼠标悬停在小部件上时显示文本，当鼠标不再悬停在小部件上时关闭。

## ☑️ 小部件模块
此模块包含下面链接的自定义 ttkbootstrap 小部件。

## 🗔 窗口模块
ttkbootstrap 附带了许多风格精美的浅色和深色主题，您可以在 _安装 ttkbootstrap 后_ 在终端中键入此命令，在演示中查看这些主题。

✔️ [**许多新的小部件：**](api/widgets/dateentry)  
ttkbootstrap附带了几个设计精美的新小部件，如[Meter](api/widgets/meter)，[DateEntry](api/widgets/dateentry)和[Floodgauge](api/widgets/floodgauge)。

## ⚙️ [实用模块](utility.md)
该模块包含一个同名的类，包装了`tkinter.Tk`和[Style](style/style.md)类，为初始应用程序启动提供更方便的api。 这也适用于 `Toplevel` 类。

❯ [窗口](window/window) ❯ [顶级窗口](window/toplevel)


## ❓其他参考
该模块包括对最终用户可能有用也可能没有用的各种实用功能。 单击标题以阅读更多信息。

## ❓other references
此 api 参考不包括从 **tkinter** 继承的类、方法和函数。 要了解有关如何使用 tkinter 的更多信息，您可以查阅下面列出的任何资源：

❯ [docs.python.org](https://docs.python.org/3/library/tkinter.html) ❯ [tkdocs](https://tkdocs.com/) ❯ [pythontutorial.net](https://www.pythontutorial.net/tkinter/) ❯ [anzeljg](https://anzeljg.github.io/rin2/book2/2405/docs/tkinter/) ❯ [tcl/tk](https://www.tcl.tk/man/tcl8.6/TkCmd/contents.html)  