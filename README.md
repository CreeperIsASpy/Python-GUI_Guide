# Python GUI 编程指南
>[!IMPORTANT]
> 本 repo 主要是 [必应专栏](https://zhuanlan.zhihu.com/p/347290491) 的转载、更新与记录。  
> 在此感谢专栏作者 [@平凡](https://www.zhihu.com/people/jzwa) ！  
> 也有几个转自 [Awesome-python 仓库中的 GUI 板块](https://github.com/vinta/awesome-python?tab=readme-ov-file#gui-development) 在此一并感谢！

>[!TIP]
> 这个 repo 是给我自己做备份用的，防止我什么时候脑残了又去拿`tkinter`去打圆角窗口……  
> 当然如果你看的高兴也可以给我点个 star :star: ！

| 库 / 框架名 |                                                                                                                             简介                                                                                                                            |                        主页链接                       | 优点                                                                                                                                                                             | 缺点                                                                                      |
|:-----------:|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|:-----------------------------------------------------:|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------|
| `tkinter`   | `Tk/Tcl`提供了一个强大、跨平台的窗口工具包，Python 程序员可通过`tkinter`包来方便地使用它。                                                                                                                                                                  | https://docs.python.org/3/library/tk.html             | 是python的内置库，无需额外下载，不存在兼容问题，且又非常详细的说明文档。                                                                                                         | 实现效果较为普通，已不再符合当前的 Unix 系统设计语言              |
| `wxPython`  | `wxPython`是一个创建桌面`GUI`应用的跨平台工具包，它的主要开发者是Robin Dunn。使用`wxPython`，开发者可以在`Windows`、`Mac`和多种`Unix`系统上开发应用程序。                                                                                                   | https://wxpython.org/                                 | 是一个免费的，可移植的GUI类库，用C++编写，可在Windows，Mac OS X，GTK，X11等许多平台上使用。可用于多种语言，包括Python，Perl，Ruby等。                                            | 设计的界面美观程度和灵活性较为普通                                                        |
| `PyQT6`     | `PyQt`是`Qt`框架的 Python 语言实现，由 _Riverbank Computing_ 开发，是最强大的GUI库之一。`PyQt`提供了一个设计良好的窗口控件集合，每一个`PyQt`控件都对应一个`Qt`控件，因此`PyQt`的 API 接口与`Qt`的 API 接口很接近，但`PyQt`不再使用`QMake`系统和`Q_OBJECT`宏。 | https://www.riverbankcomputing.com/static/Docs/PyQt6/ | 功能非常强大，可以用PyQt6开很漂亮的界面；另外它支持可视化界面设计，这点对新手非常友好。你可以通过拖动一些模块完成一些代码才能完成的工作，和`C++`的`QT`是一样的。 | 学习曲线陡峭，对新手开发难度相对高。配置和分发过程中有环境兼容性问题，对中文路径不友好。 |
| `PyGTK`     | `PyGTK`允许您用 Python 编写完整的`GTK`程序。它针对`GTK 2.x`，并可以与`gnome-python`一起使用来编写 Gnome 应用程序。 | https://pypi.org/project/PyGTK | 跟`PyQt`一样，可以实现很不错的效果，但是稍逊于`PyQt`，并且同样有可视化UI设计工具`Glade`。 | 更适合GNOME平台。 |
| `Kivy`     | Kivy 是一个开源的 Python 框架，用于快速开发应用，实现各种当前流行的用户界面，比如多点触摸等等。 Kivy 可以运行于 Windows， Linux， MacOS， Android， iOS 等当前绝大部分主流桌面/**移动端**操作系统。 | http://kivy.org/#home<br/>  [Kivy中文教程](https://cycleuser.gitbooks.io/kivy-guide-chinese/content/)<br/>  [Github Kivy项目](https://github.com/topics/kivy-application) | 界面文件和程序文件相互分离的设计思路简洁优雅，语法易学，适合新人入门；**支持移动端**。 | 只有一个中文文档，还不是特别全面，大多数教程仍为英文版本。 |
| `pyFLTK` | 一个致力于跨平台，快速开发，轻量化和容易使用的python GUI工具。 | http://pyfltk.sourceforge.io | 跨平台、轻量化 | 中文资料极为罕见！<br/>  ***真的很罕见*** |
| `Guietta` | 一个实现简单GUI的框架。 | [http://pyfltk.sourceforge.io](http://guietta.readthedocs.io/en/stable/) | 很优美、上手简单、容易理解，推荐。 | 中文文档很少。 |
