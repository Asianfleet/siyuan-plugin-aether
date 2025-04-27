<!-- markdownlint-disable MD033 -->
<!-- markdownlint-disable MD041 -->
<!-- markdownlint-disable MD036 -->

<p align="center">
    <img src="asset/aether.png" alt="catenaconf logo" width=100%/>
</p>

[English README](README_en_US.md) | [更新记录](CHANGELOG.md) | QQ 交流群：1044315407（密码：Aether）

# Aether （以太）

Aether —— Where Dialogue Meets Depth.

## 简介

Aether 是一个为思源笔记软件设计的插件。该插件在侧边栏添加了一个按钮，点击后可以弹出一个侧边视图，能够与大型语言模型进行对话（后续将会继续增加与思源深度结合的功能）。
⚠️ **注意：** 由于个人时间关系，当前仅是**极为早期**的版本。
⚠️ **注意：** 在版本稳定下来之前会清空个人配置以及对话记录，请及时将对话信息保存到其他地方。

## 最近更新实现的功能

- 样式优化
- 图片以及文档输入
- 会话中消息内容的修改与重新生成

## 开始

<p align="center">
    <img src="asset/start.png" alt="catenaconf logo" width=90%/>
    <p align="center">点击这个按钮即可打开对话界面</p>
</p>

## 功能介绍

### 界面

- **模型选择与配置**
    1. 点击右下角的模型选择按钮
        <p align="center">
            <img src="asset/model_select.png" alt="catenaconf logo" width=70%/>
            <p align="center">点击这个按钮即可打开对话界面</p>
        </p>
    2. 在此处可以选择对应的模型服务提供方并填入对应的 API Key ，随后点击保存按钮，即可保存 API Key 到内部配置中，并且之后的对话将会使用面板中选择的模型。若要切换模型，则需再打开面板，选中另外的模型并点击保存按钮。（目前仅支持阿里云、DeepSeek、OpenAI、Siliconflow 以及 Agicto 提供方，后续会支持更多的服务提供方以及自定义提供方）
        <p align="center">
            <img src="asset/save.png" alt="catenaconf logo" width=50%/>
            <p align="center">注意，只有点击保存按钮才会将更改保存到本地</p>
        </p>
    3. 自定义模型配置
        <p align="center">
            <img src="asset/custom_config.png" alt="catenaconf logo" width=50%/>
            <p align="center">自定义模型配置界面</p>
            <p align="center">注意，更新插件之后如果思源没有自己刷新，请手动刷新一次</p>
        </p>
    4. 动图演示
        <p align="center">
            <img src="asset/model_select.gif" alt="catenaconf logo" width=50%/>
            <p align="center">模型选择与配置</p>
        </p>

- **对话界面**
    <p align="center">
        <img src="asset/main_interface.png" alt="catenaconf logo" width=50%/>
        <p align="center">功能如图所示</p>
    </p>
- **对话历史界面**
    <p align="center">
        <img src="asset/history.png" alt="catenaconf logo" width=50%/>
        <p align="center">功能如图所示</p>
    </p>

### 对话

<p align="center">
    <img src="asset/chat.png" alt="catenaconf logo" width=60%/>
</p>
<p align="center">基本界面</p>

<p align="center">
    <img src="asset/reason.png" alt="catenaconf logo" width=60%/>
</p>
<p align="center">消息状态显示</p>

<p align="center">
    <img src="asset/toolbar.gif" alt="catenaconf logo" width=60%/>
</p>
<p align="center">消息工具栏</p>

<p align="center">
    <img src="asset/refdelete.gif" alt="catenaconf logo" width=60%/>
</p>
<p align="center">引用和删除</p>

<p align="center">
    <img src="asset/edit_send.gif" alt="catenaconf logo" width=60%/>
</p>
<p align="center">编辑消息、编辑并重新发送</p>

<p align="center">
    <img src="asset/copy.gif" alt="catenaconf logo" width=60%/>
</p>
<p align="center">复制消息</p>

_注：Token 以及 API Cost 的计算结果仅供粗略估计，并不完全准确。后续会更新自动余额查询功能_
