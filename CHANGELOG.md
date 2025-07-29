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
* 修复了模型切换时 URL 依旧更新不及时，需要重启思源的问题
* 优化了插件样式
* 删除了不常用的内置模型配置
* 暂时取消公式渲染功能（下个版本将重新启用，抱歉造成不便）
* 短期内不再添加新功能，以修复 bug 和改善插件稳定性为主
* 遇到明显 bug， 请重装插件，并且可以进行反馈，如果造成不便敬请谅解
* 由于各提供方 API 的调用参数各不相同，暂无法做到使用模型的全部功能（敬请等待后续优化）

* Added a new function button in the top menu bar of EverEdit  
  * Added a "Quick Chat" feature, which can pop up a corresponding window at the top (the chat records will not be saved locally)  
  * Added an inline chat feature, which can output the chat responses directly within the EverEdit file  
* Fixed the issue where the URL was not updated promptly when switching models, requiring a restart of EverEdit  
* Optimized the plugin's style  
* Removed less commonly used built-in model configurations  
* Temporarily disabled the formula rendering function (it will be re-enabled in the next version, sorry for the inconvenience)  
* In the short term, no new features will be added, focusing on bug fixes and improving plugin stability  
* If you encounter any obvious bugs, please reinstall the plugin and provide feedback. We apologize for any inconvenience caused  
* Due to the different API parameters from various service providers, it is temporarily not possible to use all the functions of the model (please wait for future optimizations)

## v0.10.0

* 模型提供方可整体隐藏
* 可隐藏单个模型
* 支持模型收藏
* 支持模型额外参数添加（如 enable_thinking 等控制模型思考的参数）
* 新增 Anthropic 以及火山引擎内置提供方
* 优化了插件样式
* 模型配置逻辑进行了重构，因此本次更新会删除已有配置，造成的不便敬请谅解
* 由于各提供商计费逻辑差异较大，插件将不再支持费用计算，仅支持 token 计算
* 公式渲染功能仍在优化中，该版本暂不开放

