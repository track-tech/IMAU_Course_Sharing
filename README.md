# 内农大课程攻略共享计划|IMAU_Course_Sharing

一次在Github上的闲逛让我发现了浙大的课程攻略计划，试着搜索了一下类似的项目，发现很多学校都有这样的非官方公共项目，也就此诞生了想创建内农大课程攻略的想法。希望这个项目可以帮到你。

--2022-4-20-Tracker--

------

**-贡献者名录-**





------

Tips:

请注意不要上传超过100M的单个文件，Github不支持。

如想保证资源完整性，请上传包含网盘等第三方资源连接的说明文档。

Discussions已开通，欢迎交流灌水~

## 目录 | Index

- [内农大课程攻略共享计划|IMAU_Course_Sharing](#内农大课程攻略共享计划imau_course_sharing)
  - [目录 | Index](#目录--index)
  - [前言 | Preface](#前言--preface)
  - [特性 | Features](#特性--features)
  - [平台 | Platform](#平台--platform)
  - [下载方法 | Download](#下载方法--download)
    - [1. 网页下载](#1-网页下载)
    - [2. clone 全仓库](#2-clone-全仓库)
    - [3. DownGit](#3-downgit)
    - [4. GitZip for github](#4-gitzip-for-github)
  - [贡献 | Contribute](#贡献--contribute)
    - [操作方法|Method](#操作方法method)
    - [提醒|Tips](#提醒tips)
    - [警告|Warning](#警告warning)
  - [许可 | License](#许可--license)
  - [参考项目 | Project](#参考项目--project)

## 前言 | Preface

来到一所大学，从第一次接触许多课，直到一门一门完成，这个过程中我们时常收集起许多资料和情报。

有些是需要在网上搜索的电子书，每次见到一门新课程，Google 一下教材名称，有的可以立即找到，有的却是要花费许多眼力；有些是历年试卷或者 A4 纸，前人精心收集制作，抱着能对他人有用的想法公开，却需要在各个群或者 CC98 中摸索以至于从学长手中代代相传；有些是上完一门课才恍然领悟的技巧，原来这门课重点如此，当初本可以更轻松地完成得更好……

我也曾很努力地收集各种课程资料，但到最后，某些重要信息的得到却往往依然是纯属偶然。这种状态时常令我感到后怕与不安。我也曾在课程结束后终于有了些许方法与总结，但这些想法无处诉说，最终只能把花费时间与精力才换来的经验耗散在了漫漫的遗忘之中。

我为这一年一年，这么多人孤军奋战的重复劳动感到不平。

我希望能够将这些隐晦的、不确定的、口口相传的资料和经验，变为公开的、易于获取的和大家能够共同完善、积累的共享资料。

我希望只要是前人走过的弯路，后人就不必再走。这是我的信念，也是我建立这个项目的原因。

>引用自[浙江大学课程攻略计划](https://github.com/QSCTech/zju-icicles))

## 特性 | Features

本项目至今为止收录了以下内容：




## 平台 | Platform

为什么采用 GitHub 项目作为平台呢？我有以下一些考虑。

- QQ 群大多为年级和专业所分隔，无法长期共同地保有；况且群文件也缺乏组织。
- GitHub 项目可以使用目录进行文件组织，并且每个目录均可以在显示文件列表的同时显示一个 README，十分适合本项目的需求。
- GitHub 带有便捷的 Issue 和 Pull Request 协作功能，并且可以方便地对贡献的质量进行监督和调整。

## 下载方法 | Download

我们尽可能提供各种方便快捷的方法，但鉴于项目的公益性，下载效果可能并不理想，还请见谅。

如果有更方便的方法，欢迎提出Issue。

### 1. 网页下载

在 GitHub 选择相应文件下载即可。

### 2. clone 全仓库

如果有充分的时间和空间，推荐使用 clone 下全项目。以此种方式下载可以保持与仓库同步。

```bash
# clone命令
$ git clone https://github.com/hewei2001/HITSZ-OpenCS
# pull更新
$ git pull
```

鉴于仓库内容有过若干次大的更新（如课程改革），导致 Commit History 较多，直接 clone 仓库可能会下载比实质内容大几倍的 .git 文件，因此可以使用如下命令限制 clone 的深度。（最终实质内容约 1.5 GB）

```bash
# clone命令
$ git clone --depth=1 https://github.com/hewei2001/HITSZ-OpenCS
```

### 3. [DownGit](https://minhaskamal.github.io/DownGit/#/home)

若要下载单个文件夹，复制该文件夹的网址，粘贴入该网页，然后点击 Download 就可以下载目录的压缩文件。

### 4. [GitZip for github](https://chrome.google.com/webstore/detail/gitzip-for-github/ffabmkklhbepgcgfonabamgnfafbdlkn)

安装 Chrome 浏览器的插件，可以选择批量下载。




## 贡献 | Contribute

**欢迎贡献！**

Issue、PR、纠错、资料、选课/考试攻略，完全欢迎！



### 操作方法|Method

提交 PR：Fork 本项目，然后在 GitHub 网页端点击 Upload File 上传文件，发起 PR 即可。留意一下项目的文件组织喔。

或者也可以直接附加在 Issue 中，由维护者进行添加。

对于教师的评价请一律使用姓名拼音首字母缩写；至于教师提供的课件就不用上传了，因为每年说不定会有更新的嘛。

由于本项目体积很大，故可以采用在Github Web端直接上传的方式，具体操作如下：

0. 首先Fork本项目

1. 上传文件到已有文件夹：打开对应文件夹，点击绿色Download按钮旁的upload，上传你的文件。

2. 上传文件到新文件夹：打开任意文件夹，点击绿色Download按钮旁的upload，**把浏览器地址栏中文件夹名称改为你想要新建的文件夹名称，然后回车**，上传你的文件。

### 提醒 | Tips

有些朋友在提交 PR 的时候可能会注意到自己的 Fork 和我们的主分支有数十甚至上百个不同的 commit 。如果出现这种情况，可以考虑以下两种解决方案：

1. 如果对git不太熟悉，建议（在备份完成后）先删除你的项目，重新 fork 、上传并重新提交 PR 。
2. 如果对git及其工作原理较为熟悉（而且愿意花费时间和流量折腾），可以尝试在 fork 出的项目上进行 rebase 以消除与主分支在历史上的冲突。

### 警告 | Warning

下列内容为不适合上传的内容。如果你认为缺少这些资料将会影响资源的完整性，请优先考虑放在校内资源平台，或联系你的教师并由教师发布。建议你撰写一个 README 文档并放置一些链接或指引文字来帮助找到这些资源。

- 盗版电子书/付费电子书
- 盗版/破解版/绿色版付费软件及其安装包
- 课程/教师主页上列出的内容（请在获得教师许可后上传）

如果你认为本仓库的一些文件侵犯了您的权益，请 [向我们发送邮件](mailto:tech@zjuqsc.com) 。我们将会从仓库中彻底清除这些文件。

## 许可 | License

由贡献者编写部分的许可如下：

[CC-BY-NC-SA：署名-非商业性使用-相同方式共享](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.zh)

> 资料仅供参考，请自己判断其适用性。

其他部分的版权归属于其各自的作者。

## 参考项目 | Project

>[QSCTech/zju-icicles: 浙江大学课程攻略共享计划 (github.com)](https://github.com/QSCTech/zju-icicles)
>
>[Salensoft/thu-cst-cracker: 清华大学计算机系课程攻略 (github.com)](https://github.com/Salensoft/thu-cst-cracker)
>
>[hewei2001/HITSZ-OpenCS: 哈尔滨工业大学（深圳）计算机专业课程攻略 | Guidance for courses in Department of Computer Science, Harbin Institute of Technology (Shenzhen) (github.com)](https://github.com/hewei2001/HITSZ-OpenCS)
