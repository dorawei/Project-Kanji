Workflow

一个Workflow的草案，希望大家多多提出意见来完善。


# 文本

## 领取任务

在Teambition主页有以目录划分的「翻譯列表（領取）」和「翻译进度」，在「翻譯列表（領取）」中勾选要翻译的章节，完成后在「翻译进度」中完成对应章节。

## 开始翻译之前

为了方便制作日文和中文的电子版，在翻译时同时进行日文原始文本的电子化。

结合OCR和手打，使用Markdown保存为UTF-8文本文件，完成后上传至Teambition→文件→Text Japanese→大章节号（如：511）

每一小章节为一单独文件，如`511-1`、`511-2`、`511-3`……

### 符号

数字、点和字母使用半角，中日文标点和`（）〔〕「」～・`等使用全角符号。

开头的方块使用「■」`Black Square U+25A0`和「□」`White Square U+25A1`。
段落缩进手动加一个全角空白「　」`Ideographic Space U+3000`。原文使用全角空白「　」`Ideographic Space U+3000`的時候文本文档中也使用全角空白「　」`Ideographic Space U+3000`。

### 图表的文本

有些表格过于复杂，全部使用图片格式可能更方便。

所以翻译在电子化和翻译图标时，单独将图标中的文本和译文以章节（同翻译的任务单位，如`511-1`）保存为文本文件供制图者使用。

从左至右，从上至下写出文本，同一行格子间的文字以「|」分开，以便制图者区分。

图表的文本文件上传至Teambition→文件→Images Text→Japanese→Part 1/2

如：

（名为543-2的文件，单个图表的编号命名请参照下面「图表的命名」）

```markdown
imgja-404

年代 | 中国社会と文字|字数|表現方法|書体
2|格子構造形成期|BC1300 BC206|殷 秦|

…（略）…

imgja-432-1

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

…（略）…

imgja-p72-1

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
```

### 图表的命名

图片使用`imgja-图片或表格编号.png`

如`imgja-404.png`或当一个编号下有多张图片时`imgja-440-1.png`。

当书中的图片或表格没有编号时使用`imgja-p页码-在当页未编号图标的顺序.png`，如`imgja-p42-2.png`。

例：

```markdown
□440 新聞活字，最初の本文偏平活字

1　森川龍文堂の最初の見本帳

![森川龍文堂の最初の見本帳](imgja-440-1.png "森川龍文堂の最初の見本帳")

2　岩田母型見本帳

![岩田母型見本帳](imgja-440-2.png "岩田母型見本帳")

3　2よる実際の朝日新聞

![2よる実際の朝日新聞](imgja-440-3.png "2よる実際の朝日新聞")
```

## 开始翻译

原始文本使用传统中文，异体字使用「爲、為」「羣、群」等可以随个人喜好（最后可以统一转换），「着」请不要使用「著」。

使用Markdown保存为UTF-8文本文件，完成后上传至Teambition→文件→Text Chinese→大章节号（如：511）

每一小章节为一单独文件，如511-1、511-2、511-3……

其实先按照上面的做好日文的电子化后，直接翻译文本就可以了。

### 符号

数字、点和字母使用半角，中日文标点和`（）〔〕「」～・`等使用全角符号。

开头的方块使用「■」`Black Square U+25A0`和「□」`White Square U+25A1`。
段落缩进手动加一个全角空白「　」`Ideographic Space U+3000`。原文使用全角空白「　」`Ideographic Space U+3000`的時候譯文也使用全角空白「　」`Ideographic Space U+3000`。

### 图表的翻译

单独将图标中的译文以章节（同翻译的任务单位，如`511-1`）保存为文本文件供制图者使用。

从左至右，从上至下写出文本，同一行格子间的文字以「|」分开，以便制图者区分。

图表的文本文件上传至Teambition→文件→Images Text→Chinese→Part 1/2

如：

（名为543-2的文件，单个图表的编号命名请参照下面「图表的命名」）

```markdown
imgzh-404

年代 | 中国社会和文字|字数|表现方法|字体
2 格子构造形成期|BC1300 BC206|殷 秦|

…（略）…

imgzh-432-1

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

…（略）…

imgzh-p72-1

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
```

### 图表的命名

图片使用`imgzh-图片或表格编号.png`，同日文编号规则，把imgja改为imgzh

如`imgzh-404.png`或当一个编号下有多张图片时`imgzh-440-1.png`。

当书中的图片或表格没有编号时使用`imgzh-p页码-在当页未编号图标的顺序.png`，如`imgzh-p42-2.png`。

例：

```markdown
□440 報紙活字，最初的正文扁平活字

1　森川龍文堂最初的樣本書

![森川龍文堂最初的樣本書](imgzh-440-1.png "森川龍文堂最初的樣本書")

2　岩田母型樣本書

![岩田母型樣本書](imgzh-440-2.png "岩田母型樣本書")

3　使用2排印的朝日新聞

![使用2排印的朝日新聞](imgzh-440-3.png "使用2排印的朝日新聞")
```

# 图片处理

当翻译完成一个小章节后，制图就可以按照翻译上传到Teambition→文件→Images Text→Japanese/Chinese中的文本文件来制作图片了。

## 任务领取和进度追踪

为了同样内容被重复制作，在开始制图前请先在任务面板的「制图（领取）」勾选自己要做的章节。完成后在「制图进度」完成相应章节。

## 文件命名

保持和翻译在文档中所用命名一致。

图片使用`imgja-图片或表格编号.后缀`（日文）命名，中文则把imgja改为imgzh

如`imgzh-404.psd`和`imgzh-404.png`或当一个编号下有多张图片时`imgzh-440-1.png`。

当书中的图片或表格没有编号时使用`imgzh-p页码-在当页未编号图标的顺序.png`，如`imgzh-p42-2.png`。

## 图片格式

图片的尺寸和文本格式等可以大家讨论一个统一的规范，同时导出一份PNG（或者其他待定）

## 文件上传

完成后上传至Teambition→文件→Images Japanese/Chinese→Part1/Part2

可编辑的如PSD等保存到Editable，导出的PNG图片保存到Export中。

**做好备份！**

# 后续

markdown导出为html，可以方便地制作成epub等电子书。

印刷版的制作似乎没有什么自动化的方式只能一章一章的手动排版？……