* Model providers can be hidden as a whole
* Individual models can be hidden
* Support for model favorites
* Support for adding additional model parameters (such as enable_thinking, etc., which control the model's thinking)
* Added built-in providers for Anthropic and Volcano Engine
* Optimized the plugin's style
* The model configuration logic has been refactored, so this update will delete existing configurations. We apologize for any inconvenience caused.
* Due to the significant differences in billing logic among various providers, the plugin will no longer support cost calculations, only token calculations.
* The formula rendering function is still being optimized and will not be available in this version.

## v0.10.1

* 修复了行内对话框不显示内容的问题

* Fixed the issue where the inline dialog box does not display content

## v0.10.2

* 修复了弹出无法读取模型配置且插件无法使用的问题
* 该问题是由于旧版本存储的当前模型配置与新版本的配置结构产生了冲突。现已完善数据迁移逻辑

* Fixed the issue where the popup could not read the model configuration and the plugin could not be used.
* This issue was caused by a conflict between the configuration structure of the old version storage and the new version. The data migration logic has now been improved.

## v0.10.3

* 添加思源块到输入框功能支持自动过滤HTML标签
* 添加思源块到输入框功能支持选择文本格式（Markdown、纯文本、HTML）
* 改进了插件样式
* 在0.10.0版本中，所有模型提供方默认隐藏，因此更新完成时模型面板时空白的。本次更新在面板中添加了提示信息

* The feature of adding a SiYuan block to the input box supports automatic filtering of HTML tags.
* The feature to add a SiYuan block to the input box supports selecting text formats (markdown, plain text, html).
* Improved the plugin style  
* In version 0.10.0, all model providers are hidden by default, so the model panel is blank after the update is completed. This update adds prompt information to the panel.

## v0.10.4

* 修复了 OpenRouter 以及 API易提供商模型的 token 计算问题

* Fixed the token calculation issue for OpenRouter and the API provider model.

## v0.11.0

* 添加了窗口设置按钮（右上角设置栏）
* 可将插件侧边窗口分离为独立窗口"
* 独立窗口时支持快速居左、居中、居右布局、支持置于顶层

* Added a window settings button (top right settings bar)
* Can detach the plugin side window into an independent window
* When the window is detached, it supports quick left, center, right layout, and supports being on top

## v0.12.0

* 输入框添加了自定义对话参数按钮
* 支持便捷覆盖插件设置中的对话参数

* Input box added custom conversation parameters button
* Support convenient override of conversation parameters in plugin settings

## v0.13.0

* 支持对话中重置上下文
* 使用方法：模型输出消息右下方的工具栏→“更多选项”→“重置上下文”
* 重置上下文后，当前对话的上下文会被清空，模型会根据新的输入进行问答，同时会出现“新话题”标志
* 点击“新话题”标志可撤销重置上下文操作
* 修复了消息工具栏“编辑内容”中的“重新生成”选项不可用的问题

* Support for resetting the context in the conversation
* How to use: Model output message bottom right toolbar → 'More options' → 'Reset context'
* After resetting the context, the current conversation's context will be cleared, and the model will answer based on new input, while a 'New topic' label will appear
* Clicking the 'New topic' label will cancel the reset context operation
* Fixed the problem that the "Re-generate" option in the "Edit content" toolbar is not available

## v0.13.5

* 公式渲染功能开放

* The formula rendering function is now open

## v0.13.7

* 修复了快速对话和行内对话无法使用的问题（相关配置与重置上下文逻辑存在冲突）

* Fixed the issue where quick conversations and inline conversations could not be used (related configuration and reset context logic exist conflicts)

## v0.14.0

* 侧栏输入框支持“@”键快捷调出上下文面板
* 上下文面板支持上下键切换选项、Esc 切换层级、Enter 键选择

* The sidebar input box supports the "@ " key to quickly call out the context panel
* The context panel supports switching options with the up and down keys, Esc key to switch levels, Enter key to select

## v0.14.1

* 修复侧栏输入框中占位符的错误（“^C”改为“^V”）

* Fix the error in the placeholder of the sidebar input box (“^C” changed to “^V”)

## v0.15.0

* 修复了插件导致思源界面加载时间增加的问题
* 修复了上下文选择面板的选项无法点击的问题
* 当退出 @ 键快捷调出的上下文面板后，光标自动还原到输入框中
* 上下文面板的键盘切换功能仍存在问题，将在未来几个版本中修复

* Fixed the issue causing the loading time of the Siyuan interface to increase due to the plugin.
* Fixed the issue where the options in the context selection panel could not be clicked.
* When exiting the @ key shortcut to call out the context panel, the cursor will automatically be restored to the input box.
* The keyboard switching function of the context panel still has issues and will be fixed in future versions.

## v0.16.0

* 支持对话中 mermaid 流程图渲染
* 支持代码块插入到思源文档中
* 代码块插入到思源文档前，需用鼠标点击一下待插入的位置（此位置应是一个思源块）

* Support mermaid flowchart rendering in conversation
* Support inserting code blocks into Siyuan documents
* Before inserting code blocks into Siyuan documents, you need to click the position where you want to insert with the mouse (this position should be a Siyuan block)

## v0.16.5

* 添加了输入框便捷插入设置，支持替换和追加两种模式
* 修复了对话气泡显示问题：输入框中的单次回车不显示换行（需连续回车两次）
* 优化了插件设置界面样式
* 优化了插件对话气泡的 Markdown 渲染样式

* Added input box convenient insertion settings, supporting replace and append two modes
* Fixed the dialog bubble display issue: single carriage return in the input box does not display line breaks (need to press enter twice in a row)
* Optimized plugin settings interface style
* Optimized plugin dialog bubble Markdown rendering style
