---
layout：post
title：Win10 快捷键总结      
date：2019-8-23    
tags：[]    
categories：   
---


嗨！我对你们的第一次降价文件** StackEdit **。如果你想了解StackEdit，你可以读我。如果你想玩Markdown，可以编辑我。完成后，您可以通过打开导航栏左下角的**文件浏览器**来创建新文件。


＃文件

StackEdit存储您的文件在您的浏览器，这意味着您的所有文件会自动保存到本地，都可以访问**下线！**

## 创建文件和文件夹

可以使用导航栏左下角的按钮访问文件资源管理器。您可以通过单击文件资源管理器中的**新文件**按钮来创建新文件。您还可以通过单击**新文件夹**按钮创建文件夹。

## 切换到另一个文件

您的所有文件和文件夹都以文件资源管理器中的树形式显示。您可以通过单击树中的文件从一个切换到另一个。

## 重命名文件

您可以通过单击导航栏中的文件名或单击文件资源管理器中的**重命名**按钮来重命名当前文件。

## 删除文件

您可以通过单击文件资源管理器中的**删除**按钮来删除当前文件。该文件将被移动到** Trash **文件夹中，并在7天不活动后自动删除。

## 导出文件

您可以通过单击菜单中的**导出到磁盘**来导出当前文件。您可以选择将文件导出为纯降价，使用把手模板或PDF作为HTML导出。


＃同步

同步是StackEdit的最大特色之一。它使您可以将工作区中的任何文件与存储在** Google Drive **，** Dropbox **和** GitHub **帐户中的其他文件同步。这使您可以继续在其他设备上书写，与共享文件的人协作，轻松集成到您的工作流程中......同步机制在后台每分钟进行一次，下载，合并和上传文件修改。

有两种类型的同步，它们可以相互补充：

- 。工作区同步将自动同步所有文件，文件夹和设置这将允许您在任何其他设备上获取工作区>要开始同步工作区，只需在菜单中使用谷歌登录即可.-文件同步将使用工作区的一个文件与** Google Drive **，** Dropbox **或** GitHub **中的一个或多个文件同步。>在开始同步文件之前，您必须在**同步**子菜单中链接一个帐户。





## 打开一个文件

您可以从打开文件**谷歌驱动器**，** Dropbox的**或** GitHub的**通过打开**同步**子菜单，然后点击**从打开**。在工作区中打开后，文件中的任何修改都将自动同步。

## 保存文件

您可以保存工作区中的任何文件**谷歌驱动器**，** Dropbox的**或** GitHub的**通过打开**同步**子菜单，然后点击**节省**。即使工作区中的文件已同步，您也可以将其保存到其他位置.StackEdit可以将一个文件与多个位置和帐户同步。

## 同步文件

一旦您的文件链接到同步位置，StackEdit将通过下载/上传任何修改定期同步它。如有必要，将执行合并，并解决冲突。

如果您刚刚修改了文件并想要强制同步，请单击导航栏中的**立即同步**按钮。

> **注：**的**立即同步**按钮是无效的，如果你没有文件同步。 

## 管理文件同步

由于一个文件可以与多个位置进行同步，你可以列出并通过单击管理同步位置**文件同步**的**同步**子菜单。这允许您列出和删除链接到您的文件的同步位置。


＃出版

在StackEdit中发布使您可以轻松地在线发布文件。一旦您对文件感到满意，您就可以将其发布到不同的托管平台，例如** Blogger **，** Dropbox **，** Gist **，** GitHub **，** Google Drive **，*                                                                                                                                             * WordPress **和** Zendesk **。使用[Handlebars templates]（http://handlebarsjs.com/ ），您可以完全控制导出的内容。

> Before starting to publish, you must link an account in the **Publish** sub-menu.

## Publish a File

You can publish your file by opening the **Publish** sub-menu and by clicking **Publish to**. For some locations, you can choose between the following formats:

- Markdown: publish the Markdown text on a website that can interpret it (**GitHub** for instance),
- HTML: publish the file converted to HTML via a Handlebars template (on a blog for example).

## Update a publication

After publishing, StackEdit keeps your file linked to that publication which makes it easy for you to re-publish it. Once you have modified your file and you want to update your publication, click on the **Publish now** button in the navigation bar.

> **Note:** The **Publish now** button is disabled if your file has not been published yet.

## Manage file publication

Since one file can be published to multiple locations, you can list and manage publish locations by clicking **File publication** in the **Publish** sub-menu. This allows you to list and remove publication locations that are linked to your file.


# Markdown extensions

StackEdit extends the standard Markdown syntax by adding extra **Markdown extensions**, providing you with some nice features.

> **ProTip:** You can disable any **Markdown extension** in the **File properties** dialog.


## SmartyPants

SmartyPants converts ASCII punctuation characters into "smart" typographic punctuation HTML entities. For example:

|                |ASCII                          |HTML                         |
|----------------|-------------------------------|-----------------------------|
|Single backticks|`'Isn't this fun?'`            |'Isn't this fun?'            |
|Quotes          |`"Isn't this fun?"`            |"Isn't this fun?"            |
|Dashes          |`-- is en-dash, --- is em-dash`|-- is en-dash, --- is em-dash|


## KaTeX

You can render LaTeX mathematical expressions using [KaTeX](https://khan.github.io/KaTeX/):

The *Gamma function* satisfying $\Gamma(n) = (n-1)!\quad\forall n\in\mathbb N$ is via the Euler integral

$$
\Gamma(z) = \int_0^\infty t^{z-1}e^{-t}dt\,.
$$

> You can find more information about **LaTeX** mathematical expressions [here](http://meta.math.stackexchange.com/questions/5020/mathjax-basic-tutorial-and-quick-reference).


## UML diagrams

You can render UML diagrams using [Mermaid](https://mermaidjs.github.io/). For example, this will produce a sequence diagram:

`   ` `美人鱼序列图表爱丽丝 -  >>鲍勃：你好鲍勃，你好吗？鲍勃 -  >>约翰：约翰，你呢？鲍勃 -  x爱丽丝：我很感谢！Bob-x John ：我很感谢！注意约翰的权利：鲍勃认为很长很长一段时间，因为文本不适合连续。鲍勃 - >爱丽丝：和约翰一起检查......爱丽丝 - >约翰：是的......约翰，你好吗？` ` `这将产生一个流程图：` `美人鱼图LR A [方形矩形]  - 链接文字 - > B（（圆圈））A  - > C（圆形）形）形）形矩形）乙- > d {菱形}℃ - > d ` ` `     





    














