# Modern CMake for C++  
*Second Edition*  

*轻松构建前沿C++代码，提供高质量的解决方案*<a href=""><img src="cover.png" height="256px" align="right"></a>

* 作者：Rafał Świdziński  
* 译者：陈晓伟
* Packt Publishing Ltd. (出版于: 2024年5月8日)

> [!IMPORTANT]
> 翻译是译者用自己的思想，换一种语言，对原作者想法的重新阐释。鉴于我的学识所限，误解和错译在所难免。如果你能买到本书的原版，且有能力阅读英文，请直接去读原文。因为与之相较，我的译文可能根本不值得一读。
>
> <p align="right"> — 云风，程序员修炼之道第2版译者</p>

## 本书概述

创建顶级软件并非易事。在线研究这个主题的开发者难以确定哪些建议是当前的，哪些方法已经更新，或已经有更好的实践方式。此外，大多数资源以混乱的方式解释过程，缺乏适当的背景、上下文和结构。

《Modern CMake for C++》提供了一个端到端的指南，通过全面处理C++解决方案的构建，提供了更简单的体验。它不仅教你如何在项目中使用CMake，还强调了如何使项目保持可维护性、优雅和简洁。该指南会引导你自动化完成许多项目中的常见任务，包括构建、测试和打包。

本书还会指导如何组织源目录、构建目标和创建包。随着了解的深入，将学习编译和链接可执行文件和库，详细理解这些过程，并优化每个步骤以获得最佳结果。此外，将发现如何将外部依赖项（如第三方库、测试框架、程序分析工具和文档生成器），进而整合到自己的项目中。最后，将学习如何导出、安装和打包解决方案，以供内部和外部使用。

完成这本书后，你将能以专业水平使用CMake。



## 作者简介

**Rafał Świdziński**是谷歌的一名资深工程师，拥有超过12年的全栈开发经验。他领导过思科Meraki、亚马逊和爱立信等行业巨头的项目，体现了对创新的承诺。作为一名自愿选择居住在伦敦的人，他始终站在技术进步的前沿，参与了许多个人创业项目。最近他转向医疗保健领域的AI。Rafał重视顶尖的代码质量和工艺，也会通过YouTube频道和出版的书籍分享见解。

致Zoe --- 无汝，无书（如果没有你，我无法写出这本书）



## 本书相关

* github翻译地址：https://github.com/xiaoweiChen/Modern-CMake-for-Cpp-2ed

* 第一版译文地址：https://github.com/xiaoweiChen/Modern-CMake-for-Cpp

* 译文的LaTeX 环境配置：https://www.cnblogs.com/1625--H/p/11524968.html

  * 禁用拼写检查：https://blog.csdn.net/weixin_39278265/article/details/87931348

  * 使用xelatex编译时需要添加`-shell-escape`和`-8bit`选项，例如：

    `xelatex -synctex=1 -interaction=nonstopmode -shell-escape -8bit "Modern-CMake-for-C++-2ed".tex`

  * 为了内容中表格和目录索引能正常生成，至少需要连续编译两次

  * Latex中的中文字体([思源黑体](https://github.com/adobe-fonts/source-han-sans))和英文字体([Hack](https://github.com/source-foundry/Hack-windows-installer/releases/tag/v1.6.0))，需要安装后自行配置。如何配置请参考主book/css.tex顶部关于字体的信息。

* vscode中配置LaTeX：https://blog.csdn.net/Ruins_LEE/article/details/123555016

