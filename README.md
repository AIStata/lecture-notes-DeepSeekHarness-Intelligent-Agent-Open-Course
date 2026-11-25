# [学习笔记--11月18日--DeepSeekHarness智能体公开课 - 计量经济网](https://www.aistata.cn/blog/230006.html)

公开课简介：本课程详细介绍了DeepSeek Harness智能体的核心概念、安装配置、插件加载及与Stata等科研工具的集成应用。

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/598Tr639EmMM8dQo41JTtYOu4uodFytfe6OmfabM5PBfYyIPF6z2n4uBTvB2YXgg1yo65zcoMocCvHyLMzicfibyDDFAYJeTyPD0lqTz4VbgQ/640?wx_fmt=png&from=appmsg&watermark=1&tp=webp&wxfrom=5&wx_lazy=1#imgIndex=0)

### 一、核心知识精讲

本节课的核心在于介绍DeepSeek Harness智能体的基本概念、安装配置以及如何通过插件扩展其功能，主要分为以下几个模块：

#### 1. DeepSeek Harness简介与核心能力

- 一切皆插件的理念：DeepSeek Harness提倡一切皆插件，所有模型接入、工具、技能、绘画管理、存储调度甚至界面都由插件拼接而成，用户可根据需求自行安装所需插件。
- 模型与框架的关系：模型负责思考，而Harness框架负责执行。同一个模型搭配不同的Harness，其能力边界完全不同，这解释了为何同样模型在网页版只能聊天而在本地客户端能改写代码和运行脚本。
- 多种运行模式与入口：DeepSeek Harness提供了标准、PTC、极简和创作者四种运行模式，可根据不同任务自由切换。同时提供桌面版、网页版及Python接口等多种形态入口，适用于不同学科背景的用户。

#### 2. 模型配置与成本控制

- 模型提供方选择：初次使用建议选择DeepSeek官方，系统会赠送余额供体验，但该余额有效期仅7天（具体以实际为准）。
- Token与积分的区别：不同大厂的Token或积分消耗模式不同，且积分存在有效期限制。用户需根据自身使用频率和需求选择合适的套餐。

#### 3. 插件安装与使用

- 插件的核心作用：DeepSeek Harness本身功能简洁，其强大能力依赖于插件的扩展。通过安装插件/MCP，可以实现与Stata等专业软件的交互，以及跑回归、因果推断等复杂任务。
- 插件的安装方法：用户可以通过输入插件包名称、从GitHub仓库地址加载或从本地目录导入三种方式安装插件。安装后需在设置中启用插件才能正常使用。
- 自研插件的功能演示：课程演示了自研的State-Kernel-Jupyter和现代DID等插件，这些插件能够实现Stata代码的一键执行、DID估计量的自动判定等功能。

### 二、重难点突破

本节课的重难点在于理解DeepSeekHarness的插件化架构，以及如何通过插件组合来满足科研需求：

科研工具集成的实现

- Stata集成的两种路径：在DeepSeek Harness中跑Stata有两种方法，一是接入MCP（模型上下文协议），二是安装专门的Stata插件。自研的插件通过封装MCP和扩展功能，实现了无需复杂配置即可运行Stata代码的能力。
- 插件的灵活切换：不同插件适用于不同的工作场景，例如有的插件专门用于DID估计量判定，有的用于Stata代码执行。用户需根据具体任务选择合适的插件，并掌握插件的启用和切换操作。



## 🌈❤️最新Stata课程--2017-2026年，数量经济学Stata课程已开设10年，10年Stata经典课程报名中！

![](https://stata101.oss-cn-chengdu.aliyuncs.com/fig-metrics/Stata%E8%AF%BE%E7%A8%8B%E5%AE%A3%E4%BC%A0%E5%9B%BE%E7%89%87.png)
