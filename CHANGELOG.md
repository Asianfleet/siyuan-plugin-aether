# Changelog

## v0.0.1-alpha

* 实现最基本的大模型对话功能
  Implement the most basic large-model dialogue function

## v0.0.1-beta

* 添加自定义模型功能
  Add custom model feature
  
## v0.02-alpha

* 实现消息（包括用户和AI生成）内容的复制、引用、修改以及重新生成功能
  Implement the copy, reference, modification and regeneration functions of message (including user and ai generation) content

## v0.02-beta

* 实现图片输入功能
  Implement image input

## v0.02-beta.1

* 实现文件粘贴与预览功能
  Implement file paste and preview function

* 新增附件输入按钮
  Add attachment input button
  
## v0.02-beta.2

* 改进更新日志样式
  Improve the update log style

* 优化消息界面布局
  Optimize message interface layout

## v0.02-beta.3

* 增加暗色模式样式
  Add dark mode style

## v0.02-beta.4

* 完善暗色模式样式
  Improve dark mode style

## v0.0.3-alpha

* 实现思源文件添加到上下文功能
  Implement the function of adding siyuan files to the context
  
## v0.0.3-beta

* 改善了上下文面板的实现逻辑
  Improve the implementation logic of the context panel
  
## v0.0.3-beta.1

* Alibaba 提供方中增加对 Qwen3、QwQ 模型的支持
  Add support for Qwen3 and QwQ models in Alibaba provider

## v0.0.3-beta.2

* 新增提示词配置功能
  Add prompt configuration function
* 新增对话历史功能
  Add conversation history function
* 修复了会话高度问题
  Fix session height issue
* 改善了界面风格
  Improve interface style

## v0.0.3-beta.3

* 增加会话界面自动滚动功能，可被用户打断
  Add automatic scrolling function to the conversation interface, which can be interrupted by the user
* 改正了错误文案
  Correct the error text
* 改善了会话界面风格
  Improve conversation interface style

## v0.0.3-beta.4

* 修复了自定义模型配置无法使用的问题
  Fix the problem that the custom model configuration cannot be used

## v0.0.3-beta.5

* 修复了关闭笔记本导致找不到id对应内容的错误
  Fix the error of not finding the content corresponding to the ID due to closing the notebook

## v0.0.3-beta.6

* 新增独立窗口功能，在右侧边栏右击 Aether 图标可选择将该窗口与思源主窗口分离
  Add independent window function, right-click the Aether icon in the right sidebar to choose to separate this window from the Siyuan main window

* 新增公式渲染
  Add formula rendering

* 改进Markdown表格渲染样式
  Improve Markdown table rendering style

## v0.0.3-beta.7

* 新增划词栏按钮（右侧），可将选中内容添加到对话框
  Add a button (on the right) to the selection bar, which can add the selected content to the dialog box

* 增加菜单按钮，可随时查看更新记录
  Add a menu button to view the update log at any time

* 改进作为独立窗口的窗口样式
  Improve the window style as an independent window

## v0.0.3-beta.8

* 添加块菜单按钮，可将选中块内容添加至输入框
  Add a block menu button, which can add the selected block content to the input box

* 改进界面样式
  Improve interface style

## v0.0.3-beta.9

* 改进了 OpenAI Compatible 模型的添加逻辑。（之前的版本中，最后添加模型名称时，需要点击左侧加号才能保存，否则无反应）
  Improve the logic of adding OpenAI Compatible models. (In previous versions, when adding the model name at the end, you need to click the left plus sign to save, otherwise there will be no response.)

## v0.0.3-beta.10

* 提示词图标支持非svg，添加了默认图标
  Prompt icon supports non-svg, added default icon

## v0.0.3-beta.11

* 改进了消息状态卡片的展开与缩小样式；改进了消息状态卡片以及代码块的颜色样式
  Improve the style of expanding and shrinking message status cards; improve the color style of message status cards and code blocks

## v0.0.3-beta.12

* 修复了插件会影响思源笔记本中代码块颜色样式的问题
  Fixed the problem that the plugin affected the color style of code blocks in the notebook

## v0.0.3-beta.13

* 进一步修复了插件会影响思源笔记本中代码块颜色样式的问题
  Further fixed the problem that the plugin affected the color style of code blocks in the notebook

## v0.1.0-alpha

* 新增插件设置页面（右上新增对应角图标），目前支持模型配置、显示设置与对话设置"
  Add plugin settings page (new corresponding corner icon in the upper right corner), currently supports model configuration, display settings and conversation settings
* 模型保存逻辑重构（最新使用方法见说明文档）
  Model save logic reconstruction (latest usage method see documentation)
* 改进界面样式
  Improve interface style

## v0.1.0-alpha.1

* 修复了插件导致思源笔记表格样式不受控制的问题
  Fixed the problem that the plugin caused the table style of Siyuan notes to be uncontrollable
* 改进界面样式
  Improve interface style

## v0.1.0-alpha.2

* 改进界面样式
  Improve interface style

## v0.1.0-alpha.3

* 修复了屏幕截图的多显示器支持问题
  Fixed the multi-monitor support issue for screen capture
* 改进了界面样式
  Improve interface style
* 删除了不常用的内置模型配置
  Deleted the rarely used built-in model configuration

## v0.2.0-alpha

* 在思源顶部菜单栏右上角新增功能按键
  * 新增快速对话功能，可在顶部唤出相应窗口（不会保存记录到本地）
  * 新增行内对话功能， 可将对话回复直接输出在思源文件内
* 修复了模型切换时 URL 更新不及时的问题
* 优化了插件样式
* 删除了不常用的内置模型配置
* 暂时取消公式渲染功能（下个版本将重新启用，抱歉造成不便）

* Added a new functional button in the top right corner of the Siyuan menu bar  
  * Added a quick chat feature that can summon a corresponding window from the top (does not save history locally)  
  * Added an inline chat feature that can output chat responses directly within Siyuan documents  
* Fixed the issue where the URL does not update promptly when switching models  
* Optimized plugin styles  
* Removed unnecessary built-in model configurations
* Temporarily disable the formula rendering feature (this functionality will be re-enabled in the next version, sorry for the inconvenience caused).
