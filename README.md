# SCUT_Latex_template

这是一份华南理工大学本科学位论文的Latex模板，也可以在此基础上进行修改，用作平时的课程报告。

以下为详细说明。

## 说明

在使用一份来自网络的[华工Latex模板](https://pan.baidu.com/s/1qYSAvec#list/path=%2F&parentPath=%2F)时发现有一些不合理的内容以及宏包冲突的部分，因此对其进行了优化，得到本模板。在此向提供原模版的作者表示感谢。

此模板以学校提供的word模板为标准进行编写，最终得到效果较为理想。效果可以参考文件：`SCUT_Latex_Template.pdf`

尽管如此，仍存在一些不尽如人意的地方。因此将项目开源，集众智、聚群力，共同维护完善本模板。

下面将分别介绍模板的项目结构、使用方法，最后给出我的开发环境与参阅的资料，以供参考。

## 项目结构

```tex
SCUT_LATEX_TEMPLATE
    │  LICENSE  % MIT LICENSE
    │  README.md  % 说明文档
    │  SCUT_Latex_Template.aux  % 辅助文件，用于存储交叉引用信息的文件
    │  SCUT_Latex_Template.fdb_latexmk  %  辅助文件
    │  SCUT_Latex_Template.fls  %  辅助文件
    │  SCUT_Latex_Template.log  % 日志文件，记录上次编译的信息
    │  SCUT_Latex_Template.out  % hyperref宏包生成的pdf书签记录
    │  SCUT_Latex_Template.pdf  % 输出的pdf文件
    │  SCUT_Latex_Template.synctex.gz  %tex文件编译后产生的文件
    │  SCUT_Latex_Template.tex  % 源文件
    │  SCUT_Latex_Template.toc  % 目录记录文件
    │  SCUT_Latex_Template.xdv   %XeTeX编译中间过程文件
    │  官方的word模板.pdf  % 参照的标准（pdf版）
    │  官方的word模板.doc  % 参照的标准（word版）
    │  开发者文档.md  % 记录开发过程中的问题
    │
    ├─fig % 存放图像文件夹
    │      SCUT.jpg  % 封面图象
    │
    └─开发者文档.assets  %  开发者文档.mdf 辅助文件
```

## 使用方法

1. 使用者：

    打开`SCUT_Latex_Template.tex`文件，对里面的一些基本内容修改为自己的，之后采用 ` XeLaTeX`编译即可。

    建议将所有图像放在 `fig` 文件夹下。

2. 开发者：

    一些我想做但是没有做的事情，以及制作过程中踩过的坑，已经放在 `开发者文档.md` 中，我们可以一起写下去，让代码更加完善！

## 开发环境

`Win10 `+ `Sublime Text 3` + `SumatraPDF`

## 参考资料

[中文文档《lshort-zh-cn》](https://mirrors.cqu.edu.cn/CTAN/info/lshort/chinese/lshort-zh-cn.pdf)

## 链接

本项目的 GitHub 地址：https://github.com/VicoZhang/SCUT_Latex_template.git

本项目的 Gitee 地址：https://gitee.com/vico_zhang/SCUT_Latex_template.git

## 最后

鉴于本人学识，程序编写不可避免有不尽完善的地方，恳请批评指正！
