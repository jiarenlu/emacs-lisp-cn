说明：
========

本工程用于翻译EMACS Lisp的说明文档，以便帮助渴望更深一步了解Emacs Lisp的朋友，目前由我个人进行翻译，欢迎有相同爱好的朋友加入到翻译工作上来。

目录结构说明
========

* lispref：翻译后的Texinfo源文件。
* orig：原始Texinfo源文件，用于校对。
* README：读我文件。

更新记录
========

* 20110804
增加ELISP翻译工程至GITHUB，以便更好地进行版本控制，同时，也便于寻找志同道合的兄弟一同协作翻译。
* 20110807
修正了一下makefile，将生成elisp.html的命令合入，修改完毕后，可以直接在lispref目录下执行rm elisp.html;make elisp.html生成新的html文档即可。
* 20111124
更新README语法为MARKDOWN。

遗留问题
=========

* texi2pdf不支持包含中文的texi文件，因此暂无法生成中文pdf，测试发现生成pdf中，中文全部消失不见。