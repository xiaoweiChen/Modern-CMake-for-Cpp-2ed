# Modern CMake for C++  
*Second Edition*  

Effortlessly build cutting-edge C++ code and deliver high-quality
solutions  <a href=""><img src="cover.png" height="256px" align="right"></a>

* 作者：Rafał Świdziński  
* 译者：陈晓伟
* Packt Publishing Ltd. (出版于: 2024年5月8日)

> [!IMPORTANT]
> 翻译是译者用自己的思想，换一种语言，对原作者想法的重新阐释。鉴于我的学识所限，误解和错译在所难免。如果你能买到本书的原版，且有能力阅读英文，请直接去读原文。因为与之相较，我的译文可能根本不值得一读。
>
> <p align="right"> — 云风，程序员修炼之道第2版译者</p>

## 本书概述

Creating top-notch software is no easy task. Developers researching this subject online often struggle to determine which advice is current and which methods have been superseded by newer, better practices. Moreover, most resources explain the process chaotically, lacking proper background, context, and structure.

Modern CMake for C++ provides an end-to-end guide that offers a simpler experience by treating the building of C++ solutions comprehensively. It not only teaches you how to use CMake in your projects but also highlights what makes them maintainable, elegant, and clean. The guide walks you through automating complex tasks common in many projects, including building, testing, and packaging.

The book instructs you on organizing source directories, building targets, and creating packages. As you progress, you will learn to compile and link executables and libraries, understand these processes in detail, and optimize each step for the best results. Additionally, you will discover how to incorporate external dependencies into your project, such as third-party libraries, testing frameworks, program analysis tools, and documentation generators. Finally, you’ll learn how to export, install, and package your solution for both internal and external use.

After completing this book, you’ll be able to use CMake confidently on a professional level.



## 作者简介

Rafał Świdziński, a seasoned staff engineer at Google, boasts over 12 years of full-stack development expertise. With a track record of spearheading projects for industry giants like Cisco Meraki, Amazon, and Ericsson, he embodies a commitment to innovation. As a Londoner by choice, he remains at the forefront of technological progress, engaging in a myriad of personal ventures. His recent pivot toward AI in healthcare reflects his dedication to impactful advancements. Rafał values top-notch code quality and craftsmanship, sharing insights through his YouTube channel and published books.

To Zoe – I couldn’t have written this book without you.



## 本书相关

* github翻译地址：https://github.com/xiaoweiChen/Modern-CMake-for-Cpp-2ed

* 第一版译文地址：https://github.com/xiaoweiChen/Modern-CMake-for-Cpp

* 译文的LaTeX 环境配置：https://www.cnblogs.com/1625--H/p/11524968.html

  * 禁用拼写检查：https://blog.csdn.net/weixin_39278265/article/details/87931348

  * 使用xelatex编译时需要添加`-shell-escape`和`-8bit`选项，例如：

    `xelatex -synctex=1 -interaction=nonstopmode -shell-escape -8bit "C++-Standard-Library".tex`

  * 为了内容中表格和目录索引能正常生成，至少需要连续编译两次

  * Latex中的中文字体([思源黑体](https://github.com/adobe-fonts/source-han-sans))和英文字体([Hack](https://github.com/source-foundry/Hack-windows-installer/releases/tag/v1.6.0))，需要安装后自行配置。如何配置请参考主.tex顶部关于字体的信息。

* vscode中配置LaTeX：https://blog.csdn.net/Ruins_LEE/article/details/123555016

