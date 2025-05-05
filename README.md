
# nemcmthesis

**东北三省数学建模联赛论文模板**

**JL**, [yhlaozero2@163.com](yhlaozero2@163.com)
**v2.0.0(2025-05-01)**

QQ 交流群：345749407

***

## Overview

现发布非官方版东北三省数学建模联赛论文模板. 本模板参照《2025 年东北三省数学建模联赛通知》《全国大学生数学建模竞赛论文格式规范（2024）》进行设计，适用于东北三省数学建模联赛论文的编写，也供各位读者研究使用.

## 模板许可说明 

本模板的发布遵守[The LaTeX Project Public License(LPPL)](https://www.latex-project.org/lppl/lppl-1-3c/)。未经允许，禁止任何人将本模板用于商业用途。

## 模板介绍

nemcmthesis(LaTeX **Thesis** Template for **N**orth**e**astern-Three-Provinces **M**athematical **C**ontest in **M**odeling)，即东北三省数学建模联赛论文模板，诞生于 2024 年春天. 本模板历经不断地改进优化，致力于让参赛者**省去繁琐的格式调试、专注于论文内容的编写**.

当读者在使用模板的过程中遇到bug或者格式问题，建议按照如下顺序逐步尝试解决问题：

1. 自己动手排查；
2. 查阅文件`gbk_of_nemcmthesis.pdf`；
3. 将模板升级到最新版本；
4. 联系模板作者，提供具体情况说明；
5. 如为语法上的 bug，则将 bug report 提交到[GitHub-Issues](https://github.com/JohnsonLo00/nemcmthesis/issues)或 [Gitee-Issues](https://gitee.com/jhonson-lo/nemcmthesis/issues).


## 模板获取方式

目前可从如下平台获取本模板：

-   [GitHub](https://github.com/JohnsonLo00/nemcmthesis) (当前版本：v2.0.0[最新])

-   [Gitee](https://gitee.com/jhonson-lo/nemcmthesis) (当前版本：v2.0.0[最新])

-   [Overleaf](https://www.overleaf.com/latex/templates/nemcmthesis-thesis-latex-template-for-northeastern-three-provinces-mathematical-contest-in-modeling/sgjxtcwrgthf) (当前版本：v1.0)

其中，GitHub 与 Gitee 上可在 **Release** 板块获取各版本模板的下载路径；Overleaf 上可通过在模板库中搜索“nemcmthesis”(作者为 JohnsonLo) 来获取模板.


## 文件组成

模板压缩包内部的文件组成如下：

```
codes/ 用于放置源代码文件. 需写入论文中的代码可以通过文件导入的命令来实现写入
figures/ 用于放置图片文件. 需插入论文中的图片可以通过文件导入的命令来实现插入
- signature/ 用于放置封面页的队员签名截图
- fig_chx/ 用于放置第x章内的图片文件
mainbody/ 用于放置正文各章节的子tex文件. 论文的每个章节均可分为不同的tex文件进行编写，最后再汇总导入一个tex文件中(即文件main.tex)
- aabstract.tex：摘要
- chx.tex：第x章
- appendices.tex：附录

guidebook_of_nemcmthesis.pdf：本模板的使用指北
nemcmthesis.cls：本模板的文档类文件
latexmkrc: latexmk配置文件
LICENSE：The LaTeX Project Public License（LPPL）
main.tex：中枢tex文件. 聚集各章节的tex文件为一体
main.pdf：由main.tex编译生成的PDF文档
refs.bib：参考文献数据库文件. 参考文献列表可以通过bib文件导入的命令来生成
```


## 更新日志

- **v2.0.0, 2025-05-01**
  - **Added**:
    - 引入了基于 latexmk 的自动化编译方法
  - **Changed**:
    - 删除了 changes 宏包的预设，保留读者使用的自由程度
    - 删除了部分命令的自定义、重定义，保留读者使用的自由程度
    - 删除了对列表环境样式的设置，保留读者使用的自由程度
    - 取消了公式、定理、图表的编号的层级
- **v1.0, 2024-06-21**
  - **Added**:
    - 首次发布本模板
