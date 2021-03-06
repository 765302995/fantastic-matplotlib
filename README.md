# Fantastic-Matplotlib

![](https://matplotlib.org/_static/logo2_compressed.svg)

本项目《Fantastic-Matplotlib》是Datawhale🐳数据可视化小组的一个开源项目。

Matplotlib可以说是python数据可视化最重要且常见的工具之一，每一位和数据打交道的人几乎都不可避免要用到，此外也有大量的可视化工具是基于matplotlib做的二次开发。

设计这样一套开源教程的初衷在于笔者最初在用python做数据可视化时面临两大痛点，

- 没有系统梳理matplotlib的绘图接口，常常是现用现查，用过即忘，效率极低
- 没有深入理解matplotlib的设计框架，往往是只会复制粘贴，不知其所以然，面对复杂图表时一筹莫展

基于此，为了彻底解决这些痛点，笔者下定决心通读[官方文档](https://matplotlib.org/)，相比于市面上的很多学习材料，官方文档的内容极为详细而全面，更重要的是，其阐明了matplotlib包的设计架构，这些对于我们掌握并应用是非常有帮助的。在通读完官方文档并结合一定的归纳总结与实践之后，笔者能明显察觉到对于matplotlib的理解上了一个层次。

如果屏幕前的你们，也正在面临以上说的这两个痛点，那么学习本项目教程将会是一个不错的选择。

本项目重点希望在两个层面帮助读者构建matplotlib的知识体系，

- 从图形，布局，文本，样式等多维度系统梳理matplotlib的绘图方法，构建对于绘图方法的整体理解
- 从绘图API层级，接口等方面阐明matplotlib的设计理念，摆脱只会复制粘贴的尴尬处境

最后还要说的是，对于学习完本教程的读者，若是仍然觉得学有余力不过瘾，强烈建议按需阅读官方文档，相信你一定会有所收获的。

关于本项目的名称，fantastic-matplotlib，在笔者精读过官网文档之后，才愈发觉得精妙，仿佛看到了一角下的广袤冰山，被它强大的功能和精巧的设计惊艳到了，之前对于matplotlib的了解还是过于浅薄，因此想用fantastic来表示笔者的感慨，也希望能够通过这样一个开源教程带领读者领略的matplotlib的精彩之处。

## 使用说明

- 使用前请将matplotlib升级到最新版本V3.3.3(2020年12月)，否则可能会出现报错！
- 若是在github中加载ipynb文件失败，可以选择 1）下载后在本地阅读 2）使用nbviewer渲染后阅读，可直接戳下方目录



## 目录

* [第一回：Matplotlib初相识](https://nbviewer.jupyter.org/github/datawhalechina/fantastic-matplotlib/blob/main/%E7%AC%AC%E4%B8%80%E5%9B%9E%EF%BC%9AMatplotlib%E5%88%9D%E7%9B%B8%E8%AF%86.ipynb)

    ​	和matplotlib的初次邂逅，赶紧拿出画布，画笔，一段奇幻的旅途即将开启

* [第二回：艺术画笔见乾坤](https://nbviewer.jupyter.org/github/datawhalechina/fantastic-matplotlib/blob/main/%E7%AC%AC%E4%BA%8C%E5%9B%9E%EF%BC%9A%E8%89%BA%E6%9C%AF%E7%94%BB%E7%AC%94%E8%A7%81%E4%B9%BE%E5%9D%A4.ipynb)

    ​	挥舞起手中的艺术画笔，发挥想象力，在画布上自由地绘制图形

* [第三回：布局格式定方圆](https://nbviewer.jupyter.org/github/datawhalechina/fantastic-matplotlib/blob/main/%E7%AC%AC%E4%B8%89%E5%9B%9E%EF%BC%9A%E5%B8%83%E5%B1%80%E6%A0%BC%E5%BC%8F%E5%AE%9A%E6%96%B9%E5%9C%86.ipynb)

    ​	没有规矩不成方圆，你应当开始学会如何合理地在画布上布局了

* [第四回：文字图例尽眉目](https://nbviewer.jupyter.org/github/datawhalechina/fantastic-matplotlib/blob/main/%E7%AC%AC%E5%9B%9B%E5%9B%9E%EF%BC%9A%E6%96%87%E5%AD%97%E5%9B%BE%E4%BE%8B%E5%B0%BD%E7%9C%89%E7%9B%AE.ipynb)

    ​	为了让你的画流传更久远，快来学习下如何在画布上题字吧

* [第五回：样式色彩秀芳华](https://nbviewer.jupyter.org/github/datawhalechina/fantastic-matplotlib/blob/main/%E7%AC%AC%E4%BA%94%E5%9B%9E%EF%BC%9A%E6%A0%B7%E5%BC%8F%E8%89%B2%E5%BD%A9%E7%A7%80%E8%8A%B3%E5%8D%8E.ipynb)

    ​	下一步你需要学习下怎么样绘制出更加花样繁复，色彩绚丽的画了

* [第六回：场景案例显神通](https://nbviewer.jupyter.org/github/datawhalechina/fantastic-matplotlib/blob/main/%E7%AC%AC%E5%85%AD%E5%9B%9E%EF%BC%9A%E5%9C%BA%E6%99%AF%E6%A1%88%E4%BE%8B%E6%98%BE%E7%A5%9E%E9%80%9A.ipynb)

    ​	最后你应当要了解不同场景下的绘图技巧，正好像山水/人物/花鸟画都有各自的独特技巧一样

## 致谢

感谢以下Datawhale成员对项目推进作出的贡献(排名不分先后)：

**贡献者名单**

| 成员   | 个人简介                              | 个人主页                                           |
| ------ | ------------------------------------------- | -------------------------------------------------- |
| 杨剑砺 | Datawhale成员，项目负责人，数据分析师       | 公众号：口羊的数据分析实验室                       |
| 杨煜   | Datawhale成员，数据分析师                   | 公众号：BI数据可视化                               |
| 耿远昊 | Datawhale成员，华东师范大学在读             | Github：https://github.com/GYHHAHA                 |
| 李运佳 | Datawhale成员，上海交通大学在读             | 知乎：https://www.zhihu.com/people/li-yun-jia-68-9 |
| 居凤霞 | Datawhale成员，数据分析师，南瓜书项目贡献者 |                                                    |

**项目贡献情况**

> 《Fantastic-Matplotlib》V1.0 : 项目第一版上线

项目构建与整合：杨剑砺

第一章：杨剑砺

第二章：杨煜，居凤霞

第三章：耿远昊

第四章：李运佳

第五章：杨剑砺

第六章：杨剑砺，杨煜，居凤霞，耿远昊，李运佳

## 关注我们

> "Datawhale是一个专注AI领域的开源组织，以“for the learner，和学习者一起成长”为愿景，构建对学习者最有价值的开源学习社区。关注我们，一起学习成长。"

[![img](https://raw.githubusercontent.com/datawhalechina/dive-into-cv-pytorch/master/markdown_imgs/datawhale_qrcode.jpeg)](https://raw.githubusercontent.com/datawhalechina/dive-into-cv-pytorch/master/markdown_imgs/datawhale_qrcode.jpeg)



