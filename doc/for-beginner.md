# 安装和环境

LaTeX的安装可以参考[这个文档](http://tug.ctan.org/info/install-latex-guide-zh-cn/install-latex-guide-zh-cn.pdf)，来自[install-latex-guide-zh-cn](https://github.com/OsbertWang/install-latex-guide-zh-cn)。

在安装完之后，为了使用`svg`包，还需要安装`inkscape`。

实际上很可能不止。。。作者不是从零开始安装环境的，有可能需求某个应用但是作者直接安装了，因此未被记录。总之大家可以提pr来补充。



# 编辑器

个人推荐使用vs code来编辑文档，你可以在code插件里搜索安装`LaTeX Workshop`。

之后建议几个配置（你可以通过`ctrl+alt+p`，然后输入`settings`找到用户设置，然后搜索来更改）：

`Latex-workshop > Latex: Out Dir`是生成结果文件的地方，建议改成`%DIR%/build`，因为`build`已经在`.gitignore`里面了。

`Latex-workshop > Latex > Auto Clean: Run`可以指定某些时候（比如编译完成时）将aux文件清除。
