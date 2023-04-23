Markdown 有什么用？
Markdown 是做笔记、为网站创建内容以及生成可打印文档的快速、简便的方法。

学习 Markdown 语法并不需要很长时间，一旦你知道如何使用它，你就可以在几乎所有地方使用 Markdown 进行书写了。大多数人使用 Markdown 来为网站创建内容，但是 Markdown 也可以很好地格式化从电子邮件到购物清单的所有内容。

下面是一些你可以使用 Markdown 的场景。

#网站
Markdown 是为 web 而设计的，因此，市面上有很多专门用于创建网站内容的应用程序就不足为奇了。

如果您熟悉 HTML、CSS和版本管理工具，请试试 [Jekyll]，这是一个广受欢迎的静态网站生成器，它能将 Markdown 文件并构建为 HTML 网站。这种方法的优势之一是 [GitHub Pages] 为 Jekyll 生成的网站提供免费托管服务。如果 Jekyll 不是你的理想之选。

如果你是 WordPress 博主，你可以使用 Jetpack 插件实现对 Markdown 的支持。

#文件资料
Markdown 并不具备像 Microsoft Word 这样的文字处理程序的所有功能，但是对于创建基本文件（例如作业和信件）来说已经足够了。你可以使用 Markdown 文档创作工具来创建 Markdown 格式的文档并将其导出为 PDF 或 HTML 格式。PDF 格式是关键，因为一旦有了 PDF 文档，您就可以使用它进行任何操作：打印、通过电子邮件发送或将其上传到网站。

这是我推荐的一些Markdown文档创作工具：

现代编辑器
VSCode / Atom

传统编辑器
Vim / Emacs / Sublime Text / Notepad++

IDE 自带编辑器
IntelliJ IDEA / Android Studio / WebStorm

专用编辑器
Ulysses / Mou / Typora / Markpad

在线编辑器
各种支持 Markdown 的网站都提供了在线 Markdown 编辑器

#笔记
在几乎所有方面，Markdown 都是记笔记的理想语法。不幸的是，两个最受欢迎的笔记应用程序 Evernote 和 OneNote 目前都不支持 Markdown。好消息是，其他一些笔记应用程序 是 支持 Markdown 的：

[Simplenote] 是适用于所有平台的免费、简单的笔记应用程序。
[Notable] 是可以在各种平台上运行的笔记应用程序。
[Bear] 是适用于 Mac 和 iOS 设备的类似 Evernote 的应用程序。默认情况下，它并不专门针对 Markdown 的，但是你可以启用 Markdown 兼容模式。
[Boostnote] 自称是“专为程序员设计的开源笔记应用程序”。
如果你无法放弃 Evernote，可以试试 Marxico，一个专门针对 Evernote 的基于订阅付费的 Markdown编辑器，或在 Evernote 网站上使用 [Markdown Here] 插件。

#书籍
想要自行出版小说？请试试 Leanpub，该服务可将你的 Markdown 格式的文件转换为电子书。Leanpub 以 PDF、EPUB 和 MOBI 文件格式输出你的图书。如果你要创建纸版书籍，可以将 PDF 文件上传到类似 Kindle Direct Publishing 之类的服务提供商处。要了解有关使用 Markdown 编写和自行出版书籍的更多信息，请阅读 此博文。

#演示文稿
信不信由你，你可以将 Markdown 格式的文件转换成演示文稿。在 Markdown 中创建演示文稿需要一点时间来适应，但是一旦你掌握了它，你就能体会到比使用 PowerPoint 或 Keynote 之类的应用程序更快、更容易。Remark（GitHub 仓库）和 Cleaver（GitHub 仓库）一样，是一种基于浏览器的、流行的 Markdown 幻灯片工具。如果你使用的是 Mac，并且希望安装一个应用程序来使用的话，请试试 Deckset 或 Marked。

#邮件
如果你需要发送大量电子邮件，并且对大多数电子邮件提供商网站上可用的格式设置控件感到厌倦，那么你将很高兴地发现有一种使用 Markdown 编写电子邮件的简便方法：[Markdown Here] 是一个免费、开源的浏览器扩展程序，可将 Markdown 格式的文本转换为可用于发送的 HTML。

#文档
Markdown 非常适合技术文档。像 GitHub 这样的公司越来越多地转向使用 Markdown 来创建其文档了，请查看此 博文 以了解如何将 Markdown 格式的文档迁移到 [Jekyll]。如果你是为产品或服务编写文档，请试试以下的便捷工具：

Read the Docs 可以将你所开源的 Markdown 文件生成文档网站。只需将你的 GitHub 仓库连接到他们的服务，然后你就可以将内容推送到该仓库中，Read the Docs 会完成其余的工作。他们还为 商业实体提供服务。
[MkDocs] 是一个快速、简单的静态站点生成器，专门用于构建项目文档。文档源文件使用 Markdown 编写，并使用一个 YAML 配置文件进行配置。MkDocs 有多个 内置主题，包括移植自 Read the Docs 的文档主题。最新的一个主题是 MkDocs Material。
[Docusaurus] 是一个静态网站生成器，专门用于创建文档网站。它支持翻译、搜索和版本控制。
VuePress 是基于 Vue 构建的静态站点生成器，并针对编写技术文档进行了优化。
[Jekyll] 前面已经提到过它了，但它也是将 Markdown 文件生成文档网站的一个不错的选择。如果你选择 Jekyll，请务必试试 Jekyll 文档主题。
#Markdown 方言
使用 Markdown 的过程中，最令人困惑的地方是：实际上每个 Markdown 应用程序都实现了稍有不同的 Markdown 语法。Markdown 的这些变体通常被称为 flavors（方言）。掌握你的应用程序所实现的 Markdown 语法是你需要主义的。

为了让你了解各 Markdown 变体的概念，将它们比作语言的方言（language dialects）可能会有所帮助。华雷斯城（Ciudad Juárez）的人说西班牙语，就像巴塞罗那（Barcelona）人一样，但是两个城市使用的方言之间有很大的不同。使用不同 Markdown 应用程序的人也是如此。Dillinger 支持的 Markdown 格式与 Ulysses 有着很大的不同。

实际上，这意味着当一个应用程序说它支持 “Markdown” 时，你永远也不会确切地知到它的实际意思。它说的是仅支持 基本语法？还是所有基本语法加 扩展语法 ？或者是某些语法的组合呢？在你阅读其文档或开始使用该应用程序之前，你永远都不会知到。

如果你只是新手，我能给你的最好建议就是选择一个具有良好 Markdown 支持的应用程序。这对保持 Markdown 文件的可移植性大有帮助。你可能需要在其它应用程序中保存或使用你的 Markdown 文件，要实现这一点，你应当从使用一个具有良好 Markdown 支持的应用程序开始。你可以在 Markdown 工具列表 中找到合适的应用程序。

#其它资源
网上有很多资源用来学习 Markdown。以下列出一些：

John Gruber’s Markdown documentation. Markdown 的创建者编写的原始指南。
Markdown Tutorial. 一个开源网站，你能用浏览器在这个网站上尝试 Markdown。
Awesome Markdown. Markdown 工具和学习资源列表。
Typesetting Markdown. 这是一个系列教程，介绍了使用 pandoc 和 ConTeXt 对 Markdown 文档进行排版的系统。
