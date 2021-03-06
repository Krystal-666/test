# *机器翻译：统计建模与深度学习方法*
*肖桐*  *朱靖波*

*东北大学自然语言处理实验室* / *小牛翻译*

这是一个教程，对机器翻译的统计建模和深度学习方法进行较为全面的介绍。其内容被编纂成书，可以供计算机相关专业高年级本科生及研究生学习之用，也可以作为自然语言处理，特别是机器翻译相关研究人员的参考资料。本书的所有源代码（tex）均已开放。

本书共分为七个章节，章节的顺序参考了机器翻译技术发展的时间脉络，同时兼顾了机器翻译知识体系的内在逻辑。各章节的主要关系如下（如果无法显示图片可以[修改host文件](https://blog.csdn.net/weixin_42128813/article/details/102915578)或fanqiang）：

<div align="center">

<img src="http://39.99.132.142:8082/guideline1.png" width=80% height=80% /> 
<!-- <img src="https://github.com/NiuTrans/MTBook/blob/xiaotong/guideline.png?raw=true" width=80% height=80% /> -->

</div>

## 内容

<a href="https://developer.niutrans.com/mtbook/section1-1.html" title="封面、导读和目录">封面、导读和目录</a>

Part I 机器翻译基础
1. 机器翻译简介
  * <a href="https://developer.niutrans.com/mtbook/section1-1.html" title="机器翻译的概念">1.1 机器翻译的概念</a>
  * <a href="https://developer.niutrans.com/mtbook/section1-2.html" title="机器翻译简史">1.2 机器翻译简史</a>
  * <a href="https://developer.niutrans.com/mtbook/section1-3.html" title="机器翻译现状">1.3 机器翻译现状</a>
  * <a href="https://developer.niutrans.com/mtbook/section1-4.html" title="机器翻译方法">1.4 机器翻译方法</a>
  * <a href="https://developer.niutrans.com/mtbook/section1-5.html" title="翻译质量评价">1.5 翻译质量评价</a>
  * <a href="https://developer.niutrans.com/mtbook/section1-6.html" title="机器翻译应用">1.6 机器翻译应用</a>
  * <a href="https://developer.niutrans.com/mtbook/section1-7.html" title="开源项目与评测">1.7 开源项目与评测</a>
  * <a href="https://developer.niutrans.com/mtbook/section1-8.html" title="推荐学习资源">1.8 推荐学习资源</a>
2. <a href="https://developer.niutrans.com/mtbook/section2.html" title="词法、语法及统计建模基础">词法、语法及统计建模基础</a>
  * <a href="https://developer.niutrans.com/mtbook/section2-1.html" title="问题概述">2.1 问题概述</a>
  * <a href="https://developer.niutrans.com/mtbook/section2-2.html" title="概率论基础">2.2 概率论基础</a>
  * <a href="https://developer.niutrans.com/mtbook/section2-3.html" title="中文分词">2.3 中文分词</a>
  * <a href="https://developer.niutrans.com/mtbook/section2-4.html" title="n-gram 语言模型">2.4 *n*-gram 语言模型</a>
  * <a href="https://developer.niutrans.com/mtbook/section2-5.html" title="句法分析（短语结构分析）">2.5 句法分析（短语结构分析）</a>
  * <a href="https://developer.niutrans.com/mtbook/section2-6.html" title="小结及深入阅读">2.6 小结及深入阅读</a>

Part II 统计机器翻译
3. 基于词的机器翻译模型
  * <a href="https://developer.niutrans.com/mtbook/section1-1.html" title="什么是基于词的翻译模型">3.1 什么是基于词的翻译模型</a>
  * <a href="https://developer.niutrans.com/mtbook/section1-1.html" title="构建一个简单的机器翻译系统">3.2 构建一个简单的机器翻译系统</a>
  * <a href="https://developer.niutrans.com/mtbook/section1-1.html" title="基于词的翻译建模">3.3 基于词的翻译建模</a>
  * <a href="https://developer.niutrans.com/mtbook/section1-1.html" title="IBM 模型 1-2">3.4 IBM 模型 1-2</a>
  * <a href="https://developer.niutrans.com/mtbook/section1-1.html" title="IBM 模型 3-5 及隐马尔可夫模型">3.5 IBM 模型 3-5 及隐马尔可夫模型</a>
  * <a href="https://developer.niutrans.com/mtbook/section1-1.html" title="问题分析">3.6 问题分析</a>
  * <a href="https://developer.niutrans.com/mtbook/section1-1.html" title="小结及深入阅读">3.7 小结及深入阅读</a>
4. 基于短语和句法的机器翻译模型
  * <a href="https://developer.niutrans.com/mtbook/section1-1.html" title="翻译中的结构信息">4.1 翻译中的结构信息</a>
  * <a href="https://developer.niutrans.com/mtbook/section1-1.html" title="基于短语的翻译模型">4.2 基于短语的翻译模型</a>
  * <a href="https://developer.niutrans.com/mtbook/section1-1.html" title="基于层次短语的模型">4.3 基于层次短语的模型</a>
  * <a href="https://developer.niutrans.com/mtbook/section1-1.html" title="基于语言学句法的模型">4.4 基于语言学句法的模型</a>
  * <a href="https://developer.niutrans.com/mtbook/section1-1.html" title="小结及深入阅读">4.5 小结及深入阅读</a>

Part III 神经机器翻译
5.  人工神经网络和神经语言建模
  * <a href="https://developer.niutrans.com/mtbook/section1-1.html" title="深度学习与人工神经网络">5.1 深度学习与人工神经网络</a>
  * <a href="https://developer.niutrans.com/mtbook/section1-1.html" title="神经网络基础">5.2 神经网络基础</a>
  * <a href="https://developer.niutrans.com/mtbook/section1-1.html" title="神经网络的张量实现">5.3 神经网络的张量实现</a>
  * <a href="https://developer.niutrans.com/mtbook/section1-1.html" title="神经网络的参数训练">5.4 神经网络的参数训练</a>
  * <a href="https://developer.niutrans.com/mtbook/section1-1.html" title="神经语言模型">5.5 神经语言模型</a>
  * <a href="https://developer.niutrans.com/mtbook/section1-1.html" title="小结及深入阅读">5.6 小结及深入阅读</a>

6.  神经机器翻译模型
  * <a href="https://developer.niutrans.com/mtbook/section1-1.html" title="神经机器翻译的发展简史">6.1 神经机器翻译的发展简史</a>
  * <a href="https://developer.niutrans.com/mtbook/section1-1.html" title="编码器-解码器框架">6.2 编码器-解码器框架</a>
  * <a href="https://developer.niutrans.com/mtbook/section1-1.html" title="基于循环神经网络的翻译模型及注意力机制">6.3 基于循环神经网络的翻译模型及注意力机制</a>
  * <a href="https://developer.niutrans.com/mtbook/section1-1.html" title="Transformer">6.4 Transformer</a>
  * <a href="https://developer.niutrans.com/mtbook/section1-1.html" title="序列到序列问题及应用">6.5 序列到序列问题及应用</a>
  * <a href="https://developer.niutrans.com/mtbook/section1-1.html" title="小结及深入阅读">6.6 小结及深入阅读</a>

7.  神经机器翻译实战 —— 参加一次比赛
  * <a href="https://developer.niutrans.com/mtbook/section1-1.html" title="神经机器翻译并不简单">7.1 神经机器翻译并不简单</a>
  * <a href="https://developer.niutrans.com/mtbook/section1-1.html" title="数据处理">7.2 数据处理</a>
  * <a href="https://developer.niutrans.com/mtbook/section1-1.html" title="建模与训练">7.3 建模与训练</a>
  * <a href="https://developer.niutrans.com/mtbook/section1-1.html" title="推断">7.4 推断</a>
  * <a href="https://developer.niutrans.com/mtbook/section1-1.html" title="进阶技术">7.5 进阶技术</a>
  * <a href="https://developer.niutrans.com/mtbook/section1-1.html" title="小结及深入阅读">7.6 小结及深入阅读</a>

Part IV 附录
* <a href="https://developer.niutrans.com/mtbook/section1-1.html" title="附录 A">A.  附录 A：基准数据集和评价工具</a>
* <a href="https://developer.niutrans.com/mtbook/section1-1.html" title="附录 B">B.  附录 B：IBM模型3-5训练方法</a>

## 源代码及编译


本书基于tex编写，源代码地址为：[https://github.com/NiuTrans/MTBook](https://github.com/NiuTrans/MTBook)

编译前需要安装[MikTeX](https://miktex.org/)，并在MikTeX Console中下载并更新编译所需宏包。之后，编译src目录下的mt-book-xelatex.tex即可得到pdf文件，编译指令如下：

```shell
xelatex mt-book-xelatex
biber mt-book-xelatex
makeindex mt-book-xelatex
xelatex mt-book-xelatex
```

在编译中可能会遇到内存不足的问题，可以通过以下方式解决：
#### Windows下使用MiKTeX或CTEX
1. 运行cmd打开命令行窗口，输入：`initexmf --edit-config-file=xelatex`

2. 在弹出的文件中输入以下内容：`main_memory=5000000 extra_mem_bot=5000000  font_mem_size=5000000 pool_size=5000000 buf_size=5000000`

3. 在cmd窗口输入： `initexmf --dump=pdflatex` 更新latex格式文件

#### TeXLive & MacTeX（Linux，OS X等）

1. 打开texmf.cnf文件，更改其内容为：`main_memory=5000000 extra_mem_bot=5000000 font_mem_size=5000000 pool_size=5000000 buf_size=5000000`

2. 调用texhash更新latex格式文件

注：编译latex文件会依赖许多宏包。如果有任何编译错误，建议将宏包更新至最新版本。

## 开源协议

本书的开源内容基于The Creative Commons Attribution-NonCommercial 4.0 Unported License（[link](http://creativecommons.org/licenses/by-nc/4.0)）

## 致谢

感谢所有为本书的编辑和排版做出贡献的人

*曹润柘、曾信、孟霞、单韦乔、姜雨帆、王子扬、刘辉、许诺、李北、刘继强、张哲旸、周书含、周涛、张裕浩、李炎洋、林野、刘晓倩、牛蕊*

## 联系我们

有任何问题请联系xiaotong@mail.neu.edu.cn （肖桐） 或 854581319@qq.com（曹润柘）
