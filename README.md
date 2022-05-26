# gui.cs

Enalbing modern, cross-platform, terminal UIs using .NET and Swift since 2007.

The gui.cs Github Organization holds the projects derived from [gui.cs](http://tirania.org/blog/archive/2007/Apr-16.html) that Miguel wrote for [mono-curses](https://github.com/mono/mono-curses) in 2007.

The original **gui.cs** was a UI toolkit in a single file and tied to curses. Since then, it has been transformed into **Terminal.Gui** which is console-agnostic and instead of having a container/widget model, only uses Views (which can contain subviews) and changes the rendering model to rely on damage regions instead of burdening each view with the details.

A presentation of this was part of the [Retro.NET](https://channel9.msdn.com/Events/dotnetConf/2018/S313) talk at .NET Conf 2018 [Slides](https://tirania.org/Retro.pdf)

The other projects in this organization are either dependencies of Terminal.Gui or related offshoots.
