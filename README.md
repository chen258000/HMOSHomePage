# 项目名称
* 适用于手机/平板的浏览器主页（兼容pc端浏览器，如edge、chrome、hwbrowser）
# 功能介绍
* 自定义搜索引擎
* 自定义图标颜色
* 自定义LOGO、壁纸
* 自定义LOGO的点击/长按功能
* 自定义主页搜索栏样式（细圆、方正）
* 自定义搜索历史是否保存
* 自定义夜间模式（手动、跟随浏览器、定时）
* 支持备份数据、检查更新。
* 搜索栏、书签支持http、https、ftp、file类URL转跳（file类型URL仅支持本地主页）
# 图标来源
* 主要为“Pure轻雨”图标包，部分改自官方LOGO
# 相关地址
* 在线使用地址：https://icedwatermelonjuice.github.io/HMOSHomePage/
* Github仓库：https://github.com/IcedWatermelonJuice/HMOSHomePage/
* Gitee仓库：https://gitee.com/gem_xl/HMOSHomePage
# 感谢项目
* liumingye/quarkHomePage 
* 原仓库地址：https://gitee.com/liumingye/quarkHomePage/
# 联系方式
* Email：gem_xl@petalmail.com
# 更新日志
<版本 1.8>
* 修改了精选页“热搜榜”替换来源，并改名为“微博热搜榜”，“知乎热榜”替换来源，改名为“知乎热搜榜”
* 修改了设置页的文字说明
* 增加了“自动夜间模式（用户定时）”功能，可以定时开启夜间模式而不是简单的跟随浏览器
* 当启用“自动夜间模式（跟随浏览器）”时，将屏蔽“夜间模式”与“自动夜间模式（用户定时）”两个选项；当启用“自动夜间模式（用户定时）”时，将屏蔽“夜间模式”与“自动夜间模式（跟随浏览器）”两个选项
* 针对via浏览器，屏蔽无法使用的“自动夜间模式（跟随浏览器）”功能
* 修改默认设置。现在将根据via浏览器、x浏览器、其他浏览器（如chromium内核浏览器）的不同，拥有不同的默认设置，体验更佳

<版本 1.7>
* 设置“关于”增加版本检测功能
* 修复了PC端Edge浏览器LOGO功能设置选项中，有时候会出现“打开书签”选项的BUG

<版本 1.6>
* 增加“点击/长按LOGO”功能设置，可以在打开书签（由于chromium内核限制，书签功能仅Via浏览器和X浏览器可用，其他浏览器意屏蔽该选项）、打开设置、打开精选，三者任选（LOGO功能和书签至少要有一个为设置）
* 修改默认设置：Via浏览器和X浏览器，点击LOGO打开书签，长按LOGO进入设置；其他浏览器，点击LOGO打开精选，长按LOGO进入设置
* 
<版本 1.5>
* 修复了本地主页时，设置页无法通过点击Github/Gitee转跳网页的BUG
* LOGO长按/点击逻辑调整，从而适配PC端：对于Via浏览器和X浏览器，点击可以打开书签，长按可以打开设置；对于其他浏览器如Kiwi浏览器，点击长按均为打开设置页
* 设置页描述性文字修改，整体UI略微改动
* 
<版本 1.4>
* 修改设置页（Github与Gitee跳转暂仅支持非本地主页，正在抓紧修复中）
* 新增“恢复默认书签和设置”功能
* “导入/导出主页数据”功能在原本正常“书签”数据基础上，额外支持“设置”数据

<版本 1.3>
* 默认LOGO适配夜间模式
* 新增“自动夜间模式”功能，可跟随浏览器夜间模式（默认开启）。支持PC端Edge浏览器，移动端Kiwi浏览器、X浏览器。暂不支持移动端Via浏览器、华为浏览器、Alook浏览器。其他浏览器效果未知。

<版本 1.2>
* 书签、搜索栏支持“file:///”类型本地URL(本地主页时可用)

<版本 1.1>
* 修改首页默认书签
* 精选页面调整修改

<版本 1.0>
* 修改默认设置：搜索引擎默认为“百度”，搜索栏样式默认为“细圆”，历史记录默认为“不记录”
* 修改首页LOGO，采用华为“HarmonyOS”官方LOGO图标
