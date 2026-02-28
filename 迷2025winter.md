20250828 今天收到新手机，真的很高兴！

Godot + .NET 强强联合，香在哪里？

✅ 彻底免费：MIT开源协议，商业项目也绝无任何费用与抽成！真正做到收益全归你！
✅ 极致轻量：引擎本体仅80M，下载解压即用，低配电脑也能流畅运行！
✅ C#原生支持：拒绝冷门语言！Godot完美支持.NET，语法与Unity神似，初学者也能快速上手！
✅ 设计超前：独特的节点（Node）系统，像搭积木一样构建游戏，开发效率直接拉满！
✅ 2D之王：原生2D渲染效果吊打一众3D引擎改2D，像素游戏开发者的首选！

3分钟创建你的第一个Godot C#游戏！（实战步骤）

Dev snapshot: Godot 4.5 beta 6
https://github.com/godotengine/godot-demo-projects

Telegram是一款专注于安全性和速度的即时通讯应用，支持多平台，包括Android、iOS、Windows和macOS。Telegram的源代码是开源的，开发者可以使用其API和源代码创建自己的应用程序。

获取Telegram源代码

Telegram的Android版本源代码可以在GitHub上找到，具体地址为DrKLO/Telegram。你可以通过以下步骤获取和编译Telegram的源代码：

下载源代码：从GitHub下载Telegram源代码： git clone https://github.com/DrKLO/Telegram.git

配置编译环境：你需要Android Studio 3.4、Android NDK rev. 20和Android SDK 8.1。将你的release.keystore文件复制到TMessagesProj/config目录，并在gradle.properties文件中填写相关的密码信息。

配置Firebase：访问Firebase控制台，创建两个Android应用程序，应用程序ID分别为org.telegram.messenger和org.telegram.messenger.beta，然后下载google-services.json文件并复制到TMessagesProj目录下。

配置API ID和API Hash：登录my.telegram.org，申请api_id和api_hash，然后替换TMessagesProj/src/main/java/org/telegram/messenger/BuildVars.java文件中的APP_ID和APP_HASH字段。

编译运行程序：在Android Studio中打开项目（注意是打开而不是导入），填写BuildVars.java中的变量值，然后编译运行Telegram。

kitten tts
pip install https://github.com/KittenML/KittenTTS/releases/download/0.1/kittentts-0.1.0-py3-none-any.whl

```
from kittentts import KittenTTS
m = KittenTTS("KittenML/kitten-tts-nano-0.2")

audio = m.generate("This high quality TTS model works without a GPU", voice='expr-voice-2-f' )

# available_voices : [  'expr-voice-2-m', 'expr-voice-2-f', 'expr-voice-3-m', 'expr-voice-3-f',  'expr-voice-4-m', 'expr-voice-4-f', 'expr-voice-5-m', 'expr-voice-5-f' ]

# Save the audio
import soundfile as sf
sf.write('output.wav', audio, 24000)
```

StackBlitz Bolt.new：AI+WebContainers的“全栈开发神器”
StackBlitz Bolt.new将AI与WebContainers融合，八周实现2000万美元ARR增长。以“创建Markdown编辑的Next.js博客”为例，传统数小时流程被压缩至分钟级。

3分钟开发全流程

访问bolt.new加载WebContainers沙箱
输入prompt生成代码
自动npm install并启动服务器
实时预览并一键部署至Netlify
这种“即开即开发”体验消除环境差异，支持跨设备协作，团队成员可在平板等任何设备继续开发[19]。

https://udlbook.github.io/udlbook/?ref=aihackr

https://github.com/bravenewxyz/agent-c A ultra-lightweight AI agent written in C that communicates with OpenRouter API and executes shell commands.

Naive UI Pro 发布！Vue3 开箱即用！
𝙂𝙤𝙤𝙜𝙡𝙚 𝙋𝙞𝙭𝙚𝙡 10

https://arxiv.org/abs/2401.03568 Agent AI: Surveying the Horizons of Multimodal Interaction 李飞飞

WPF界面 vs MAUI界面
⚠️ 避坑指南（血的教训）
iOS闪屏卡启动页：Info.plist里必须声明启动图！
Android权限无效：MainActivity.cs要动态申请！
依赖注入报错：改用MauiProgram.cs注册服务

rendergit：一键渲染 GitHub 仓库为静态网页的工具。该项目可以一键将 GitHub 仓库代码渲染为单页静态 HTML，提供便于阅读的 Human 模式，支持语法高亮、Markdown 渲染和侧边栏导航等功能。同时还支持 LLM 模式，方便将项目代码快速复制到 AI 工具作为上下文。

Nuitka is the optimizing Python compiler written in Python that creates executables that run without a separate installer. Data files can both be included or put alongside.
python -m pip install -U "https://github.com/Nuitka/Nuitka/archive/develop.zip"

AI时代，是时候告别Django和Flask 拥抱FastAPI了！

Framework Laptop 12 is a 12.2” convertible with stylus support. Designed for easy customization, upgrades, and repairs. https://frame.work/laptop12 模块化笔记本

Framework Laptop 16 is an endlessly customizable laptop with upgradeable graphics, powered by NVIDIA® GeForce RTX™ 5070 and AMD's latest Ryzen™ AI 300 Series processors. https://github.com/FrameworkComputer/Framework-Laptop-16

https://github.com/PixiEditor/PixiEditor
PixiEditor 是一款基于 .NET 构建、开源（LGPL-3.0 license）、功能强大、通用的 2D 图形编辑器，旨在为您提供满足所有 2D 需求的工具和功能。为您的游戏、动画创建精美的精灵，编辑图片，设计标志。所有功能都集成在一个直观且熟悉的界面中。3种工具集
- 像素艺术(Pixel art)：包含适用于像素级精确场景的工具。
- 绘画(Painting)：基础绘画工具，柔软画笔，抗锯齿形状。
- 矢量(Vector)：用于创建矢量的形状与路径。

Q1：什么是智能体客户端协议ACP？

A：ACP是谷歌与Zed Industries联合推出的标准化协议，用于AI智能体与集成开发环境的整合。它通过JSON-RPC over stdio进行通信，重用模型上下文协议规范，并提供TypeScript和Rust实现库。

1、侪（chái）辈
2、盥（guàn）洗
3、觊觎（jì yú）
4、痉（jìng）挛
5、踟蹰（chí chú）
6、傀（kuǐ）儡
7、耒耜 (lěi sì)
 8、彘肩 (zhì jiān)
9、囹圄 (líng yǔ)
10、馄饨 (hún tun)
11、绯闻 (fēi wén)
12、嫉妒 (jí dù)
13、潜力 (qián lì)
14、惩罚 (chéng fá)
15、勉强 (miǎn qiǎng)
16、粗犷 (cū guǎng)
17、压轴 (yā zhòu)
18、蛤蜊 (gé  lí‌）
19、皈 (guī）依
20、诡谲 (guǐ jué）
21、颔 (hàn）首
22、沟壑（gōu hè）
23、赧然（nǎn rán）
24、饾饤（dòu dìng）
25、乜斜（miē xie）

32.4K星标一夜刷屏，开源数据库设计工具DrawDB

C与C++头文件建议使用#pragma once替换 #ifndef XXX、#define XXX、#endif是C/C++头文件的保护“铁三角”机制

Go开发者必备工具chromedp，基于Chrome DevTools协议实现高性能浏览器自动化，支持页面导航、元素交互、JS执行等核心功能，提供截图导出、反爬策略等高级特性

https://github.com/dockur/windows 
https://automatic-potato-wxgp6x7wjf5x6v.github.dev/

So for a better experience you can connect using any Microsoft Remote Desktop client to the IP of the container, using the username Docker and password admin.

There is a RDP client for Android available from the Play Store and one for iOS in the Apple Store. For Linux you can use FreeRDP and on Windows just type mstsc in the search box.

How do I run macOS in a container?
You can use dockur/macos for that. It shares many of the same features, except for the automatic installation.

How do I run a Linux desktop in a container?
You can use qemus/qemu in that case.


1、媾和（gòu hé）
2、痤 (cuó) 疮
3、皈 (guīicon) 依
4、龋 (qǔ) 齿
5、鞭笞 (chī）
6、针砭 (biān)
7、莅 (lì) 临
8、贿赂 (lù)
9、木讷 (nè)
10、伛偻 (yǔ lǚ)
11、老妪 (yù)
12、晕 (yùn) 车
13、参与 (yù)
14、熨 (yùn) 帖
15、噱（xué）头
16、咋（zé）舌
17、殷（yān）红
18、内讧（hòng）
19、拓（tà）本
20、豆萁（qí）
21、整饬（chì）
22、延宕（dàng）
23、翌（yì）日
24、肴馔（zhuàn）
25、渣滓（zǐ）

itch.io
FCEUX（经典 NES/FC 模拟器）

bun build ./cli.ts --compile --outfile mycli
All imported files and packages are bundled into the executable, along with a copy of the Bun runtime. All built-in Bun and Node.js APIs are supported.
When deploying to production, we recommend the following:

bun build --compile --minify --sourcemap ./path/to/my/app.ts --outfile myapp
You can also generate standalone executables using the Bun.build() JavaScript API.

https://www.github-zh.com/top github排行榜TOP200

对于母语是英语的人，Godot 的发音为 “GOD-oh”，其中 “t” 不发音。这个发音类似于法语原版的发音。
具体来说，Godot 的英语音标为 /ˈɡɒdoʊ/。这种发音方式在戏剧《等待戈多》中也是如此。
此外，Godot引擎的名称应该总是以标题的形式出现，并且应该只有一个大写字母，即 “Godot”

## 2025-09-03
### Build Git from source on Linux, Debian / Ubuntu
Git requires the several dependencies to build on Linux. These are available via apt:

1. From your shell, install the necessary dependencies using apt-get:

$ sudo apt-get update
$ sudo apt-get install libcurl4-gnutls-dev libexpat1-dev gettext libz-dev libssl-dev asciidoc xmlto docbook2x
2. Clone the Git source (or if you don't yet have a version of Git installed, download and extract it):

$ git clone https://git.kernel.org/pub/scm/git/git.git
3. To build Git and install it under /usr, run make:

$ make all doc info prefix=/usr
$ sudo make install install-doc install-html install-info install-man prefix=/usr

Jira是由澳洲Atlassian公司开发的一款流行的项目管理和缺陷跟踪工具，主要用于软件开发中的敏捷项目管理、问题跟踪和任务管理。它支持多种敏捷方法（如Scrum和看板），提供问题类型（如Story、Task、Bug、Epic）和强大的配置功能，并且可以根据团队需求进行定制化。Jira有云端（Cloud）和数据中心（Data Center）两种部署模式，并且有Jira Software、Jira Service Management等针对不同团队需求的产品。﻿

ConEmu is an advanced console window where you can run any shell of your choice

Flyoobe
From bypassing hardware restrictions to giving you fine-tuned control over setup, Flyoobe makes installing and configuring Windows as fast, clean, and personal as it should be.

Confluence是一个知识管理和团队协作工具，主要用于文档分享、讨论和知识积累。 它支持创建和管理各种类型的内容，包括会议记录、项目文档和企业wiki。 相比之下，Jira是一个项目管理和问题跟踪工具，专注于帮助团队高效地管理软件开发过程。 它支持敏捷开发、任务分配、进度跟踪和报告功能。

https://nanobananaai.com/
https://lmarena.ai/

https://massgrave.dev/
irm https://get.activated.win | iex

gitea

https://github.com/shiyu-coder/Kronos
Kronos: A Foundation Model for the Language of Financial Markets

根据 DistroWatch 的统计，目前活跃的 Linux 发行版有 300 多个，总数超过 1000 个！
常见的有：
Debian 家族：Debian、Ubuntu、Linux Mint
Red Hat 家族：RHEL、CentOS、Fedora、Rocky Linux、AlmaLinux
独立派：Arch Linux、Gentoo、Slackware、openSUSE
面向安全的：Kali Linux、Parrot OS
面向嵌入式的：Yocto、OpenWrt

Tesla 几千美元的房子

开源AI语音转写神器 Whispering：22MB 本地部署秒开
https://github.com/epicenter-so/epicenter/tree/main/apps/whispering


曾经有人对稚晖君所具有的技能做了总结，他的技能包括：
电子基础、电子元器件选型、电路原理图设计、高速电路 PCB 设计、电子元器件焊接技术、电路板调试、启动程序 UBOOT 裁剪移植、Linux 内核裁剪移植、文件系统、底层驱动程序（C语言、ARM 架构汇编、Linux 内核架构）、上层应用程序（C++、Qt、JAVA、Python等，深度学习，机器学习，OpenCV，神经网络，自然语言处理）、静态博客服务器搭建、高等数学、线性代数、概率论、离散数学、3D 建模、3D 打印、雕刻机、视频拍摄后期制作、防脱发技术等。

这些技能中有哪些是我们作为嵌入式工程师必须掌握的？它们的学习路线又是怎样的？

https://github.com/microsoft/rd-agent

什么是 tzst？
简单说，它就是 tar 归档 + Meta（Facebook）的 Zstandard 算法的组合，完美处理大文件和海量小文件！

Vibe Coding（氛围编码）

P2P File Transfer is a prototype of peer-to-peer file sharing system implemented in Go. It heps in large transfers between peers by dividing files into chunks, and using a central server for peer discovery and metadata management.

`npm create vue@latest my-app --template vapor`

Prompt-Optimizer: AI 提示词优化神器
prompt.always200.com
https://github.com/linshenkx/prompt-optimizer

https://xianyu110.github.io/awesome-nano-banana/
Awesome curated collection of images and prompts generated by gemini-2.5-flash-image (aka Nano Banana) state-of-the-art image generation and editing model. Explore AI generated visuals created with Gemini, showcasing Google’s advanced image generation capabilities.
案例 91：谷歌地图变身古代藏宝图

https://0bcd5baf6c08e24956.gradio.live/
https://github.com/microsoft/VibeVoice Frontier Open-Source Text-to-Speech

最近科技圈被一句话炸锅了：“现在的AI，在GroK4面前都是‘半成品’”。说这话的不是别人，正是马斯克。7月刚推出的GroK4，才半个月就把GPT-5、Claude 3这些“老大哥”比下去了—
最近科技圈被一句话炸锅了：“现在的AI，在GroK4面前都是‘半成品’”。说这话的不是别人，正是马斯克。7月刚推出的GroK4，才半个月就把GPT-5、Claude 3这些“老大哥”比下去了

ttps://github.com/abdullah-erturk/pmas
PMAS - PowerShell Multi Activation System (TSF/HWID/OHOOK Activation)

有的人喜欢Claude，有的人喜欢Gemini，还有的人更倾向于GPT-5/Codex，又或是Grok Code。
评论区，一位网友问Karpathy有没有尝试过grok-code-fast-1？

npm install -g @openai/codex 
codex

https://marketplace.visualstudio.com/items?itemName=openai.chatgpt

标准	发布时间	主要特性
C89	1989/1990	函数原型、标准库规范
C99	1999	变长数组、单行注释、long long、灵活变量声明
C11	2011	线程支持、类型泛型、静态断言
C17	2018	C11 的缺陷修复
C23	2023	nullptr、二进制常量、属性语法

通过学习这些标准，你就能理解 C 语言程序在不同编译环境中的运行差异，进而根据项目需求选择合适的编译器选项（例如 -std=c99）。

ai.studio/banana
https://ai.google.dev/gemini-api/docs/image-generation?hl=zh-cn#rest_1

https://github.com/libuv/libuv
libuv 是一个高性能、跨平台的异步 I/O 支持库，专为需要高效处理非阻塞 I/O 操作的 C/C++开发者设计。它最初为Node.js开发，用于提供事件驱动的异步 I/O 能力，如今已被广泛应用于 Luvit、Julia、uvloop 等多种项目。libuv 的核心目标是简化跨平台异步编程，提供统一的事件循环机制，屏蔽底层操作系统差异，让开发者专注于业务逻辑而无需深陷平台特定的 I/O 处理细节。无论是网络编程、文件操作还是多线程任务调度，libuv 都能提供高效、可靠的支持，特别适合需要高并发、低延迟的应用程序。
libuv 是一个高性能、跨平台的异步 I/O 支持库，专为需要高效处理非阻塞 I/O 操作的 C/C++开发者设计。它最初为Node.js开发，用于提供事件驱动的异步 I/O 能力，如今已被广泛应用于 Luvit、Julia、uvloop 等多种项目。libuv 的核心目标是简化跨平台异步编程，提供统一的事件循环机制，屏蔽底层操作系统差异，让开发者专注于业务逻辑而无需深陷平台特定的 I/O 处理细节。无论是网络编程、文件操作还是多线程任务调度，libuv 都能提供高效、可靠的支持，特别适合需要高并发、低延迟的应用程序。

寒武纪
寒武纪成立于2016年，专注于人工智能芯片产品的研发与技术创新，
致力于打造人工智能领域的核心处理器芯片，让机器更好地理解和服务人类。
 
寒武纪提供云边端一体、软硬件协同、训练推理融合、具备统一生态的系列化智能芯片产品和平台化基础系统软件。寒武纪产品广泛应用于服务器厂商和产业公司，面向互联网、金融、交通、能源、电力和制造等领域的复杂 AI 应用场景提供充裕算力，推动人工智能赋能产业升级。
陈云霁 陈天石兄弟👬
Fellou.ai
Agentic AI Browser for Deep Search …
Deep action: Fellou independently plan and execute complex web and desktop based tasks across multiple apps to achieve your goals. Deep search: Fellou automates in-depth research across the entire internet, including logged-in accounts on pla…

Pocket Flow: Codebase to Tutorial

code2tutorial.com/

BlogKeeper - 文捕 - 博客内容一键解析下载工具 https://blog-keeper.com/

Google Docs 中使用markdown
Google supports Markdown. Inside of a Google App, select Tools, then Preferences. Next, check the box beside “Automatically detect Markdown”

https://marp.app/  The Marp ecosystem contains a rich toolset to assist your work. Marp for VS Code is an extension that allows you to edit and preview slide Markdown and custom theming within VS Code. Marp CLI is a command line tool allows you to convert Markdown with a simple CLI interface. ... and much more!

C++的GUI框架
1

C++提供了多种GUI框架，适用于不同的开发需求，包括跨平台支持、Windows专用开发、游戏图形开发以及嵌入式系统开发。以下是一些常见的C++ GUI框架及其特点和适用场景：

跨平台GUI框架

Qt 是一个功能强大的跨平台框架，支持Windows、macOS、Linux、Android和iOS。它提供丰富的GUI组件、信号与槽机制以及多媒体、网络和数据库支持，适合需要跨平台支持的桌面应用开发。

wxWidgets 是一个开源框架，支持Windows、macOS和Linux，提供原生外观和丰富的GUI组件，适合需要跨平台且保持原生外观的应用。

FLTK 是一个轻量级的跨平台库，支持OpenGL，适合图形密集型应用或需要快速响应的轻量级应用。

GTK+ 主要用于Linux桌面环境（如GNOME），也支持Windows和macOS，适合Linux桌面应用开发。

Windows专用框架

WinAPI 是微软提供的底层API，功能强大但学习曲线较陡，适合需要高度定制化的Windows应用。

MFC 是基于WinAPI的C++类库，提供更高层次的抽象和丰富的GUI组件，适合快速开发Windows桌面应用。

WTL 是一个轻量级的C++模板库，基于ATL，适合需要高效轻量的Windows应用。

游戏和图形开发框架

SFML 是一个跨平台库，提供图形、音频和网络模块，适合游戏和多媒体应用开发。

SDL 是一个多媒体库，支持多种平台，适合图形密集型应用和游戏开发。

OpenGL 是一个高性能图形API，适合开发需要2D/3D渲染的应用，如游戏和CAD软件。

DirectX 是微软提供的API，专注于Windows平台的高性能图形和多媒体开发。

嵌入式和低级开发框架

Qt for Embedded 是Qt的嵌入式版本，支持嵌入式Linux和Windows Embedded，适合嵌入式系统的图形界面开发。

EFL 是一个轻量级框架，主要用于嵌入式系统，适合需要高效运行的嵌入式应用。

其他框架

Dear ImGui 是一个即时模式的GUI库，轻量高效，适合嵌入式GUI和游戏开发。

Ultimate++ 是一个跨平台框架，提供丰富的GUI组件，适合快速开发跨平台桌面应用。

根据具体需求选择合适的框架，可以显著提高开发效率和应用性能。例如，跨平台开发推荐使用Qt或wxWidgets，而Windows专用开发可以选择MFC或WinAPI。对于游戏和图形开发，SFML和OpenGL是强大的工具，而嵌入式开发则可以考虑Qt for 

https://h5login.qqchess.qq.com/

中文名
御名方守矢
外文名
Moriya Minakata
别名
御名
性别
男
登场作品
月华之剑士
月华之剑士2
拳皇wing

御名方守矢，格斗游戏《月华剑士》及其衍生作品中的角色之一。

御名方守矢，17岁就超越了师父的天才剑士，表面上冷酷无情，很少有人理解他那颗高傲孤独的心，其实，守矢一直在关心着他的师弟阿枫和师妹阿雪。他的象征之物是“满月”，浑身带满了金制饰物。

拳皇97


FLTK

The Fast Light Tool Kit (FLTK) is a cross-platform C++ GUI toolkit for UNIX®/Linux® (X11 or Wayland), Microsoft® Windows®, and macOS®. FLTK provides modern GUI functionality without bloat and supports 3D graphics via OpenGL® and its built-in GLUT emulation. It was originally developed by Mr. Bill Spitzak and is currently maintained by a small group of developers across the world with a central repository on GitHub.  
https://www.fltk.org/ https://github.com/fltk/fltk/

https://gitlab.com/veloren/veloren
Veloren is a multiplayer voxel RPG written in Rust. It is inspired by games such as Cube World, Legend of Zelda: Breath of the Wild, Dwarf Fortress and Minecraft.

选型口诀：小团队轻量选Gitea，合规场景锁定Gitee，全功能协作用GitLab！
B3. 手把手教你搭建：Gitea实战步骤
用Gitea搭建服务器就像搭积木，3步完成，全程复制粘贴命令：
B3.1 环境准备（10分钟）
# Ubuntu系统一键安装依赖
sudo apt update && sudo apt install -y git docker.io docker-compose
sudo systemctl enable --now docker  # 启动Docker
B3.2 安装Gitea（一行命令）
docker run -d -p 3000:3000 -p 22:22 --name gitea -v /data/gitea:/data gitea/gitea:latest
B3.3 初始化配置（3分钟）
打开浏览器访问http://服务器IP:3000，按提示设置：
数据库选SQLite（免配置）
管理员密码用"大小写+数字+符号"
仓库路径选/var/lib/gitea/repositories
图片来源：CSDN博客安装教程
成功标志：看到登录界面就搞定！默认管理员账号是admin。
B4. 安全配置：6步筑牢防线
B4.1SSH密钥登录（必做）
# 本地生成密钥（按回车到底）
ssh-keygen -t ed25519 -C "你的邮箱"
# 复制公钥到服务器（替换IP）
ssh-copy-id -p 22 git@服务器IP
这样操作后，克隆代码不用输密码，还能防暴力破解！
B4.2 2025年漏洞紧急修复
⚠️高危漏洞CVE-2025-48384已被利用，立即执行：
# 升级Git到安全版本
sudo apt update && sudo apt install git -y
# 验证版本（需≥2.43.7）
git --version


flowith.io 无限执行的AI智能体 Agent Neo
https://www.codefather.cn/ 程序员 鱼皮

https://github.com/TapXWorld/ChinaTextbook

手心输入法 utools
https://jimeng.jianying.com/ai-tool/home

https://ftp.mozilla.org/pub/firefox/releases/143.0b9/win64/en-US/

Feb 7, 2023 — IBM's first AI-optimized, cloud-native supercomputer, Vela. It has been online since May of 2022, housed within IBM Cloud, and is currently just for 

Xiaomi Vela 是小米基于开源实时操作系统NuttX 打造的物联网嵌入式软件平台，Vela 在各种物联网硬件平台上提供统一的软件服务，支持丰富的组件和易用的框架，

单文件执行与Shebang支持
单文件脚本开发流程简化为：
csharp 
#!/usr/bin/dotnet run
:package Newtonsoft.Json@13.0.3
using Newtonsoft.Json;
Console.WriteLine(JsonConvert.SerializeObject(new { name = "单文件执行" }));
赋予执行权限后直接运行：chmod +x app.cs && ./app.cs，告别传统项目配置繁琐步骤。

.NET的Blazor框架直接让C#开发者实现"前后端一把梭"——用C#写Web UI，编译为WebAssembly在浏览器运行，性能接近原生应用：
•技术原理：Blazor组件直接编译为wasm，绕过JavaScript桥接，执行效率比React/Vue还高15%

一键唤起系统分享面板，直达微信、微博、Telegram，需HTTPS。
navigator.share?.({ title: '好文', url: location.href });

B12. WritableStream
逐块写入磁盘或网络，实时保存草稿、上传大文件更稳。
const writer = stream.writable.getWriter();
await writer.write(chunk);
B13.Background Fetch
PWA后台静默下载，断网恢复继续，课程视频提前缓存。
await registration.backgroundFetch.fetch('video', ['/course.mp4']);
B14.FileSystem Access
读写本地真实文件，需用户授权，Web IDE即开即用。
const [fh] = await showOpenFilePicker();
editor.value = await (await fh.getFile()).text();
B15.Clipboard
异步读写剪贴板，无需第三方库，HTTPS环境安全复制。
await navigator.clipboard.writeText('邀请码 9527');
B16. URLSearchParams
解析、修改、构造URL查询串，告别手写正则。
const p = new URLSearchParams(location.search);
p.set('page', 2);
history.replaceState({}, '', `?${p}`);
B17. structuredClone
深拷贝对象、数组、Map、Date，循环引用也能完美复制。
const copy = structuredClone(state)

Windows超级管理器是一款绿色全能系统工具箱，软件大小仅为6.7MB却包含了数十种功能模块。
Windows超级管理器 - 科利特尔软件网https://software.colithel.com/windows_super_manager

这两年，shadcn/ui 可谓火到出圈，霸榜各种榜单。它的设计风格极简、体验极佳，Star 数一路飙升，成为React开发者的首选 UI 组件库。不少人已经把它当作“前端标配”。
Now available: shadcn CLI 3.0 and MCP Server
最近，一个叫 shadcn-ui-mcp-server 的开源项目又给它带来了新玩法：你可以让代码助手“读懂”这个组件库，帮你查组件、写示例，甚至生成整页布局。说白了，就是多了个懂 shadcn 的搭档，能和你一起“拼 UI”。
Github：https://github.com/Jpisnice/shadcn-ui-mcp-server
https://ui.shadcn.com/docs/components/chart

智东西9月10日消息，今日上午，阿布扎比穆罕默德·本·扎耶德人工智能大学（MBZUAI）联合AI创企G42推出的新低成本推理模型K2 Think，相关论文已arXiv预印本平台发表，昨天下午模型在Hugging Face、GitHub上开源。
智东西9月10日消息，今日上午，阿布扎比穆罕默德·本·扎耶德人工智能大学（MBZUAI）联合AI创企G42推出的新低成本推理模型K2 Think，相关论文已arXiv预印本平台发表，昨天下午模型在Hugging Face、GitHub上开源。
K2 Think有320亿个参数，基于阿里巴巴的开源模型Qwen 2.5构建，性能超过参数规模是其20倍的OpenAI和DeepSeek旗舰推理模型。
K2 Think有320亿个参数，基于阿里巴巴的开源模型Qwen 2.5构建，性能超过参数规模是其20倍的OpenAI和DeepSeek旗舰推理模型。
在复杂数学任务基准测试中，研究人员计算了K2 Think在AIME24、AIME25、HMMT25和OMNI-Math-HARD中的平均得分，超过GPT-OSS、DeepSeek V3.1、Qwen3 235B-A22B等一众开源模型。
在复杂数学任务基准测试中，研究人员计算了K2 Think在AIME24、AIME25、HMMT25和OMNI-Math-HARD中的平均得分，超过GPT-OSS、DeepSeek V3.1、Qwen3 235B-A22B等一众开源模型。
K2 Think主页：
https://www.k2think.ai/
技术报告：
https://arxiv.org/abs/2509.07604


System.Text.Json作为.NET官方解决方案，已全面超越Newtonsoft.Json，成为JSON处理的首选工具。其零依赖特性、300%性能提升、持续的官方支持，使其成为现代.NET应用的必备技术。

Google ai Veo2 可免费使用了

Win11Debloat：优化系统流畅度！
https://github.com/Raphire/Win11Debloat

Warp, the intelligent terminal for developers
https://www.warp.dev

6️⃣AIX下载器 https://aixdownloader.com/zh
​​一键获取网页上所有图片、视频、音频和文档！ AIX下载器让你轻松下载所需内容，完全免费。

就今日(9月10号)，微软发布新一代宇宙第一IDE: Visual Studio 2026，当然是 Insiders（早期测试版）而非正式版。

卡罗琳·莱维特（Karoline Leavitt），女，1997年8月出生于美国新罕布什尔州[2]，美国白宫新闻发言人[1]。

bmp是什么格式

将 PDF 文档转换为 Doc 或 Docx 格式的文件。
完整代码示例如下：
using Spire.Pdf;

namespace ConvertPdfToFixedLayoutWord
{
    class Program
    {
        static void Main(string[] args)
        {
            //创建PdfDocument对象
            PdfDocument doc = new PdfDocument();

            //加载PDF文档
            doc.LoadFromFile("C:\\Users\\Administrator\\Desktop\\sample.pdf");

            //将PDF转换为Doc格式并保存到指定路径
            doc.SaveToFile("output/ToDoc.doc", FileFormat.DOC);

            //将PDF转换为Docx格式并保存到指定路径
            doc.SaveToFile("output/ToDocx.docx", FileFormat.DOCX);
            doc.Close();
        }
    }

如果您需要Spire.PDF for .NET的完整权限并希望解锁该产品的更多功能，可联系官方工作人员申请免费的30天临时许可证。

ZHO-ZHO-ZHO
/
ZHO-nano-banana-Creation
Public
我的 nano-banana 创意玩法大合集！ 持续更新中！

万里汇 蚂蚁集团

🧰 常用的Vibe Coding工具 目前已有一些工具支持这种开发方式，例如：

· Lovable：强调“零技术门槛”，适合产品经理等非技术人员快速验证想法。
· v0 (by Vercel)：专注于快速生成现代、美观的前端界面。
· Replit：在线编程环境，其AI代理能与你对话并理解项目类型。
· Cursor：一款强大的AI编程助手，适合更深度的定制和调试。
· Bolt.new：适合快速原型设计和MVP（最小可行产品）验证。

GitHub - umami-software/umami: Umami is a modern, privacy-focused ...
Umami is a simple, fast, privacy-focused alternative to Google Analytics. A detailed getting started guide can be found at umami.is/docs. A database. Umami
https://eu.umami.is/share/LGazGOecbDtaIwDr/umami.is
Umami Cloud a_boy@live.com
```
<script defer src="https://cloud.umami.is/script.js" data-website-id="6c271546-5c8e-40db-be7d-b2667d3d93de"></script>
```

罗罡是江西赣州宁都县固村镇人，效力于赣州市足球队，司职中场50号，曾效力苏州趣普仕、拉萨城投等俱乐部，百场经验成球队核心。

个人背景：

● 罗罡自幼随父母在广东梅州生活，在那里他接触并爱上了足球。

● 小学三年级时开始踢足球，展现出了过人的天赋。

职业生涯：

● 曾效力于苏州趣普仕、拉萨城投、云南昆陆、上海汇龙和云南玉昆钢铁等职业俱乐部。

● 积累了超过百场的职业比赛经验。

在赣州市足球队的表现：

● 在江西省城市足球超级联赛中，罗罡是球队的中场核心。

● 前三轮比赛中全部首发出场，表现稳定。

● 在对阵吉安队的比赛中，他在中场的组织和防守中发挥了重要作用。

罗罡以其丰富的经验和稳定的表现，成为了赣州市足球队的重要一员。


https://github.com/myshell-ai/MeloTTS/blob/main/docs/quick_use.md

IT之家 9 月 11 日消息，微软昨天发布博客，宣布个人开发者现可免费在Microsoft Store发布应用，无需再缴纳此前的 19 美元（IT之家注：现汇率约合 135.3 元人民币）注册费，惠及学生、编程爱好者。


芯片烧录程序的原理是将编译后的机器码程序和配置信息通过特定协议写入芯片内部的非易失性存储器，主要涉及物理基础、连接供电、通信协议、数据写入及验证等步骤。

1. 物理基础：芯片程序通常存储在Flash存储器或OTP存储器中。Flash存储单元基于浮栅晶体管，通过在控制极施加高压使电子注入浮栅来改变阈值电压表示0或1，擦除时施加反向高压。OTP存储器使用熔丝或反熔丝，通过高压烧断熔丝或击穿绝缘层来表示0或1。

2. 连接与供电：烧录器通过编程接口连接到芯片的专用引脚，提供稳定的编程电压。常用的编程接口包括ICSP、SWD、JTAG等。

3. 通信协议：烧录器与芯片通过同步串行协议通信，如SPI、I²C或厂商私有协议。典型指令包括全片擦除、写入程序、校验和写配置字等。

4. 数据写入流程：配置字是独立于程序存储区的特殊寄存器，控制芯片底层行为。某些存储器在写入前需要先擦除原有内容。

5. 数据验证：烧录完成后，烧录器会读取存储器内容并与原始数据对比，以确保烧录成功。

6. 保护与锁定：有些存储器支持写保护功能，可通过设置锁位防止内容被意外修改。

烧录器在这个过程中起到协议转换器的作用，将PC端的信号转换为芯片能识别的编程协议信号。通过这些步骤，芯片烧录程序确保芯片能够按照预期运行。若需更详细的信息，建议查阅相关技术文档或专业书籍。


ML.NET是微软推出的一个用于在.NET应用中进行机器学习的框架。它提供了简单易用的API，使得开发者可以轻松地训练和部署机器学习模型。

雷鸟RayNeo Air 3s Pro智能AR眼镜 高清巨幕观影眼镜 柯南联名款 https://rayneo.cn/v3.html 雷鸟发布新一代AR眼镜X3Pro，首发定价8999元起，国家补贴后7649元。

Arm 全新 Lumex CSS 平台 核心指标
1、CPU-C1-Ultra：较 Cortex-X925性能、单线程均升25%，视频快15%，宽微架构提效
2、CPU-C1-Pro：较 Cortex-A725 性能升12%，节能12%，优化Cortex A75
3、CPU-SME2：C1 集群含 SME2，矩阵效率升 5 倍，Gemma 3B 推理等降延迟4.7 倍
4、GPU-Mali G1-Ultra：首持移动下一代光追，性能升20%、能效升9%
5、系统架构：SI L1优带宽延迟，SLC功耗降 71%，支持 MTE 保安全
6、软件生态：获阿里、腾讯等采用

OpenAI o3成绩直接飙到了47分（满分50分）
人工智能数学奥林匹克（AIMO）创立于2023年，旨在推动开源AI模型在高阶数学推理的的发展。

3.cn  jd.com 京东域名

Google Labs
https://labs.google
Whisk - labs.google/fx
A new experimental tool that lets you use images as prompts to visualize your ideas and tell your story.

歡迎使用 Flow，這個 AI 電影製作工具能協助你輕鬆創作電影短片和場景，以連貫手法講述故事。這個平台專為創作者而生，也與創作者共同打造，並運用 Google 最先進的生成式模型。

提示：如要獲得創作靈感並瞭解 Flow 出色功能，請造訪 Flow TV。

网络热门4款AR眼镜的选购指南 （#Rokid Glasses，#INMO Air3，#雷鸟X3 Pro，#XREAL One Pro）

https://www.pythonanywhere.com/pricing/
Beginner: Free!
A limited account with one web app at your-username.pythonanywhere.com, restricted outbound Internet access from your apps, low CPU/bandwidth, no IPython/Jupyter notebook support. 
https://www.pythonanywhere.com/user/avvboy/files/home/avvboy

optimus机器人 tesla pi phone

IT之家 9 月 12 日消息，科技媒体 NeoWin 昨日（9 月 11 日）发布博文，报道称开发者 NTDEV 在github发布了全新脚本 nano11，可将原版 Windows 11 镜像体积压缩至约 2GB，并通过LZX压缩实现 2.8GB 装机空间，占用空间远低于原版近 20GB。它移除了Windows Update，因此用户无法为系统进行更新和维护。
https://github.com/ntdevlabs/nano11

科迪勒拉山系（Cordillera）是世界上最长的 褶皱山系，纵贯南北 美洲 大陆西部。 北起阿拉斯加，南到 火地岛，绵延约1.5万千米。 该山系的北美洲部分称为 落基山脉， 南 …

阿拉斯加州（State of Alaska）位于北美大陆西北端，东与加拿大接壤，另三面环北冰洋、白令海和北太平洋。该州拥有全美20座最高山脉中的17座，6194米的德纳里山是北美最高峰。世界上大多数活动冰川在阿州境内，其中最大的马拉斯皮纳

安第斯山脉（盖丘亚语：Andes；奇楚亚语：Antis），属于科迪勒拉山系，也称安第斯山脉或安蒂斯山脉，位于南美洲的西岸，全长约8900千米，宽约300千米，总面积在50万平方千米以上，是世界上最长的山脉。

https://pine64.org/devices/

深圳中学，中国中学的天花板！[赞][比心]

NVIDIA年初就宣布了“Project Digits”，号称桌面AI超级计算机，或者叫迷你AI工作站，这也是NVIDIA的第一款桌面级PC。
NVIDIA  DGX Spark基于自研的GB10超级芯片，台积电3nm工艺制造、2.5D封装技术，CPU部分有20个Armv9.2架构核心、两组共32MB三级缓存，GPU部分有6144个Blackwell架构的CUDA核心、24MB二级缓存，NVFP4格式算力1000 TOPS，然后还有14MB四级系统缓存。
热设计功耗高达140W，256-bit位宽LPDDR5X-9400统一内存，DGX Base OS定制操作系统。
NVIDIA宣称，搭配128GB内存，GB10可以运行最高2000亿参数的AI大模型，或者最高700亿参数的微调模型。
两台DGX Spark可以通过ConnectX-7总线互连，大模型参数最高可达4050亿。

垚读音【yáo】，形容山高，多用于人名。
壵读音为【zhuàng】,古同「壮」。

【新智元导读】刚刚，豆包·图像创作模型Seedream 4.0同时登顶「文生图」和「图像编辑」两项榜单！相比Nano Banana，Seedream 4.0在文生图的清晰度和美感上优势较为明显；在图像编辑上则难分伯仲，仅小幅领先。
https://aigcarena.com/?scene=T2I

shimmy     The 5MB Alternative to Ollama
# Install from crates.io (Linux, macOS, Windows)
cargo install shimmy

# Or download pre-built binary (Windows only)
curl -L https://github.com/Michael-A-Kuykendall/shimmy/releases/latest/download/shimmy.exe

《Foundations ofLarge Language Models》PDF已经整理好，见评论区
是由东北大学自然语言处理实验室的肖桐教授与朱靖波教授共同编写，是面向大语言模型领域的入门读物，适合希望掌握大模型基础知识的读者。
改书是由东北大学自然语言处理实验室的肖桐教授与朱靖波教授共同编写，是面向大语言模型领域的入门读物，适合希望掌握大模型基础知识的读者。

https://www.producthunt.com/shoutouts?ref=header_nav

flowith https://flowith.io/blank
https://www.k2think.ai/

https://cobalt.tools/ 音视频下载

实现实时搜索功能，传统JS需25行代码，而htmx仅需5行HTML：
```
<input type="text" id="search-input" 
       hx-get="/search" 
       hx-trigger="keyup delay:300ms changed" 
       hx-target="#results">
<div id="results"></div>
```
核心优势在于"后端逻辑即交互逻辑"：通过hx-post提交表单，Django视图处理后返回HTML片段，hx-target指定更新区域，实现无刷新体验。

sim.ai Sim作为一个专注于AI工作流构建的开源平台
https://elsaspeak.com/en/

Autogen 是 Microsoft 推出的编程框架，旨在支持代理 AI 的开发。通过这个框架，开发人员可以轻松创建复杂的代理系统并进行智能交互。
主要特点：
支持创建自主或协作工作的多代理 AI 应用程序。
框架支持 Python 和.NET，提供灵活的开发环境。
提供 AutoGen Studio 和 AutoGen Bench，用于无代码 GUI 构建和代理性能评估。
项目地址：
https://github.com/microsoft/autogen

motion vue 动画库

https://github.com/cline/cline
https://docs.cline.bot/getting-started/installing-cline

https://github.com/codexu/note-gen  A cross-platform Markdown AI note-taking software. 

indexedDB

一行代码利用Fetch API的配置选项，明确告诉浏览器这是一个需要CORS支持的请求。mode: 'cors'指示浏览器发送带有CORS头部的请求，而credentials: 'include'则允许请求携带凭证信息（如cookies）。当然，服务器端仍需进行适当配置以响应这类请求：
```
const response = await fetch('https://api.example.com/data', { mode: 'cors', credentials: 'include' });
```

湖南省长沙市岳麓区银盆岭街道潇湘北路三段1250号图鸿大厦2607
谢乐 李新林

YISHION - 东莞市以纯集团有限公司
yishion.com
http://116.6.135.227/

成立信息：湖南锦诺名品网络科技有限公司成立于2025年06月10日，位于湖南省长沙市，主要经营技术服务、互联网销售等业务。 
商业模式：锦诺名品采用“名品平价”的策略，所有商品均为国内知名品牌，旨在通过源头供应链直供来降低价格，吸引消费者。 

https://github.com/mermaid-js/mermaid-live-editor

https://longcat.chat/ 美团ai
 React Native， beeshell 2.0
 https://tech.meituan.com/2019/09/26/open-source-react-native-component-library-beeshell.html
 
2023年12月1日，美团旗下自营零售品牌“美团买菜”升级为全新品牌“小象超市”。
“小象超市”坚持美团自营零售模式，通过在社区设立的集存储、分拣、配送为一体的便民服务站，为社区居民提供生鲜食杂日用及配送服务，定位为“30分钟快送超市”。
▲美团买菜升级为“小象超市”，启用新品牌Logo。
品牌升级后，小象超市丰富多彩的商品已经达到线下大型超市水平。目前，小象超市已在北京、上海、深圳、广州、武汉、苏州等多个城市上线。在美团“零售+科技”战略聚焦下，小象超市将通过更稳定、更便利、更丰富的商品零售，帮大家吃得更好，生活更好。

https://huggingface.co/LLM360/K2-Think
https://huggingface.co/meituan-longcat/LongCat-Flash-Chat

滴滴青桔🍊＾ω＾
https://m.bilibili.com/opus/904672369138729017 Windows11轻松设置（1.11版）
https://www.osssr.com/17697.html
https://github.com/Mercury13/unicodia

https://techcommunity.microsoft.com/blog/azure-ai-foundry-blog/announcing-live-interpreter-api---now-in-public-preview/4453649

AutoAgent is a Fully-Automated and highly Self-Developing framework that enables users to create and deploy LLM agents through Natural Language Alone.

git clone https://github.com/HKUDS/AutoAgent.git
cd AutoAgent
pip install -e .

WPS正在推出EXcel的Power Query功能（简介PQ）。


Nuitka-GUI the Python 3 Binary machine code Compiler and Node Inspector 

https://github.com/juancarlospaco/nuitka-gui

https://github.com/ZuodaoTech/everyone-can-use-english
https://enjoy.bot/courses/96acfb9c-f034-4e19-bfb5-b1c079f4095d
青苔科技
https://cdmosstech.com
青苔科技
成立于2022年的我们，是一家位于中国四川省成都市的创新型游戏开发公司。自成立以来，我们致力于打造独特、引人入胜的游戏体验，旨在通过创新的游戏设计和

https://github.com/wenyuanw/quick-prompt
Quick Prompt ✨ 提示词管理与快捷输入浏览器插件 | Browser extension for prompt management and quick input ✨ 

前几天，Adobe设计布道师Howard Pinsky在推特上发布了一条看似轻描淡写的动态：
“Nano Banana（Gemini 2.5 Flash Image）将在今年9月融入 Photoshop！”
这条推文一经发布，立刻引爆了设计圈和 AI 圈的讨论。

rizz是 Z 世代俚语，意思是“魅力”。因此，今年夏天，一个被称为“Rizzbot”的垃圾话机器人在互联

https://github.com/The-Pocket/PocketFlow/tree/main/cookbook/pocketflow-chat

Microsoft 的 pg 数据库插件 forvscode chat with this database

爱编程的涵涵 嘉立创EDA

SD Maid 2/SE is Android's most thorough cleaning tool. 

Chatbox（https://chatboxai.app/）是由开发者@benn 开发的一个流行的大语言模型全平台聊天客户端。2025年1月28日
Cherry Studio是一款功能强大的国产开源AI工具，支持本地部署、知识库管理、多模型聚合和联网搜索等特性。2025年3月2日

深圳市纵维立方科技有限公司（以下简称：纵维立方）成立于2015年，如今公司已成为消费级3D打印机领域的领军企业之一。 2023年，纵维立方的年营收超过10亿元，且营收和利润均保持增长，成为少数几家达到十亿级规模的厂商之一。 经过多年的发展，纵维立方现已形成了两大产品品牌：Anycubic Kobra系列和Anycubic Photon系列。网页相关图像
Anycubic Kobra S1 Combo 是一款出色的机器，其配置选项、功能特性，最重要的是价格，都使其成为无论是初学者还是有经验的 3D 打印用户的理想选择
https://www.makeronline.com/zh/

https://labs.google/lll/en/experiments/tiny-lesson

8月28日，擅长编码且速度极快的Grok Code Fast 1发布。
两周多后，主打速度的Grok 4 Fast也上线了。
值得一提的是，Grok 4 Imagine在图像生成速度上，也是一把好手。

i18n-cli

TinyEditor
一个基于 Quill 2.0 的富文本编辑器，在 Quill 基础上扩展了丰富的模块和格式，功能强大、开箱即用。
https://github.com/opentiny/tiny-editor/tree/main/packages/projects
https://github.com/slab/quill/
https://quilljs.com/playground/snow

你可以通过以下两种方法查看红米手机的进程：
通过手机自带的应用程序管理功能查看
打开手机的“设置”应用；
导航到“应用程序”或“应用程序和通知”选项；
查看列出的所有应用程序，找到正在运行的应用程序，它们通常会显示为“运行中”或“活动”。
使用USB线连接手机和电脑，并通过adb命令进入手机查看
使用USB线将手机与电脑连接；
打开电脑上的命令提示符（cmd）或终端；
导航到adb所在的文件夹；
输入命令  adb shell  进入手机shell；
输入  top -m 10 -s cpu  命令查看CPU占用情况；
输入  dumpsys meminfo   查看特定应用的内存使用情况。
综上所述，你可以根据自身需求选择合适的方法来查看红米手机的进程。

https://juejin.cn/post/7549131152999383075  玩转Flex布局：看完这篇你也是布局高手！  

https://github.com/topics/awesome
https://github.com/awesomedata/awesome-public-datasets

Git.io
URL shortening service is no longer accepting new links.
© 2025 GitHub Inc. All rights reserved. • Terms of Service • Privacy • Security

https://golf-lang.com/examples.html

https://juejin.cn/post/7535361978270433334
由于Claude Code暂不支持大陆用户使用，需要使用**ClaudeYY**， 获取 API Key然后连接到镜像服务器：
bash 体验AI代码助手 代码解读复制代码# 设置镜像服务器地址

export ANTHROPIC_BASE_URL=https://www.claudeyy.com/api
# 验证配置
echo $ANTHROPIC_BASE_URL

在启动的时候，执行claude -c，可以继续上次对话
  执行claude -r，可以选择历史对话继续。如果你已经打开了某个对话，你也可以输入 /resume 来切换到其他会话
  
  https://graphique-design-lab.nocode.host
  
https://github.com/dyad-sh/dyad



https://github.com/mlabonne/llm-course

https://github.com/dbeaver/cloudbeaver
https://demo.cloudbeaver.io/#/

https://juejin.cn/post/7544924903046643753
作为一个程序员，每天都在和各种登录机制打交道，但你真的搞清楚 Token、Session、Cookie、JWT、OAuth2 这五兄弟的关系了吗？

用 requestAnimationFrame 分批丝滑渲染海量数据，如果你的数据量真的超级大（比如 10W+），即使分批渲染也会占用大量 DOM，这时可以考虑 虚拟滚动（只渲染可视区域内的元素）。
核心思路：
只渲染可见区域的数据，滚动时动态替换内容。
使用 IntersectionObserver 或监听 scroll 事件计算可视范围。

```
// 老
const xhr = new XMLHttpRequest();
xhr.open('GET', '/api', false);   // 同步
xhr.send();

// 新
const res = await fetch('/api');
const data = await res.json();

作者：404星球的猫
链接：https://juejin.cn/post/7547207040532971559

const ext = fileName.slice(fileName.lastIndexOf('.'));
jQuery —— “百万网站”历史债
现状：BuiltWith 统计全球 Top 1M 网站 78% 仍引用，但新立项使用率 < 6%（State of JS 2024）
替代：

DOM：querySelector + addEventListener
Ajax：fetch
动画：Web Animations API / CSS transition
链式：可选链 ?. + 空值合并 ??

```

自动化邮件发送的终极秘籍：Python库smtplib与email的完整玩法

https://link.juejin.cn/?target=https%3A%2F%2Fwww.indietools.work

https://github.com/dataease/SQLBot

https://github.com/tekaratzas/RustGPT

https://github.com/EricLBuehler/mistral.rs

https://marble.worldlabs.ai/

https://github.com/eythaann/Seelen-UI
The Fully Customizable Desktop Environment for Windows 10/11.Seelen UI requires the WebView runtime to be installed. On Windows 11, it comes pre-installed with the system. However, on Windows 10, the WebView runtime is included with the setup.exe installer. Seelen-UI 采用Rust + TypeScript + Tauri的组合，在性能、安全性与轻量化之间找到了完美平衡。

https://github.com/GUI-for-Cores/GUI.for.Clash A GUI program developed by vue3 + wails.
https://gui-for-cores.github.io/guide/gfc/how-to-use

FlClash下载地址：https://github.com/chen08209/FlClash/releases
FlClash使用教程：https://clash.download/flclash

刚刚，谷歌和OpenAI同时拿下ICPC金牌，尤其OpenAI还是满分！
ICPC全称国际大学生程序设计竞赛，是世界上最负盛名的编程竞赛之一！

ICPC
https://icpc.global
ICPC Global
The International Collegiate Programming Contest is an algorithmic programming contest for college students. Teams of three, representing their university, ...

好的，这里有一份按照字母顺序排列的常见职业英文单词列表，并附上了中文翻译。

为了方便您查阅，我将它们分成了几个大类。

A - C

· Accountant - 会计师
· Actor / Actress - 男演员 / 女演员
· Architect - 建筑师
· Artist - 艺术家
· Astronaut - 宇航员
· Athlete - 运动员
· Baker - 面包师
· Banker - 银行家
· Barber - 理发师（男性）
· Bartender - 调酒师
· Biologist - 生物学家
· Builder - 建筑工人
· Businessperson - 商人/企业家
· Butcher - 肉贩
· Carpenter - 木匠
· Cashier - 收银员
· Chef - 主厨
· Chemist - 化学家；（英）药剂师
· Cleaner - 清洁工
· Clerk - 职员，办事员
· Coach - 教练
· Computer Programmer - 计算机程序员
· Cook - 厨师
· Counselor - 顾问，咨询师

D - L

· Dancer - 舞蹈家
· Dentist - 牙医
· Designer - 设计师
· Detective - 侦探
· Doctor - 医生
· Driver - 司机
· Economist - 经济学家
· Editor - 编辑
· Electrician - 电工
· Engineer - 工程师
· Farmer - 农民
· Firefighter - 消防员
· Fisherman - 渔民
· Florist - 花商
· Journalist - 记者
· Judge - 法官
· Lawyer - 律师
· Librarian - 图书管理员
· Lifeguard - 救生员

M - R

· Manager - 经理
· Mechanic - 机械师
· Model - 模特
· Musician - 音乐家
· Nurse - 护士
· Nutritionist - 营养师
· Officer - 官员，警察
· Painter - 画家；油漆匠
· Pharmacist - （美）药剂师
· Photographer - 摄影师
· Pilot - 飞行员
· Plumber - 水管工
· Police Officer - 警察
· Politician - 政治家
· Professor - 教授
· Psychologist - 心理学家
· Receptionist - 接待员
· Reporter - 记者
· Scientist - 科学家

S - Z

· Sailor - 水手
· Salesperson - 销售员
· Secretary - 秘书
· Singer - 歌手
· Soldier - 士兵
· Surgeon - 外科医生
· Teacher - 教师
· Technician - 技术员
· Translator - 翻译
· Veterinarian - 兽医
· Waiter / Waitress - 男服务员 / 女服务员
· Writer - 作家

几点说明：

1. 以“-er/-or/-ist/-ian”结尾：许多职业名词由动词或名词加上这些后缀构成，例如：teach（教）→ teacher（教师），science（科学）→ scientist（科学家）。
2. 性别中性化趋势：现代英语中，越来越多地使用性别中性的词汇。例如，用 Police Officer 代替 Policeman/Policewoman，用 Flight Attendant 代替 Steward/Stewardess，用 Actor 统称男女演员也变得很常见。
3. 此列表仅为部分常见职业：世界上有成千上万种职业，这个列表只涵盖了一部分最常用和最常见的。

希望这个列表对您有帮助！
https://opal.withgoogle.com/landing/

https://clash.download/flclash
https://qiaomimi.cloud/#/dashboard ficlash免费试用，速度超快 Singapore

蝉不懂禅，妄称知了；
吏唯知利，怎言公仆？

蝉不懂禅，妄称知了。
猿未解缘，枉号悟空。

TCL首发SQD-Mini LED技术打破色域十年僵局！

专用版模型GPT-5-Codex，vscode插件https://openai.com/index/introducing-upgrades-to-codex/
npm i -g @openai/codex 
https://chatgpt.com/codex

jdk 25 Features
    470: 	PEM Encodings of Cryptographic Objects (Preview)
    502: 	Stable Values (Preview)
    503: 	Remove the 32-bit x86 Port
    505: 	Structured Concurrency (Fifth Preview)
    506: 	Scoped Values
    507: 	Primitive Types in Patterns, instanceof, and switch (Third Preview)
    508: 	Vector API (Tenth Incubator)
    509: 	JFR CPU-Time Profiling (Experimental)
    510: 	Key Derivation Function API
    511: 	Module Import Declarations
    512: 	Compact Source Files and Instance Main Methods
    513: 	Flexible Constructor Bodies
    514: 	Ahead-of-Time Command-Line Ergonomics
    515: 	Ahead-of-Time Method Profiling
    518: 	JFR Cooperative Sampling
    519: 	Compact Object Headers
    520: 	JFR Method Timing & Tracing
    521: 	Generational Shenandoah

Typer is a library for building CLI applications that users will love using and developers will love creating. Based on Python type hints.
Documentation: https://typer.tiangolo.com
Source Code: https://github.com/fastapi/typer
Typer is FastAPI's little sibling, it's the FastAPI of CLIs.

受够了黑白分明的终端输出吗？Rich 能让你的终端变得五彩斑斓。
from rich import print

user = {'name': 'omega', 'id': 'invalid'}
# Rich 能漂亮地打印数据结构，还支持 emoji
print(f":wave: Rich 打印\nuser: {user}")

https://rich.readthedocs.io/en/stable/introduction.html#requirements

Marimo：下一代 Python 交互式笔记本
pip install marimo && marimo tutorial intro
https://marimo.app/?slug=55kclj

ServBay

GraalVM不单单是个JDK，它是个高性能的多语言虚拟机。它最牛的地方在于能把Java代码直接编译成一个本地可执行文件，压根儿不需要JVM就能跑。
javac HelloWorld.java

native-image HelloWorld

The last command generates an executable file named helloworld in the current working directory
因此Java应用启动能快得像C++，内存占用能小得像Go。

SQL Playground  sqlplayground.app/

https://github.com/mit-han-lab/tinyml

https://elementary.io/zh_CN/

1. 体验与观察：安装系统，使用原生应用，阅读 HIG。
2. 技术选型：了解 Vala、GTK、Meson、Flatpak 这个技术组合。
3. 模仿与实践：按照官方指南，创建一个最简单的 elementary 风格应用。
4. 深度源码分析：选择一个你感兴趣的原生应用，阅读其源码，理解其架构和实现细节。
5. 参与贡献：提交 PR，融入社区，获得最直接的反馈。

https://www.w10privacy.de/english-home/instructions-1/
 CleanMem –内存释放利器
Razer Cortex 是雷蛇出的一款免费游戏优化工具，它的核心功能就是在你玩游戏时，把其他不必要的后台进程都暂停掉，腾出更多资源给游戏本身。
Driver Booster–驱动自动更新神器

https://github.com/GUI-for-Cores/GUI.for.Clash
A GUI program developed by vue3 + wails.

Nuclear
是一款开源免费的音乐流媒体播放器，能整合YouTube、SoundCloud等平台的免费音乐资源，支持跨平台（Windows/Mac/Linux）使用。它采用TypeScript和Rust开发，提供智能搜索、歌词显示、离线下载等功能，完全无广告且无需会员。最新版本可通过GitHub或包管理器（如Chocolatey/Brew）安装
https://enjoy.bot/chapters/

【新智元导读】DeepSeek-R1荣登Nature封面，成为史上首个经严格同行评议的大模型。年仅18岁的天才少年涂津豪作为作者之一，以实习生身份参与其中，他的故事从高中生到Nature作者，堪称励志传奇。

微信和支付宝在7月20日和21日相继宣布全面开放绑定Visa、Mastercard等主流境外卡，并升级相关的服务。

https://gemini.google.com/app/22726c00fb9c1437 

https://github.com/ashishpatel26/500-AI-Agents-Projects

OpenMind推出全球首个“AI原生”开源机器人系统OM1，该系统基于MIT协议在GitHub开源，致力于构建跨平台机器人开发统一框架。OM1支持四足、双足、人形及轮式等多种硬件，兼容AMD64与ARM64架构，原生适配宇树Unitree G1、Go2及优必选等机器人产品。通过集成SLAM、LiDAR与Nav2路径规划技术，该系统可实现复杂环境下的自主导航与行为仿真，并提供了基于React的OM1 Avatar交互界面，显著降低开发门槛与实验风险。

jdk25新特性
// 无需显式类声明
void main() {
    IO.println("Hello, JDK 25!"); // java.lang.IO 自动导入
    String name = IO.readln("Enter your name: ");
    IO.println("Hello, " + name);
}

import module java.base; // 导入模块的所有公共类
// 可直接使用 List、ArrayList 等，无需单独导入

uiverse
Open-Source UI elements made with CSS or Tailwind

中国移动eSIM预约页面上线，支持新入网、换卡、携号转网等业务

https://github.com/SubtitleEdit/subtitleedit/releases

https://github.com/puruvj/macos-web
https://winxp.vercel.app/

https://github.com/topics/web-os
https://github.com/bytebot-ai/bytebot
Bytebot is a self-hosted AI desktop agent that automates computer tasks through natural language commands, operating within a containerized Linux desktop environment.

github.com/CodebuffAI/codebuff

drawdb https://www.drawdb.app/editor
https://csrankings.org/

https://3d.hunyuan.tencent.com/
访问官方文档：https://github.com/rough-stuff/rough
在线演示：https://roughjs.com/demos/
扩展库：rough-viz（图表）、rough-notation（标注）

BillionMail gives you open-source MailServer,  email marketing — fully self-hosted, dev-friendly, and free from monthly fees. https://demo.billionmail.com/send 

https://github.com/GrindGold/CppGuide?tab=readme-ov-file
「C/C++学习+面试指南」一份涵盖大部分 C++ 程序员所需要掌握的知识。入门、进阶、深入、校招、社招，准备 C++ 学习& 面试，首选 CppGuide！

TencentOS tiny的内核确实是非常非常小巧，最少资源占用为RAM 0.6KB，ROM 1.8 KB。这是他们团队自主研发的RTOS，源码非常简单易懂，源码作者以非常清晰的逻辑实现了整个内核。

everything
基础搜索：
直接输入文件名或关键词（如 "document"）。
支持通配符：*（任意字符）、?（单个字符）。示例："*.jpg" 搜索所有 JPG 图片，"file?.txt" 搜索 file1.txt、fileA.txt 等。
布尔运算符：
AND（默认）："word excel" 搜索同时包含 "word" 和 "excel" 的文件。
OR："word | excel" 搜索包含任一关键词的文件。
NOT："word !excel" 搜索包含 "word" 但不含 "excel" 的文件。
路径与属性过滤：
"path:C:\Users\"：限定搜索路径。
"ext:pdf"：按扩展名过滤（如 PDF、MP4）。
"dm:2023-01-01"：按修改日期过滤（dm= 修改日期，dc= 创建日期）。
"size:>10MB"：按文件大小过滤（支持 KB、MB、GB）。

上海交大大模型教程

zread.ai

https://gist.github.com/dekomote/4069446

https://labs.google.com/mixboard/welcome

容器运行时的格局也在悄然生变。containerd 和 runc 成为了 Kubernetes 官方推荐的运行时，它们更轻、更专注，

https://github.com/mcp/github/github-mcp-server

https://developer.chrome.com/blog/chrome-devtools-mcp?hl=zh-cn

https://lynx.invisible-island.net/lynx_help/Lynx_users_guide.html

头条搜  夏思凝美图分享

https://www.vue-plugins.org/

Durable.co — 30秒网站生成器
GitHub：github.com/hydropix/TranslateBookWithLLM

1. 设计目标：MQTT为物联网设备通信优化，WebSocket用于浏览器与服务器通信。
2. 通信模型：MQTT是发布/订阅模式，WebSocket是直接的客户端-服务器模式。
3. 应用场景：MQTT适用于物联网设备与云平台，WebSocket适用于实时Web应用。
4. 协议特性：MQTT轻量、支持QoS，WebSocket实时性强、易于实现。
https://presenton.ai/outline

德国四人组“重新定义Git”，靠图形化客户端年入10亿元！
​fournova团队因受够命令行Git的晦涩难用，开发出图形化工具Tower——将rebase、cherry-pick等复杂操作转化为拖拽点击，全球超300万开发者付费使用，年收入破10亿元！

visual web editor for professionals
Pinegrow lets you work faster with HTML, CSS, SASS, Bootstrap, Tailwind CSS, GSAP Interactions, WordPress and WooCommerce.

Pinegrow is available as a desktop app, as an online service and as a self-hosted WordPress plugin.

Adobe 软件的最佳替代品 原文在这里
Evince (Adobe Acrobat Reader) 一个“支持多种文档格式的文档查看器”，可以查看 PDF，还支持各种漫画书格式
Pixlr (Adobe Photoshop) 一个强大的图像编辑工具
Inkscape (Adobe Illustrator) 一个专业的矢量图形编辑器
Pinegrow Web Editor (Adobe Dreamweaver) 一个可视化编辑制作 HTML 网站
Scribus (Adobe InDesign) 一个开源电子杂志制作软件
Webflow (Adobe Muse) 一款可以帮助用户不用编码就可以快速创建网站的谷歌浏览器插件。
Tupi (Adobe Animate) 一款可以创建 HTML5 动画的工具。
Black Magic Fusion (Adobe After Effects) 一款先进的合成软件，广泛应用于视觉特效、广电影视设计以及 3D 动画设计等领域。

$* 或 $@	除了 $0 外的所有位置参数
$#	不包括 $0 在内的位置参数的个数
$#	返回参数个数
$*	返回所有参数
$$	脚本运行的当前进程 ID 号
$!	后台运行的最后一个进程的 ID 号
$@	返回所有参数（与 $* 相同）
$-	返回 Shell 使用的当前选项，与 set 命令功能相同。
$?	函数返回值（或上一个命令的退出状态）

如果希望执行某个命令，但又不希望在屏幕上显示输出结果，那么可以将输出重定向到 /dev/null：
如果希望屏蔽 stdout 和 stderr，可以这样写：
$ command > /dev/null 2>&1

Any2Text：免费转换音频和视频为文本的AI工具

https://sindresorhus.com/hyperduck

Windows 11正在推出一项名为“Windows AI Labs”的新计划，旨在让用户提前体验微软的AI功能。

高通骁龙峰会今日正式开幕，新一代旗舰芯片骁龙8 Elite Gen 5终于揭开面纱，性能数据直接让整个安卓圈集体破防”！这颗芯片采用台积电3nm工艺，CPU设计彻底放飞”——2颗4.61GHz超大核+6颗3.63GHz大核，全大核架构堪称性能核弹”，多核性能暴增50%。

git clone https://github.com/opactorai/Claudable.git
cd Claudable

# 2. 安装依赖（自动配置环境）
npm install

# 3. 启动开发服务器
npm run dev

虚拟机网络配置
桥接模式：将虚拟机桥接到物理机的网卡，需要与物理机在同一网段，适合需要与局域网内其他设备通信的场景。
2
NAT模式：虚拟机通过宿主机的NAT功能访问网络，适合需要访问外部网络但不需要被局域网内其他设备直接访问的场景。
2
主机模式：虚拟机与宿主机通信，与外部网络隔离，适合内部测试和开发。
2

使用nmcli命令连接Wi-Fi
登录Linux系统。
使用nmcli命令扫描周围的WiFi热点：nmcli device wifi list。
连接到指定的WiFi热点：nmcli device wifi connect <wifi name> password <wifi passwd>。
使用ip addr show wlan0查看WiFi的IP地址。
使用ping命令测试网络连通性。

https://cr.console.aliyun.com/

code --add-mcp '{"name":"chrome-devtools","command":"npx","args":["chrome-devtools-mcp@latest"]}'

gemini mcp add -s user chrome-devtools npx chrome-devtools-mcp@latest

npm install -g @iflow-ai/iflow-cli
https://github.com/Snawoot/nth-dump/releases/tag/v1.5.0

https://ifconfig.co/ ifconfig.me ipinfo.io

maji 水 muzuli sawa好👌

1).woo码物语编程语言是为广大[码人]创建的一款不用编译的动态解释型脚本语言，一个解释器，安装及其简单。 2).编码方式类似php，很多全局函数;例如:_json_encode({1,2}),不同的是全局函数前面都有下划线，一是防止和用户局部变量重名，二是用编辑器使用更加方便，输入下划线就弹出所有全局函数，方便输入 查找。 3).woo语言是多线程模式的，相对与php的多进程模式占用内存更小，且支持多线程，使用_run('file.woo',params...)来开启一个线程。 4).woo语言的包管理器是wpm（code wooyri package mamager）和python的pip，php的conposer一个用途，wpm install oshine/bitmap即可安装对于的包和插件。 5.)语法兼容lua脚本90%,会简单的lua脚本就可以编写。 6.)面试go程序员的时候，应该被问到chan（通道），装逼必须得了解的，当然了，woo语言也集成了这类装B的功能：

-- test.woo中的内容为:
_chan_put(false,{1,2,3,4,5,6,_ARGS[1]})

-- main.woo中的内容为:
_run('test.woo', "线程1")
_out('主线程loop，取线程提交值', _chan_get(true), "\n") 

-- 执行:woo main.woo
7.)集成了许多好用的库（开源）

woo_proxy | sockets5代理 （下面的在开发中。。。） Murphy web框架 英文翻译库 还有更多不一一列举... 开发插件不限制语言，官方提供了插件开发的go语言库：插件开发库，当然了其他语言也可以开发woo插件，和插件通信使用udp和tcp均可

8.)支持sockets（udp/tcp）/websockets/http服务

https://lite-xl.com/playground/

Notepad4 (Notepad2⨯2, Notepad2++) is a light-weight Scintilla based text editor for Windows with syntax highlighting, code folding, auto-completion and API list for many programming languages and documents, it's based on (rewritten in modern C++) Florian's Notepad2 and XhmikosR's Notepad2-mod. matepath is a file browser plugin and based on (rewritten in modern C++) Florian's metapath.

https://www.wolfram.com/wolframscript/
WolframScript 让 Wolfram 语言代码可以在任何终端运行，无需依赖系统中是否拥有 Wolfram 内核。 
例

在本地 Wolfram 引擎计算 Wolfram 语言代码 2+2：

$ wolframscript -code 2+2
            4

在 Wolfram Cloud 计算 Wolfram 语言代码 2+2：

$ wolframscript -cloud -code 2+2
            4

脚本文件

创建文件，以便在本地执行 Wolfram 语言代码：
file.wls

#!/usr/bin/env wolframscript
            Print[2+2]

$ ./file.wls
            4

创建文件，以便在 Wolfram Cloud 上执行 Wolfram 语言代码：
file.wls

#!/usr/bin/env wolframscript -cloud
                Print[2+2]

$ ./file.wls
            4

创建使用命令行参数的文件：
file.wls

#!/usr/bin/env wolframscript
                 Print[ToExpression[$ScriptCommandLine[[2]]]^2]

$ ./file.wls 5
            25

创建给出一个函数的文件，其参数来自命令行：
file.wls

#!/usr/bin/env wolframscript -function -signature City City
                Print[GeoDistance[#1, #2]]&

$ ./file.wls "Champaign, IL" "Oxford, England"
            Quantity[4010.4812837526256, Miles]
            
https://resources.wolframcloud.com/PromptRepository/
https://resources.wolframcloud.com/FunctionRepository

https://www.oceanengine.com/ 
ec2-13-213-4-54.ap-southeast-1.compute.amazonaws.com

https://github.com/WolframResearch/vscode-wolfram

安卓 访问官方内测入口：https://wj.toutiao.com/q/366529/8g9c9q6D/#/，填写问卷获取资格后下载安装包 需完成问卷验证，部分机型可能不兼容

OpenAI Sora 2 与 Google Veo 3 的主要区别是什么？
Sora 2 强调物理真实感与音视频同步，让人物、物体和场景的表现更自然，并配以电影级的音效。相比之下，Google Veo 3 更注重画面质感和精准的口型同步，但生成的视频片段更短。

虽然年仅18岁，但特朗普的长孙女 凯·特朗普（Kai Trump）已经成为特朗普家族第三代中的代表人物。她是职业高尔夫球手，开创了自己的品牌，坐拥数百万粉丝，还开始在政坛崭露头角。那么，这个女孩会不会成为特朗普的继承人呢？

凯·特朗普 2007年5月12日出生在纽约市，是小唐纳德·特朗普（Donald Trump Jr.）与前妻凡妮莎·海登·特朗普（Vanessa Haydon Trump）的第一个孩子。
但伊万卡的女儿， 阿拉贝拉·库什纳（Arabella Kushner）已成为第三代中的另一位潜力股。

Poe.com 最好的人工智能，尽在一处。访问 ChatGPT、Claude 3.5 Sonnet、Gemini、一流的图像、视频和音频生成模型，以及数百万个用户创建的机器人。

https://github.com/mco2004/qwen-tts

Excel解释 transformer

https://motionbgs.com/gaze-of-the-blade
Live Wallpaper for PC: Windows 11/10/7 & Mac
4K Download (21.5Mb)
3840x2160 mp4 video file

GitHub - winfunc/opcode: A powerful GUI app and Toolkit for Claude Code ...
🌟 Overview opcode is a powerful desktop application that transforms how you interact with Claude Code. Built with Tauri 2, it provides a beautiful GUI for …

mdserve是一个使用 Rust 开发的 Markdown 预览服务器，他只有一个可以执行文件，不需要额外的依赖。

单一可执行文件，无需额外依赖

通过 WebSocket 通信机制实现实时预览

内置主题选择器

GFM 和 Mermaid 图表支持

daisyUI adds a set of customizable color names to Tailwind CSS and these new colors use CSS variables for the values. 

24岁的Carina Hong称作一个「推动数学超级智能的人」。
创立Axiom Math并担任CEO，Axiom Math核心员工中大多数来自Meta

重命名默认分支： git branch -M main

全球支付要变天了：PayPal 联手微信支付，加密支付全面接入
PayPal 正式宣布推出 PayPal World，携手 微信支付、印度 UPI、拉美 Mercado Pago，实现跨境钱包互联。
以后老外来中国旅游，用 PayPal 扫微信二维码就能付钱；
国人出国，也能直接用微信扫 PayPal 的二维码，真正做到“跨境支付=本地支付”。首批合作预计在今年秋季上线。
更值得注意的是，PayPal 已经把 加密支付 纳入主流：

https://github.com/dduan/tre

https://md.doocs.org/

Remove-Item（别名：rm, del）删除文件或目录：
# 删除文件
Remove-Item "file.txt"

# 强制删除目录及其内容
Remove-Item "C:\temp" -Recurse -Force

# 使用量排序
Get-Process | Sort-Object WorkingSet -Descending

# 获取占用CPU最多的进程
Get-Process | Sort-Object CPU -Descending | Select-Object -First 10

# 以管理员权限启动PowerShell
Start-Process powershell -Verb RunAs

# 获取正在运行的服务
Get-Service | Where-Object {$_.Status -eq "Running"}

Start-Service -Name Spooler
Stop-Service -Name Spooler
Restart-Service -Name Spooler

Get-ComputerInfo

Get-WmiObject用来获取WMI信息，这个功能超级强大：
# 获取系统信息
Get-WmiObject -Class Win32_ComputerSystem

# 获取CPU信息
Get-WmiObject -Class Win32_Processor

# 获取内存信息
Get-WmiObject -Class Win32_PhysicalMemory

# 获取磁盘信息
Get-WmiObject -Class Win32_LogicalDisk

Select-String（类似grep，这个很重要）在文本中搜索：
# 在文件中搜索文本
Select-String -Path "*.log" -Pattern "error"

# 搜索多个文件
Get-ChildItem *.txt | Select-String "keyword"

Where-Object（别名：where, ?）用来过滤对象：
# 获取大于100MB的文件
Get-ChildItem | Where-Object {$_.Length -gt 100MB}

# 获取最近7天修改的文件
Get-ChildItem | Where-Object {$_.LastWriteTime -gt (Get-Date).AddDays(-7)}

#查看端口是否被占用
netstat -ano|findstr :80

场景一：批量重命名文件
假设你要把一个目录下所有的.txt文件重命名为.bak文件。
CMD的做法：
for %f in(*.txt) do ren "%f" "%~nf.bak"
PowerShell的做法：
Get-ChildItem *.txt | Rename-Item -NewName {$_.Name -replace '\.txt$','.bak'}
PowerShell的版本更直观，而且支持正则表达式，处理复杂的重命名规则更方便。

场景四：批量管理服务器
这是PowerShell最强大的功能之一。假设你需要在多台服务器上执行相同的操作：
# 定义服务器列表
$servers = "Server01", "Server02", "Server03"

# 批量获取服务器信息
Invoke-Command -ComputerName $servers -ScriptBlock {
Get-WmiObject -Class Win32_LogicalDisk |
Where-Object {$_.DriveType -eq 3} |
Select-Object DeviceID, Size, FreeSpace
}

# 批量重启服务
Invoke-Command -ComputerName $servers -ScriptBlock {
Restart-Service -Name Spooler
}

# 将结果保存到文件
Get-Process | Export-Csv "processes.csv"

# 将结果转换为HTML
Get-Service | ConvertTo-Html | Out-File "services.html"

问题1：脚本执行被阻止
这是最常见的问题，解决方法是修改执行策略：
# 临时允许执行脚本
Set-ExecutionPolicy -ExecutionPolicy Bypass -Scope Process

# 永久修改（需要管理员权限）
Set-ExecutionPolicy RemoteSigned

问题2：中文乱码
有时候PowerShell显示中文会出现乱码，可以这样解决：
# 设置控制台编码
[Console]::OutputEncoding = [System.Text.Encoding]::UTF8

# 或者在脚本开头添加
$OutputEncoding = [Console]::OutputEncoding = [Text.UTF8Encoding]::UTF8
问题3：远程连接失败
使用PowerShell远程管理时可能遇到连接问题：
# 启用PowerShell远程管理
Enable-PSRemoting -Force

# 添加信任的主机
Set-Item WSMan:\localhost\Client\TrustedHosts -Value "192.168.1.*"

# 测试远程连接
Test-WSMan -ComputerName "RemoteServer"
问题4：内存占用过高
PowerShell有时会占用较多内存，特别是处理大量数据时：
# 强制垃圾回收
[System.GC]::Collect

# 使用流式处理代替一次性加载
Get-Content "largefile.txt" -ReadCount 1000 | ForEach-Object {
# 处理每1000行
}

https://learn.microsoft.com/zh-cn/powershell/
在线教程
PowerShell Gallery有很多实用的脚本和模块，可以学习别人的代码。
地址：https://www.powershellgallery.com/


Python一行代码解决方案：
```
import pandas as pd
# 一行代码合并多个相同结构的Excel文件
combined_df = pd.concat([pd.read_excel(f)forfin['销售部.xlsx', '市场部.xlsx', '财务部.xlsx']])

#进阶用法（带自动文件检测）：
import glob

# 自动读取文件夹内所有Excel文件并合并
all_data = pd.concat([pd.read_excel(f) for f in glob.glob('月度报表/*.xlsx')])
```


​git reset -hard HEAD~1  撤销最近的提交
git reset  取消暂存的修改
git checkout - [file-path]   丟弃工作目录中的修改
​git merge [branch-name]   合并指定的分支到当前分支
git rebase [branch-name]   把当前分支的修改基于指定分支重新应用(变基）
git tag [tag-name]  在当前提交上创建一个tag标签

高德扫街榜

https://github.com/fathyb/carbonyl
 是由 Fathy Boundjadj 用 Rust 语言开发的终端浏览器。它基于 Chromium，支持几乎所有的 Web API，包括 WebGL、WebGPU、音频和视频播放、动画等。
 
找到了一个开源免费的 BT 种子下载客户端：PikaTorrent。
​提供简洁易用的下载管理界面，并且支持边下载边播放视频，最重要是全平台支持。
​GitHub：github-com/G-Ray/pikatorrent
https://github.com/eclaire-labs/eclaire
Local-first, open-source AI assistant for your data — unify tasks, notes, docs, photos, and bookmarks. Private, self-hosted, and extensible via APIs.

netplwiz 打开微软官方的用户管理工具。取消密码要求。
：计算机\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Winlogon
3. 在右边一大堆值里面，找到这三个宝贝：
AutoAdminLogon：双击它，把数值数据从0改成1。
DefaultUserName：双击它，确认数值数据就是你的用户名。
DefaultPassword：如果这个项不存在，你就右键空白处 -> 新建 -> 字符串值，然后把它命名为 DefaultPassword。双击它，在数值数据里填上你的开机密码。
做完这些，关闭注册表编辑器，重启电脑同样生效。

https://github.com/asweigart/pyautogui

https://openwrite.cn/

https://github.com/OpenListTeam/OpenList

链接: https://pan.baidu.com/s/1SGP_CsPOg_LIGXXOy9iMcg 提取码: yh26 复制这段内容后打开百度网盘手机App，操作更方便哦

https://tresjs.org/
marimo

IT之家 10 月 4 日消息， 当地时间本月 2 日正式发布了 ZGX Nano G1n AI Station。这款三维 150×150×51 (mm) 的超紧凑桌面工作站专为 AI 开发而构建，配备了 FP4 稀疏 AI 算力达 1 pTOPS  GB10 Grace Blackwell 超级芯片。
ZGX Nano G1n 板载 128GB LPDDR5x 统一内存，拥有 273GB/s 的内存带宽，配备 1TB 或 4TB 容量的 TCG Opal 加密 M.2 NVMe 固态硬盘。

wxWidgets/Phoenix
0xJacky/nginx-ui

https://froala.com/wysiwyg-editor/demo/

微软即将推出含广告的免费Xbox云游戏服务

https://github.com/craigbarnes/dte
A small, configurable terminal text editor 

微软CTO称将启动自研芯片
https://github.com/simular-ai/Agent-S

https://fmhy.net/ https://fmhy.net/ai

https://www.text-to-speech.online/ 我们使用强大的微软 AI 语音库来合成接近真人声音的独特阅读音频。

copyweb.ai

Vert.x-Web is a set of building blocks for building web applications with Vert.x. Think of it as a Swiss Army Knife for building modern, scalable, web apps.
Vert.x是一个基于Java的开源框架，用于构建异步、响应式的应用程序，它在某些方面有着独特的优势，但相对来说没有特别“火”，主要原因包括学习曲线较陡、生态系统规模有限、应用场景相对特定，以及社区活跃度问题。

谷歌加入CUA战场，发布Gemini 2.5 Computer Use：AI直接操作浏览器
PythonAnywhere is a server-side, no-gui sort of environment, so we currently don't support any sort of graphics (unless you count web apps). So things like turtle and pygame are out. Which is a shame because graphics are so great, particularly for the student's first few experiences with programming. You may want to check out https://trinket.io as an alternative for the first few classes.

https://chat.openai.com/cdn-cgi/trace

https://googlechromeai2025.devpost.com/ Google Chrome Built-in AI Challenge 2025

https://github.com/shadowsocks/shadowsocks-windows/releases/tag/4.4.1.0    A C# port of shadowsocks

go.dev  https://pkg.go.dev/net/http
To run the tour locally, you'll need to first install Go and then run:
    go install golang.org/x/website/tour@latest
    
This will place a tour binary in your GOPATH's bin directory. When you run the tour program, it will open a web browser displaying your local version of the tour.

coleifer/sqlite-web
Web-based SQLite database browser written in Python

https://github.com/SagerNet/sing-geosite/releases/download/20250916122507/geosite.db

Console Importer｜通过控制台快速引入第三方库
chromewebstore.google.com/detail/cons…
我们只需要在控制台中输入$i('dayjs')，然后再输入 dayjs 的方法即可。

UI 组件库：像 shadcn/ui、daisyUI、flowbite 等，几乎全是基于 tailwindcss 打造。
框架模版：Next.js、Nuxt、Remix、Astro 的官方或社区 starter 里，大多数开箱即配好 tailwindcss。
文档和教程：tailwindcss 的学习资料、视频课程、最佳实践文章，数量远超 unocss。

https://edgeone.ai/zh/register?s_url=https://console.tencentcloud.com/edgeone/pages

linux内核代码阅读工具总结：
１、vi+ctags
2、sourceinsight
3、lxr（在线）
4、eclipse
5、vscode

https://www.figure.ai/ The future of home help is here
Figure 03 is a general purpose humanoid robot for every day.

https://github.com/CapSoftware/Cap
Cap is the open source alternative to Loom. Lightweight, powerful, and cross-platform. Record and share securely in seconds with custom S3 bucket support. Connect your own domain.

正在努力扭转艰难处境的老牌芯片厂英特尔，周四展示了即将亮相的新一代先进制程PC芯片，开始向苹果、高通、AMD、台积电等竞品发起反击。
公司发布的照片显示，今年3月履新的CEO陈立武站在亚利桑那工厂门口，捧着一块代号为Panther Lake的新一代酷睿处理器晶圆。这是首款采用英特尔18A工艺（18埃米，即1.8纳米）的芯片。

https://github.com/GrapesJS/grapesjs
用GrapesJS非常简单，只需几行代码就能创建一个基础编辑器：
<div id="gjs"></div>

<script type="text/javascript">
  var editor = grapesjs.init({
    container: '#gjs',
    components: '<div class="txt-red">Hello world!</div>',
    style: '.txt-red{color: red}',
  });
</script>


惠普Z2 Mini G1a迷你工作站在京东上架，“AMD锐龙AI Max+ PRO 395处理器 + 128GB RAM + 2TB SSD + AMD Radeon 8060S显卡”版本定价21999元，支持按需定制。

Olib 是一款体积不到 50MB 的绿色软件，将“找书→下载→管理→阅读”的全流程需求集成一体——对常看电子书、又厌烦网页端广告多/速度慢的 Windows 用户来说，它是目前最省心、零成本的实用选择之一，如果想下载体验，可自行搜索软件名或去GitHub开源地址，Python编写。https://github.com/shiyi-0x7f/o-lib 

https://geminicli.com/extensions/

https://system76.com/laptops/oryp13/configure

Nuitka 把Python源代码翻译成 C 代码，再交给 C 编译器生成可执行文件或扩展模块。它的目标不是彻底改变 Python，而是尽量保持兼容性，同时减少运行时开销。可以看成是 CPython 的“加速器/打包器”的合体。


[Windows] 搞机工具箱 v11.0.0
一款利用ADB(安卓调试桥）来控制手机的玩机工具。
由于ADB的权限shell介于用户与超级用户(Root)之间，因此本工具可在不Root的情况下实现一些手机自带设置中不具有的功能。

10月9日，蚂蚁集团发布万亿参数的通用语言模型Ling-1T。除了Ling-1T这款非思考大模型，蚂蚁百灵团队还在训练万亿参数级的深度思考大模型Ring-1T，已在9月30日开源了preview版。//ling.tbox.cn/

https://github.com/openpanel-dev/openpanel 为什么我决定从宝塔换到 OpenPanel？

FydeOS for PC
通用版本，支持各类 PC 设备，提供全面的硬件兼容性，让你轻松将 FydeOS 带入日常工作环境。

拔掉网线，关闭Wi-Fi，让电脑彻底“失联”。这一步千万别省，不然后面全白搭。
在Windows 11登录界面，同时按下Shift+F10，调出命令提示符窗口
输入这串代码（一个字都不能错）：
reg add HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\OOBE /v BypassNRO /t REG_DWORD /d 1 /f
回车执行后，再输入重启命令：
shutdown /r /t 0
电脑重启后，奇迹出现了——直接跳过Microsoft账户登录，让你创建本地账户！

ruancang.net   qijishow.com Fosshub是一个提供完全免费开源电脑软件的良心网站 rjsos.com软件SOS是一个常见软件pojie激活教程集合   0daydown.com msdn.itellyou.cn

OpenAI宣布推出类似 Anthropic 的 Artifacts 的应用Canvas，并称「这是一种使用ChatGPT写作和编程的新方式」。

https://mall.bilibili.com/neul-next/detailuniversal/detail.html?from=detailspage&isMerchant=1&itemsId=11190494&jumpLinkType=0&module_name=Android_tt_url&noTitleBar=1&page=detailuniversal_detail&share_mid=489127461&share_token=17993414-be30-4d37-82be-6c9b3659003b&tt_from=copy_link&utm_campaign=client_share&utm_medium=toutiao_android&utm_source=copy_link#noReffer=true

github.com/spieglt/FlyingCarpet
Cross-platform AirDrop. File transfer between Android, iOS, Linux, macOS, and Windows over ad hoc WiFi. No network infrastructure required, just two devices with WiFi chips (and optionally Bluetooth) in close range.

https://github.com/hoffstadt/DearPyGui
带了超全功能演示：
python -m dearpygui.demo
下面这段代码，堪称经典入门模板：
import dearpygui.dearpygui as dpg

def save_callback():
    print("Save Clicked")

dpg.create_context()
dpg.create_viewport()
dpg.setup_dearpygui()

with dpg.window(label="Example Window"):
    dpg.add_text("Hello world")
    dpg.add_button(label="Save", callback=save_callback)
    dpg.add_input_text(label="string")
    dpg.add_slider_float(label="float")

dpg.show_viewport()
dpg.start_dearpygui()
dpg.destroy_context()
不到十行，你就能跑出一个带按钮、滑块、输入框的窗口。
——DearPyGui基于C++和 GPU 渲染，性能吊打传统的 Tkinter、PyQt。简单来说，它给 Python 加了“火箭推进器”，让你写界面像写脚本一样爽！

让我们用timeit来实际解答上面的问题：
# 测试在列表中查找元素
python -m timeit "'needle' in ['needle']*1000"

# 测试在集合中查找元素
python -m timeit "'needle' in set(['needle']*1000"
集合（set）的查找速度会远超列表（list）

python -i命令允许你在脚本运行结束后，立即进入交互模式（REPL），并且保留脚本中所有加载的变量和状态。
python -i my_script.py

pydoc str
这个命令会立即在你的终端中显示**str类型的所有方法及其详细解释**。它比在浏览器中搜索更快，信息更直接。
 搭建本地文档 Web 服务器：
python -m pydoc -p 1234

python -X importtime是一个不为人知的调试标志（flag），它能精确地测量并报告每个被导入模块的加载耗时。
你可以直接对一个 Python 脚本文件进行反汇编：
python -m dis my_script.py

```
# 1. 创建虚拟环境
python -m venv myenv

# 2. 激活虚拟环境（Linux/macOS）
source myenv/bin/activate

# 3. 激活虚拟环境（Windows）
myenv\Scripts\activate.bat
```

kimi ok computer

Python库eel

https://www.classcentral.com/subject/ai

近日，零刻GTR9 Pro迷你AI工作站发布，价格12999元，是最便宜的迷你AI工作站之一。

https://jitword.com/doc

https://uiverse.io/
The Largest Library of Open-Source UI

https://github.com/proxifly/free-proxy-list

https://github.com/RamonUnch/AltSnap

https://www.phonevalidator.com/  检测实体手机号。

https://github.com/jingyaogong/minimind

一个现代化的网络安全练习和竞赛平台 - CyberPoC

WinOptimizer
awesome-llm-apps

https://platform.openai.com/agent-builder
https://github.com/a-boy/Windows-12-Concept

https://github.com/Open-Dev-Society/OpenStock

GitHub 链接：https://github.com/karpathy/nanochat
与 Karpathy 之前发布的 nanoGPT 仓库（只覆盖了预训练阶段）不同，nanochat 是一个从零开始实现的、极简但完整的 ChatGPT 克隆版训练 / 推理全流程项目，所有内容都集中在一个依赖极少、结构干净的代码库中。

https://github.com/iflow-ai/iflow-cli/blob/main/README_CN.md

运行 npm install -g @iflow-ai/iflow-cli 来安装 iFlow CLI
运行 iflow 来启动 iFlow CLI
npm uninstall -g @iflow-ai/iflow-cli

https://github.com/hangwin/mcp-chrome/blob/master/README_zh.md

https://codepen.io/Po-Ti/pen/ogbGXzN
https://codepen.io/ChetasLua/pen/EaPvqVo
https://aistudio.google.com/apps/drive/1IsiTJr3znRJXuoA7wwSqg9IN9op_Zuj-?resourceKey=&showPreview=true

CheekyBastard55
•
4h ago
•
Edited 3h ago
You don't have to trust him, you're free to try it out yourself on AI Studio.

Prompt: "Design and create a web os like mac os full functional features from text editor , to dile manager to paint to video editor and all important mac os pre bundled software Use whatever libraries to get this done but make sure I can paste it all into a single HTML file and open it in Chrome.make it interesting and highly detail , shows details that no one expected go full creative and full beauty in one code block"

Edit: I got this result, don't think it's the top model on the A/B test from Gemini 3.0 Pro.

https://codepen.io/Po-Ti/pen/ogbGXzN
https://github.com/okibcn/nano-for-windows/tree/master/src

https://github.com/ashishpatel26/500-AI-Agents-Projects

IT之家 10 月 14 日消息，英伟达当地时间 13 日宣布，基于 GB10 Grace Blackwell 超级芯片的 DGX Spark 桌面 AI 超算将于本月 15 日正式发售，第一方 FE 版本售 3999 美元（IT之家注：现汇率约合 28533 元人民币）。
DGX Spark 采用的 GB10 芯片包含由 10 个 Arm Cortex-X925 核心与 10 个 Arm Cortex-A725 核心构成的 20 核 CPU，GPU 部分则拥有 6144 个 CUDA 核心，配备 256-Bit 128GB 的 LPDDR5x-9400 统一内存，FE 版本提供 4TB 固态硬盘。

谷歌Gemini 3杀疯了！内测碾压GPT-5，前端开发直接被“降维打击”，10月22日正式发布

https://github.com/jwangkun/Prompt-Tools 

https://github.com/sansan0/TrendRadar

Explore over 70 expert-lead sessions, live demos, and hands-on workshops. Join us October 27–29 in Washington, D.C., including NVIDIA CEO Jensen Huang’s keynote on October 28. Register Now 

NVIDIA Base Command
The operating system of the NVIDIA DGX data center.

作为新一代计算机，DGX Spark 以小巧的桌面机形态提供 1 PFLOP AI 性能和 128GB 统一内存，使开发者能够在本地运行最高 2000 亿参数的 AI 模型推理以及对 700 亿参数的模型进行微调。此外，开发者还可通过 DGX Spark 在本地创建 AI 智能体和运行高级软件堆栈。
DGX Spark 将整个 NVIDIA AI 平台——包括 GPU、CPU、网络、CUDA® 库及 NVIDIA AI 软件堆栈——整合为一台可置于实验室或办公室的小型系统，该系统拥有加速代理式 AI 与物理 AI 开发所需的强大性能。凭借空前的性能与 NVIDIA 庞大的生态系统，DGX Spark 将台式机转变为 AI 开发平台。

DGX Spark 系统搭载 NVIDIA GB10 Grace Blackwell 超级芯片、NVIDIA ConnectX®-7 200Gb/s 网卡及 NVIDIA NVLink™-C2C 技术，可提供最高 1 PFLOP 的 AI 性能。其带宽是第五代 PCIe 的 5 倍，并配备 128GB CPU-GPU 一致性内存。

预装的 NVIDIA AI 软件堆栈让开发者能够开箱即用，立即投入 AI 项目开发。通过 DGX Spark，开发者可访问包括模型、库及 NVIDIA NIM 微服务在内的 NVIDIA AI 生态系统工具，建立本地工作流，例如定制 Black Forest Labs 的 Flux.1 模型优化图像生成、使用 NVIDIA Cosmos Reason 视觉语言模型创建视觉搜索与摘要智能体，或使用针对 DGX Spark 优化的 Qwen3 开发 AI 聊天机器人等。

为庆祝 DGX Spark 全球交付，黄仁勋赴德克萨斯州星舰基地，亲手将首批 DGX Spark 之一交付给 SpaceX 首席工程师埃隆·马斯克。此次交接承载着对超级计算机起源的致敬——早在 2016 年，马斯克所在团队就曾从黄仁勋手中接收了首台 NVIDIA DGX™-1 超级计算机。

其他首批收到 DGX Spark 的企业有 Anaconda、Cadence、ComfyUI、Docker、谷歌、 Hugging Face、JetBrains、LM Studio、Meta、微软、Ollama 和 Roboflow，他们正在针对 DGX Spark 对各自工具、软件和模型进行测试、验证和优化。

## windows special folders
 windows special folders     http://www.nirsoft.net/utils/special_folders_view.html
 shell:sendto shell:appsfolder shell:fonts

%UserProfile% - Opens your user's profile C:\Users\{username}
%AppData%\Microsoft\Windows\Start Menu\Programs\Startup - Opens Windows 10 Startup location for program shortcuts

chrome://apps/

## curl ipinfo.io
C:\Users\PC>curl ipinfo.io
{
  "ip": "120.227.43.82",
  "city": "Shanghai",
  "region": "Shanghai",
  "country": "CN",
  "loc": "31.2222,121.4581",
  "org": "AS56047 China Mobile communications corporation",
  "postal": "200000",
  "timezone": "Asia/Shanghai",
  "readme": "https://ipinfo.io/missingauth"
}
PS C:\Users\PC> curl ipinfo.io
{
  "ip": "163.223.40.32",
  "city": "Kobe",
  "region": "Hyōgo",
  "country": "JP",
  "loc": "34.6913,135.1830",
  "org": "AS32135 SAKURA LTD.",
  "postal": "761-4146",
  "timezone": "Asia/Tokyo",
  "readme": "https://ipinfo.io/missingauth"
}
PS C:\Users\PC> curl ipinfo.io/205.134.180.164
{
  "ip": "205.134.180.164",
  "hostname": "teon-customer.ai.net",
  "city": "Washington",
  "region": "District of Columbia",
  "country": "US",
  "loc": "38.8951,-77.0364",
  "org": "AS6405 American Information Network",
  "postal": "20004",
  "timezone": "America/New_York",
  "readme": "https://ipinfo.io/missingauth"
}

## 加密解密文件或文件夹
C:\Users\PC\cipher>cipher /e 1.txt
C:\Users\PC\cipher>cipher /d 1.txt

C:\Users\PC\cipher>cipher /e /s:.
C:\Users\PC\cipher>cipher /d /s:.

AdaCpp | C++ Online AI+IDE

## 2025-07-10
Win+Alt+R 录屏
appwiz.cpl 控制面板\程序\程序和功能
route print 查看路由表
arp -a 显示ARP缓存表
netsh wlan show profiles key=clear name="Xiaomi_8866"
copy file1.txt+file2.txt merged.txt 合并文件
xcopy src dest /E /H /C
runas /user:Administrator notepad
for /L %i in (1,1,8) do ping 8.8.8.%i
https://learn.microsoft.com/en-us/windows-server/administration/windows-commands/for
wmic product get name,version > software.csv
reg query HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Run 查看启动项

C:\Windows\System32\MRT.exe
Windows 恶意软件删除工具 (MSRT) 可帮助 Windows 计算机免受流行恶意软件攻击。 MSRT 可发现和删除威胁，并还原这些威胁所做的更改。 MSRT 通常每月作为 Windows 更新的一部分发布，或作为独立的工具在此处提供以供下载。

C:\Windows\System32\msra.exe 远程协助
mstsc.exe 远程桌面连接
C:\Windows\System32\perfmon.msc perfmon.exe 性能监视器
psr.exe 步骤记录器
resmon.exe 资源监视器
Ribbons.scr 屏幕保护程序Ribbons
C:\Windows\System32\sudo.exe
"C:\Windows\System32\WF.msc" 防火墙配置
C:\Users\PC>where cl
D:\Program Files\Microsoft Visual Studio\2022\Community\VC\Tools\MSVC\14.44.35207\bin\Hostx64\x64\cl.exe

---
1 公顷 = 15 亩 = 10000 ㎡

1 亩 = 666.67 ㎡

1 平方公里 = 1500 亩 = 100 公顷

---
1 英寸 ≈ 2.54 cm（"英二半"记得牢）

1 米 = 3 尺 ≈ 39.37 英寸

1 英里 ≈ 1.6 公里

1 海里 ≈ 1.85 公里

1 尺 ≈ 0.33 米
---

摄氏度（℃） ↔ 华氏度（℉）

℉ = ℃ × 1.8 + 32

℃ = (℉ − 32) ÷ 1.8

摄氏度（℃） ↔ 开尔文（K）

K = ℃ + 273.15

℃ = K − 273.15
---


Clairad
C语言混乱代码大赛（IOCCC）经典代码解析

https://img.shields.io/badge/build-passing-brightgreen.svg

https://dustinbrett.com/

https://cachyos.org/download/

sniffnet

free PlanetVPN https://freevpnplanet.com/

https://tresjs.org/ create awesome 3D experiences with Vue    npm install @tresjs/core three

https://liquipedia.net/starcraft/China_Seasons_League/Xiamen

https://github.com/neutralinojs/neutralinojs
https://codezri.org/docs/buildzri/integrate

Win10系统 默认以管理员权限运行所有程序
一、 win+R, 输入 regedit 运行注册表
二、 在注册表地址栏输入 HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Policies\System
选中左边System文件夹，在右侧找到 EnableLUA，将值从1改为0
三、 重启系统即可，然后就可以看到管理员就变成了你现操作的系统。执行的各种程序也都是直接以管理员权限执行

PS C:\Windows\System32> iex "& {$(irm get.scoop.sh)} -RunAsAdmin"
Initializing...
Downloading...
Creating shim...
Adding ~\scoop\shims to your path.
Scoop was installed successfully!
Type 'scoop help' for instructions.
PS C:\Windows\System32> scoop help
PS C:\> which scoop
C:/Users/PC/scoop/shims/scoop

https://www.raidrive.com/zh-hans/pricing 列出了当前的网盘服务

## 7:12 2025/8/20
https://www.google.com/maps/place/中国湖南省长沙市/@28.1763401,112.6949161,10z/data=!3m1!4b1!4m15!1m8!3m7!1s0x3420ba186987384d:0xcc21910be4ae2ce5!2z5Lit5Zu95rmW5Y2X55yB!3b1!8m2!3d28.1142216!4d112.9833341!16zL20vMDE2Njl0!3m5!1s0x342735f39e1c64c5:0xb1e5bb9ca1f1a680!8m2!3d28.2277799!4d112.93886!16zL20vMDFjdzZs?hl=zh-CN&entry=ttu&g_ep=EgoyMDI1MDgxNy4wIKXMDSoASAFQAw%3D%3D

https://www.mkdb.sh/ free hosted postgres, as simple asmkdir

ContourPlot[f,{x,Subscript[x, min],Subscript[x, max]},{y,Subscript[y, min],Subscript[y, max]}]
生成关于  x 和 y 的函数 f 的等高线图.

loofah  [ˈluːfə]  n.【植】丝瓜；丝瓜络
像这样列出常见的蔬菜水果的英语单词

当然可以！以下是一些常见蔬菜和水果的英语单词及其中文翻译：

### 蔬菜
1. Carrot [ˈkærət] - 胡萝卜
2. Tomato [təˈmeɪtoʊ] - 西红柿
3. Cucumber [ˈkjuːkʌmbər] - 黄瓜
4. Spinach [ˈspɪnɪtʃ] - 菠菜
5. Broccoli [ˈbrɑːkəli] - 西兰花
6. Potato [pəˈteɪtoʊ] - 土豆
7. Onion [ˈʌnjən] - 洋葱
8. Bell Pepper [bɛl ˈpɛpər] - 彩椒
9. Lettuce [ˈlɛtɪs] - 生菜
10. Cauliflower [ˈkɔːlɪfaʊər] - 花椰菜

### 水果
1. Apple [ˈæpl] - 苹果
2. Banana [bəˈnænə] - 香蕉
3. Orange [ˈɔːrɪndʒ] - 橙子
4. Grape [ɡreɪp] - 葡萄
5. Pineapple [ˈpaɪnæpl] - 菠萝
6. Strawberry [ˈstrɔːbəri] - 草莓
7. Mango [ˈmæŋɡoʊ] - 芒果
8. Watermelon [ˈwɔːtərˌmɛlən] - 西瓜
9. Peach [piːtʃ] - 桃子
10. Kiwi [ˈkiːwi] - 猕猴桃

希望这些词汇对你有帮助！如果你需要更多的信息或其他类型的词汇，请告诉我！
请列出更多的蔬菜和水果的英语单词，尽量全面，

当然可以！以下是一些常见的蔬菜和水果的英语单词，尽量涵盖全面，并注上音标：

### 蔬菜 (Vegetables)
1. Carrot - 胡萝卜 /ˈkærət/
2. Potato - 土豆 /pəˈteɪtoʊ/
3. Tomato - 西红柿 /təˈmeɪtoʊ/
4. Onion - 洋葱 /ˈʌnjən/
5. Garlic - 大蒜 /ˈɡɑːrlɪk/
6. Cucumber - 黄瓜 /ˈkjuːkʌmbər/
7. Lettuce - 生菜 /ˈlɛtɪs/
8. Spinach - 菠菜 /ˈspɪnɪtʃ/
9. Broccoli - 西兰花 /ˈbrɑːkəli/
10. Cauliflower - 花椰菜 /ˈkɔːlɪˌfaʊər/
11. Bell pepper - 彩椒 /ˈbɛl ˈpɛpər/
12. Zucchini - 西葫芦 /zuˈkiːni/
13. Eggplant - 茄子 /ˈɛɡplænt/
14. Peas - 豌豆 /piːz/
15. Celery - 芹菜 /ˈsɛləri/
16. Radish - 萝卜 /ˈrædɪʃ/
17. Beetroot - 甜菜 /ˈbiːtruːt/
18. Pumpkin - 南瓜 /ˈpʌmpkɪn/
19. Squash - 瓜类 /skwɔːʃ/
20. Asparagus - 芦笋 /əˈspærəɡəs/
21. Artichoke - 朝鲜蓟 /ˈɑːrtɪˌtʃoʊk/
22. Kale - 羽衣甘蓝 /keɪl/
23. Brussels sprouts - 球芽甘蓝 /ˈbrʌsəlz ˈsprɑʊts/
24. Chard - 瑞士甜菜 /tʃɑːrd/
25. Fennel - 茴香 /ˈfɛnəl/

### 水果 (Fruits)
1. Apple - 苹果 /ˈæpl/
2. Banana - 香蕉 /bəˈnænə/
3. Orange - 橙子 /ˈɔːrɪndʒ/
4. Grape - 葡萄 /ɡreɪp/
5. Strawberry - 草莓 /ˈstrɔːbɛri/
6. Blueberry - 蓝莓 /ˈbluːˌbɛri/
7. Raspberry - 覆盆子 /ˈræzˌbɛri/
8. Blackberry - 黑莓 /ˈblækˌbɛri/
9. Pineapple - 菠萝 /ˈpaɪnˌæpəl/
10. Mango - 芒果 /ˈmæŋɡoʊ/
11. Peach - 桃子 /piːtʃ/
12. Pear - 梨 /pɛr/
13. Cherry - 樱桃 /ˈtʃɛri/
14. Watermelon - 西瓜 /ˈwɔːtərˌmɛlən/
15. Cantaloupe - 哈密瓜 /ˈkæntəloʊp/
16. Honeydew - 蜜瓜 /ˈhʌnidjuː/
17. Kiwi - 猕猴桃 /ˈkiːwi/
18. Pomegranate - 石榴 /ˈpɑːmɪˌɡrænɪt/
19. Fig - 无花果 /fɪɡ/
20. Papaya - 木瓜 /pəˈpaɪə/
21. Coconut - 椰子 /ˈkoʊkənʌt/
22. Lemon - 柠檬 /ˈlɛmən/
23. Lime - 青柠 /laɪm/
24. Apricot - 杏子 /ˈeɪprɪˌkɑːt/
25. Guava - 番石榴 /ˈɡwɑːvə/

$a_1$

## 2025-08-21 09:06:15
tcb ai

user
summarize WIN32 api in C programming

codex
The Windows API (Win32 API) is a set of functions provided by Microsoft for interacting with the Windows operating
system. It allows developers to create applications that can manage windows, handle input, perform file operations, and
more. Here’s a concise summary of key aspects:

### Core Components

- Windows Management: Functions like CreateWindow, ShowWindow, and DestroyWindow for managing windows.
- Messages and Events: The WndProc function handles messages like WM_PAINT, WM_CLOSE, and WM_COMMAND.
- Graphics and Drawing: Use GDI functions like TextOut, Rectangle, and BitBlt for rendering graphics.
- File and I/O Operations: Functions like CreateFile, ReadFile, and WriteFile for file handling.
- Memory Management: Functions like GlobalAlloc, LocalAlloc, and VirtualAlloc for memory allocation.
- Process and Thread Management: Functions like CreateProcess, CreateThread, and WaitForSingleObject for managing
processes and threads.
- Registry and Configuration: Functions like RegOpenKey, RegSetValueEx, and RegQueryValueEx for accessing the Windows
Registry.
- Networking: Functions like WSAStartup, socket, and send for network communication.

### Common Patterns

- Message Loop: A loop that processes messages from the OS using GetMessage, TranslateMessage, and DispatchMessage.
- Event Handling: Implement a WndProc function to handle specific events like mouse clicks or key presses.
- Resource Management: Use handles (HWND, HINSTANCE, etc.) to manage resources like windows, files, and memory.

### Example Code
```
#include <windows.h>

LRESULT CALLBACK WndProc(HWND, UINT, WPARAM, LPARAM);

int WINAPI WinMain(HINSTANCE hInstance, HINSTANCE hPrevInstance, LPSTR lpCmdLine, int nCmdShow) {
    WNDCLASS wc = {0};
    wc.lpfnWndProc = WndProc;
    wc.hInstance = hInstance;
    wc.lpszClassName = "MyWindowClass";

    RegisterClass(&wc);

    HWND hwnd = CreateWindow("MyWindowClass", "Win32 Example", WS_OVERLAPPEDWINDOW, CW_USEDEFAULT, CW_USEDEFAULT, 640,
480, NULL, NULL, hInstance, NULL);

    ShowWindow(hwnd, nCmdShow);

    MSG msg;
    while (GetMessage(&msg, NULL, 0, 0)) {
        TranslateMessage(&msg);
        DispatchMessage(&msg);
    }

    return msg.wParam;
}

LRESULT CALLBACK WndProc(HWND hwnd, UINT msg, WPARAM wParam, LPARAM lParam) {
    switch (msg) {
        case WM_PAINT:
            PAINTSTRUCT ps;
            HDC hdc = BeginPaint(hwnd, &ps);
            TextOut(hdc, 10, 10, "Hello, Win32!", 12);
            EndPaint(hwnd, &ps);
            break;
        case WM_CLOSE:
            DestroyWindow(hwnd);
            break;
        case WM_DESTROY:
            PostQuitMessage(0);
            break;
        default:
            return DefWindowProc(hwnd, msg, wParam, lParam);
    }
    return 0;
}
```

### Key Points

- Platform-Specific: The Win32 API is specific to Windows and not portable to other operating systems.
- Low-Level Control: Provides fine-grained control over Windows features but can be complex to use.
- Wide Range of Capabilities: From simple window creation to advanced networking and system management.

	EditPlus 不过有网络的大神分享了最新的6.x版本的注册号。
	注册信息
	用户名：EditPlus
	注册码：WGJ8J-62UCJ-J6AGG-4A6GQ-26SSC

f(x)=a_0+∑_(n=1)^∞▒(a_n  cos⁡〖nπx/L〗+b_n  sin⁡〖nπx/L〗 )

https://github.com/max-niederman/ttyper ttyper is a terminal-based typing test built with Rust and Ratatui.

https://chromewebstore.google.com/detail/markdown-editor/ekdcaddpmiodcipjfmffhhefijpdckaf

## 2025-08-23 07:46:50
docker run -d -p 6080:6080 -e EMULATOR_DEVICE="Nexus 7" -e WEB_VNC=true --device /dev/kvm --name android-nexus7 budtmo/docker-android:emulator_14.0

Drawnix 是一款强大的开源白板工具（https://github.com/plait-board/drawnix），集成思维导图、流程图等功能。基于Plait 框架开发，支持插件扩展，提供自动保存、无限画布

docker run -d -p 6080:6080 -e EMULATOR_DEVICE="Samsung Galaxy S10" -e WEB_VNC=true --device /dev/kvm --name Android-GalaxyS10 budtmo/docker-android:emulator_14.0

OverType is a transparent textarea over rendered markdown.
Plain text simplicity, WYSIWYG beauty, zero complexity.

78KB TOTAL
•
ONE SCRIPT TAG
•
UNDERSTAND YOUR EDITOR

## 2025-08-25 17:28:55
https://overtype.dev/demo
A **lightweight** markdown editor with perfect WYSIWYG alignment.

## Features
- 🚀 Lightning fast performance
- 🎨 Theme support
- ⌨️ Keyboard shortcuts
- 📱 Mobile optimized

## 2025-08-29 09:36:05
https://github.com/ollama/ollama Developer(s)	Meta AI  Written in	Python

C:\Users\PC\AppData\Local\Programs\Ollama\lib\ollama\ggml-cuda.dll
C:\Users\PC\.ollama\models

'+−×÷<>=‹›«»⟮⟯•‣․ ‥ … ‧ ♪¬⁒'.charCodeAt(1)  8226• 183· 8231‧
Middle Dot · (U+00B7) &#183; &#xB7; &centerdot;
Bullet • (U+2022)
One Dot Leader ․ (U+2024)
Hyphenation Point ‧ (U+2027) &#8231; &#x2027;
Bullet Operator ∙ (U+2219)
Dot Operator ⋅ (U+22C5)
Z Notation Spot ⦁ (U+2981)

https://www.compart.com/en/unicode/category/Sm  List of Unicode Characters of Category “Math Symbol”
https://www.w3schools.com/charsets/ref_utf_math.asp

Dalvík is the main village of the Icelandic municipality of Dalvíkurbyggð. Its population is approximately 1,400. Dalvík. Town and Municipality. 达尔维克(Dalvik)是冰岛达尔维克市(Dalvikurbyggo)的主要村庄。该市人口约1400人。达尔维克。城镇和市镇

Android Open Source Project
https://source.android.com › docs › core › runtime
26 Aug 2024 — ART and Dalvik are compatible runtimes running DEX bytecode, so apps developed for Dalvik should work when running with ART.

Bolt.new is an AI-powered web development agent that allows you to prompt, run, edit, and deploy full-stack applications directly from your browser—no local setup required.
- Full-Stack in the Browser: Bolt.new integrates cutting-edge AI models with an in-browser development environment powered by StackBlitz’s WebContainers. This allows you to:

Install and run npm tools and libraries (like Vite, Next.js, and more)
Run Node.js servers
Interact with third-party APIs
Deploy to production from chat
Share your work via a URL

- AI with Environment Control:

https://stackblitz.com/ netlify.com

映山红
[yìng shān hóng]
na.azalea; Indian azalea
网络Azalea; Rhododendron simsii; Rhododendron simsii Planch.

agent-c
```
void init_agent(void) {
    strcpy(agent.messages[0].role, "system");
    strcpy(agent.messages[0].content, "You are an AI assistant with Napoleon Dynamite's personality. Say things like 'Gosh!', 'Sweet!', 'Idiot!', and be awkwardly enthusiastic. For multi-step tasks, chain commands with && (e.g., 'echo content > file.py && python3 file.py'). Use execute_command for shell tasks. Answer questions in Napoleon's quirky style.");
    agent.msg_count = 1;
}
```

elderscrollsonline.com/cn/home 《上古卷轴OL》  The Elder Scrolls

https://rendergit.com/github.com/qingtk/webbud?process=true

https://github.com/bgreenwell/doxx  A fast, terminal-native document viewer for Word files. View, search, and export .docx documents without leaving your command line.

https://win32.run/

https://github.com/FedericoBruzzone/tgt TUI for Telegram written in Rust 🦀
https://github.com/fdehau/tui-rs

https://github.com/FrameworkComputer/Framework-Laptop-16
Framework Laptop 16 (AMD Ryzen™ AI 300 Series)
Starting at $58,500

https://github.com/PixiEditor/PixiEditor

## 2025-09-01 18:35:32
99446192

https://www.tablesgenerator.com/text_tables

The generator / editor is quite flexible and allows to generate tables similar to the example shown below. As can be seen, multi-row and multi-column cells are supported.

+---------------------------------------+
|                Results                |
+-------------+-------------------------+
|             |        Contestant       |
| Competition +-------+--------+--------+
|             |  John | Andrea | Robert |
+-------------+-------+--------+--------+
| Swimming    |  1:30 |   2:05 |   1:15 |
+-------------+-------+--------+--------+
| Running     | 15:30 |  14:10 |  15:45 |
+-------------+-------+--------+--------+



不及物动词
绑定GitHub的二级域名需要进行以下几个步骤：

1. 在GitHub上创建仓库：首先，在GitHub上创建一个新的仓库。该仓库将用于托管您的网站源文件。

2. 创建一个gh-pages分支：在您的仓库内，创建一个名为”gh-pages”的分支。该分支将用于托管生成的静态网页。

3. 配置仓库的设置：在您的仓库内，点击”Settings”选项卡。滚动到”GitHub Pages”部分，并选择”gh-pages”分支作为源。

4. 设置域名：点击”Enforce HTTPS”按钮以启用HTTPS。然后，在”Custom domain”字段中输入您想要绑定的二级域名。

5. 配置DNS解析：接下来，您需要在您的域名注册商或DNS解析服务商处配置DNS记录。添加一个CNAME记录，将您的二级域名指向用户名.github.io。如果您希望启用HTTPS，还需要添加一个A记录，将您的二级域名指向GitHub的IP地址：185.199.108.153。

以上步骤完成后，您的二级域名将与GitHub仓库绑定。通过访问您的二级域名，您将能够看到您在仓库中的静态网页。请注意，生成的网页可能需要一些时间才能在您的二级域名上生效，因为DNS解析可能需要一些时间。如果遇到问题，您可以检查GitHub的文档和帮助中心，或向GitHub的支持团队寻求帮助。

https://blog-keeper.com/ 文捕 博客内容一键解析下载工具

combi
美 [ˈkɑmbi]
英 [ˈkɒmbi]
网络康贝；日本康贝；组合(combination)
kombi

http://www.aiinnovation.com.cn/#/trackDetail?id=153 兴智杯全国人工智能创新应用大赛 报名时段：2025-05-08~2025-09-15

https://micai.org/2025/  MICAI 2025
_The Mexican International Conference on Artificial Intelligence (MICAI_) is the leading AI event in Mexico, organized by the Mexican Society for Artificial ...

中国新一代迷彩服被称为“星空迷彩”，其花型和颜色都是全新设计的，共有林地、荒漠、丛林、城市和沙漠等五种配色，可以适应国内外的各种地形地貌的使用需求，迷彩服的主要作用是两方面，一是增加战士在实战环境中的伪装效果，二是要穿着实用，可以满部队日常训练和野外放置物品等需求，图中是新一代迷彩服臂章采用隐形图案。

军事丨解放军换装新一代迷彩服，臂章采用隐形图案，远近伪装超棒
据国内军事专家介绍，该新式迷彩服之所以有星空的效果，是因为引入更不易识别的微小数码格，较传统迷彩图案更细腻。在实战中，无论远视还是近视该迷彩服，都很容易看走眼，因为星空迷彩使人体与作战环境高度趋同，大大提高了隐蔽效果。

军事丨解放军换装新一代迷彩服，臂章采用隐形图案，远近伪装超棒
同时，与过去的老式迷彩服大面积色块相比，星空迷彩服的数码色块设计更加细碎，和自然环境能够更好地融合。为此，配套的头盔、战术手套、作战背心也都选用了同款颜色，就是军靴也做了改进。像沙漠款就搭配了绿色的靴子，丛林款是黑色的，这样在各自的地形里都协调、隐蔽一些。

军事丨解放军换装新一代迷彩服，臂章采用隐形图案，远近伪装超棒
新一代“星空迷彩”强调穿着新式迷彩服的官兵很难从外表上判别所属军种，从而回归到迷彩的最根本用途——伪装、隐藏，从远距离上看，不同颜色的斑点通过并置、交错，产生空间混色，能够形成大斑点的效果，可模拟森林、群山等背景群落的表面特征。
军事丨解放军换装新一代迷彩服，臂章采用隐形图案，远近伪装超棒
2020-05-31 08:02·武器看点
解放军换装最新一代迷彩服，臂章采用隐形图案：近日，解放军陆续公布最新一代迷彩作战服，新式迷彩服已在国庆阅兵中公开亮相。新式迷彩服将按照计划陆续配发全军部队，该迷彩服可以更好的适应国防和军队改革的要求，更好地满足部队的战备训练需要。

军事丨解放军换装新一代迷彩服，臂章采用隐形图案，远近伪装超棒
中国新一代迷彩服被称为“星空迷彩”，其花型和颜色都是全新设计的，共有林地、荒漠、丛林、城市和沙漠等五种配色，可以适应国内外的各种地形地貌的使用需求，迷彩服的主要作用是两方面，一是增加战士在实战环境中的伪装效果，二是要穿着实用，可以满部队日常训练和野外放置物品等需求，图中是新一代迷彩服臂章采用隐形图案。

军事丨解放军换装新一代迷彩服，臂章采用隐形图案，远近伪装超棒
据国内军事专家介绍，该新式迷彩服之所以有星空的效果，是因为引入更不易识别的微小数码格，较传统迷彩图案更细腻。在实战中，无论远视还是近视该迷彩服，都很容易看走眼，因为星空迷彩使人体与作战环境高度趋同，大大提高了隐蔽效果。

军事丨解放军换装新一代迷彩服，臂章采用隐形图案，远近伪装超棒
同时，与过去的老式迷彩服大面积色块相比，星空迷彩服的数码色块设计更加细碎，和自然环境能够更好地融合。为此，配套的头盔、战术手套、作战背心也都选用了同款颜色，就是军靴也做了改进。像沙漠款就搭配了绿色的靴子，丛林款是黑色的，这样在各自的地形里都协调、隐蔽一些。

军事丨解放军换装新一代迷彩服，臂章采用隐形图案，远近伪装超棒
新一代“星空迷彩”强调穿着新式迷彩服的官兵很难从外表上判别所属军种，从而回归到迷彩的最根本用途——伪装、隐藏，从远距离上看，不同颜色的斑点通过并置、交错，产生空间混色，能够形成大斑点的效果，可模拟森林、群山等背景群落的表面特征。

军事丨解放军换装新一代迷彩服，臂章采用隐形图案，远近伪装超棒
除了衣服之外，此次配发的头盔、战术手套、作战背心和军靴也都使用了相同的新式迷彩，一套装备下来不光是看着酷，是实实在在的提升了军人的隐蔽性。新的迷彩服是按照地形来划分的，也就是城市、林地、荒漠、从林和沙漠，不同的作战任务可以给士兵发放不同的迷彩服，便于整个作战方向所有人员的服装的统一，可以实现更好伪装自己的目的，也可以满足未来全军实现全疆域立体攻防作战的需求。

## 2025-09-09 11:34:06
du.hanyupinyin.cn 在线读拼音

FLTK - Fast Light Tool Kit - https://github.com/fltk/fltk - cross platform GUI development  www.fltk.org

charmap.exe

https://h5login.qqchess.qq.com/ 这里可以做一个AI接入的机器人，chrome extension，或者js脚本

C:\Windows\Tasks
计算机\HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Run

手心输入法，真的很好用，敲字快多了！

https://github.com/Raphire/Win11Debloat

warp.dev
Warp was founded in June 2020 by Zach Lloyd, former Principal Engineer at Google and interim CTO at TIME.[5] Lloyd and an early engineering team decided to develop Warp as a modern version of the command line terminal. Warp was built natively in Rust.[6]

In April 2023, Warp announced Warp AI, which integrated an OpenAI large language model chatbot into the terminal.[7] In June 2023, Warp introduced Warp Drive for collaboration on the command line

https://lmstudio.ai/ Download and run local models, Run gpt-oss, Qwen, Gemma, DeepSeek on your computer.

TF卡

https://labs.google/fx

DNS欺骗(DNS Spoofing)也被称为DNS缓存投毒(DNS Cache Poisoning)，是一种计算机安全攻击手段。攻击者通过利用DNS解析器软件的漏洞，向DNS解析器的缓存中注入虚假的DNS


https://utcp.io
UTCP is a lightweight, secure, and scalable standard that enables AI agents and applications to discover and call tools directly using their native protocols - ...

音乐魔石  https://yym4.com/search/宋小睿

duckdb  https://duckdb.org/docs/stable/
https://shell.duckdb.org/
npm install @duckdb/node-api
pip install duckdb

```
# Get the top-3 busiest train stations
import duckdb
duckdb.sql("""
    SELECT station, count(*) AS num_services
    FROM train_services
    GROUP BY ALL
    ORDER BY num_services DESC
    LIMIT 3;
    """)
```

质数 73939133

https://ninite.com/
Install and Update All Your Programs at Once
No toolbars. No clicking next. Just pick your apps and go.

https://www.gamespot.com.cn/en/downloads/19276

```
/* 手机（小于 600px） */
@media (max-width: 599px) {
    .container {
        flex-direction: column; /* 在手机上垂直排列 */
    }
    .item {
        width: 100%; /* 项目占据 100% 宽度 */
    }
}
```

使用Windows语音识别快捷键
Win + H：快速启动语音输入（推荐）
Ctrl + Win + S：切换语音识别模式
Alt + Shift + C：取消当前语音输入

cmd "C:\Program Files\EditPlus\editplus.exe" -d "E:\cloud\github\2293"

https://support.github.com/request

https://www.scmp.com/tech

https://www.doubao.com/thread/w280275885d67e7b2 豆包音乐生成 奋斗点亮希望 罗哈/豆包

## 2025-09-15 06:42:23
https://github.com/Mercury13/unicodia Encyclopedia of Unicode characters
OSSSR.COM  发现、学习、分享，与软件爱好者共同成长。

Koto City, Tokyo

Koto
https://koto.studio
Optimists building brand and digital for the most impactful companies of today and the founders defining tomorrow.

https://www.city.koto.lg.jp/
江东区役所
公司编号：6000020131083
东京都江东区东洋4-11-28 135-8383 电话号码：03-3647-9111（总机）

https://en.wikipedia.org › wiki › Koto_(instrument)
The koto (箏 or 琴) is a Japanese plucked half-tube zither instrument, and the national instrument of Japan.

https://en.wikipedia.org › wiki › Biwa
The biwa (Japanese: 琵琶) is a Japanese short-necked wooden lute traditionally used in narrative storytelling. The biwa is a plucked string instrument

feijipan.com

- http://aiwa.fun/ Your Super AI-Powered Virtual Assistant for WhatsApp
- aiwa.xyz  AI-Powered Hybrid Wallet

正确使用 IPv6 地址访问本机服务的方法：
需要在 IPv6 地址前后加 方括号 []，明确告诉浏览器这是一个 IPv6 地址，格式为：
[::1]
如果服务有特定端口（如 8080），需在括号后加端口号，例如：
[::1]:8080

https://chinese.yabla.com/
https://english.yabla.com/player_cdn.php?id=19672&tlang_id=zh_CN


Marimo Notebook
https://marimo.io https://marimo.app/
Transform data, train models, and run SQL queries with marimo — feels like an AI-native reactive notebook, stored as Git-friendly reproducible Python.

import marimo as mo

mo.md("# Welcome to [marimo](https://github.com/marimo-team/marimo)! 🌊🍃")


Documentation: https://typer.tiangolo.com
Source Code: https://github.com/fastapi/typer

Typer is a library for building CLI applications that users will love using and developers will love creating. Based on Python type hints.

It's also a command line tool to run scripts, automatically converting them to CLI applications.
Typer is FastAPI's little sibling, it's the FastAPI of CLIs.


https://github.com/Textualize/rich
Rich is a Python library for rich text and beautiful formatting in the terminal.
The Rich API makes it easy to add color and style to terminal output. Rich can also render pretty tables, progress bars, markdown, syntax highlighted source code, tracebacks, and more — out of the box.

Rich 是一个 Python 库，可以为您在终端中提供富文本和精美格式。
Rich 的 API 让在终端输出颜色和样式变得很简单。此外，Rich 还可以绘制漂亮的表格、进度条、markdown、语法高亮的源代码以及栈回溯信息（tracebacks）等——开箱即用。
https://calmcode.io/course/rich/introduction
c9.io 现在跳转到 https://aws.amazon.com/cn/cloud9
AWS Cloud9 不再面向新客户提供。AWS Cloud9 的现有客户可以继续照常使用该服务。了解详情

https://apod.nasa.gov/apod/archivepixFull.html Astronomy Picture of the Day Archive

许多开源项目提供了基于 noVNC 的在线演示环境。例如，DistroSea(https://distrosea.com/) 就允许用户直接在浏览器中“试驾”60 多种 Linux 发行版。DistroSea 免费开放，无需注册即可启动虚拟机。
OnWorks 在线 VPS 也是一个类似平台（参见 https://www.onworks.net/ ），提供免费云端工作站。OnWorks 支持多种 Linux（如 Edubuntu、Lubuntu、Ubuntu 22 等）以及在线 Windows/Mac 仿真环境，通过浏览器运行完整系统。官方介绍称：“OnWorks 是一个免费在线 VPS 服务商，提供免费的工作站环境……

https://humphd.github.io/browser-shell/

https://github.com/Gar-b-age/CookLikeHOC 像老乡鸡🐔那样做饭。
https://cooklikehoc.soilzhu.su/%E7%82%92%E8%8F%9C/%E5%AE%B6%E5%B8%B8%E5%B0%8F%E7%82%92

trayChrome https://github.com/cornradio/tray-chrome

https://www.zhiyuan-robot.com/

## 2025-09-23 08:42:40
https://csacademy.com/app/graph_editor/

https://js.cytoscape.org/ https://github.com/cytoscape/cytoscape.js   https://js.cytoscape.org/demos/circle-layout/

https://gojs.net/beta/samples/

https://demo.billionmail.com/smtp
Custom SMTP Relay
Bound Domain：
bimail.io
DNS records need updating
Server：
mail.bimail.io
Port：
587
Username：
bimail

https://developers.cloudflare.com/warp-client/get-started/linux/
https://docs.gtk.pw/contents/linux/clash-cli.html#%E9%85%8D%E7%BD%AE%E5%BC%80%E6%9C%BA%E5%90%AF%E5%8A%A8  在 Linux 通过 cli 使用 Clash

https://blog.elementary.io/updates-for-august-2025/

## 2025-09-27
Tower Git
https://www.git-tower.com
Over 100000 developers and designers are more productive with Tower - the most powerful Git client for Mac and Windows.

https://github.com/github/copilot-cli
npm install -g @github/copilot@latest

## 2025-10-01 16:20:10
alias
shcm -> Show-Command

Wolfram Notebook Assistant + LLM Kit $20/m trial

notepad4 matepath.exe

https://ossinsight.io/collections/text-editor/

https://ossinsight.io/collections/static-site-generator/trends/

https://platform.openai.com/docs/overview

https://developer.puter.com/tutorials/free-unlimited-openai-api/

https://mui.com/x/react-data-grid/demos/real-time-data/

https://www.chartjs.org/  https://github.com/chartjs/Chart.js

7960+ Live Wallpapers 4K - Free Animated Wallpapers for PC
Motion Backgrounds
https://motionbgs.com
Download Free 4K Live Wallpapers at MotionBGs ✓ 100% Free ✓ Best 7960+ Animated Wallpapers for PC on Windows 11/10 & Mobile.

https://md.doocs.org/

https://www.paypal.com/us/digital-wallet/paypal-world

https://github.com/artyom/mdserver  Basic http server rendering markdown files, Go
https://github.com/jfernandez/mdserve  Fast markdown preview server with live reload and theme support. Rust

https://www.byhand.ai/p/transformer-spreadsheet
https://www.byhand.ai/p/full-stack-transformer

https://threejs.org/editor/  tresjs

https://github.com/SagerNet/sing-box shanlian.app

https://trendshift.io/?trending-limit=100
https://github.com/ChatGPTNextWeb/NextChat  https://nextnext.chat/new-chat


Cap is the open source alternative to Loom. Lightweight, powerful, and cross-platform. Record and share securely in seconds with custom S3 bucket support. Connect your own domain. cap.so

python -m pydoc -p 8080 文档web服务
python -m dis my_script.py 反汇编

```
import dis
dis.dis("x = 2 + 2")

# 1. 创建虚拟环境
python -m venv myenv
# 2. 激活虚拟环境（Linux/macOS）
source myenv/bin/activate
#激活虚拟环境（Windows）
myenv\Scripts\activate.bat
```

https://wiki.python.org/moin/GuiProgramming

https://simonwillison.net/2025/Oct/13/nanochat/
The best ChatGPT that $100 can buy.  https://github.com/karpathy/nanochat


## 2025-10-22
zrok  ona gitpod.io
igraph https://github.com/igraph/igraph
https://igraph.org/c/html/latest/igraph-Tutorial.html

octahide
zed preview

Bonjour 国际音标：标准发音为 /bɔ̃.ʒuʁ/  “Bonsoir”（晚上好）Merci	谢谢	麦（mài）喝西（xi）	/mɛʁ.si/ Au revoir	再见	哦（ò）喝呜瓦（wǎ）	/o.ʁə.vwaʁ/

Chrome Music Lab
https://musiclab.chromeexperiments.com
·
Chrome Music Lab is a website that makes learning music more accessible through fun, hands-on experiments. What can it be used for? Many teachers have ...

### 值得学习的项目
AI SVG 动画生成器 一句话生成高质量矢量动画 https://www.svganimate.ai/zh/home https://www.svganimate.ai/en/gallery

ImageJ https://ij.imjoy.io/

## 2025-12-30
Opera News Hub
https://hub.opera.com
· Opera News Hub: Create. Share. Earn
Opera News utilizes an AI-technology-powered recommendation system to help creators distribute their content to a highly targeted audience. Our goal is to help ...

github多用户管理 You can use the `github [list | login | logout]` commands to manage your GitHub accounts. These commands are documented in the command-line usage or by running   
`git credential-manager github --help` .

Pinterest is an American social media service for publishing and discovery of information[5] in the form of digital pinboards.[6] This includes recipes, home, style, motivation, and inspiration on the Internet using image sharing.[7] Pinterest, Inc. was founded by Ben Silbermann, Paul Sciarra, and Evan Sharp,[8] and is headquartered in San Francisco.[9]

OpenStreetMap 是一个世界地图，由像您一样的人们所构筑，可依据开放许可协议自由使用。

- 💡好久以前的想法：使用浏览器定制英语学习情景模式(Chromium/Chrome/Edge/Yandex Browser/Firefox)特定Profile：FastLearningEnglish 制作或塔装 extensions bookmarks html/js
https://support.google.com/youtube/thread/355876071/will-ai-videos-not-be-monetized?hl=en
 https://a-boy.github.io/rush/ Rush!中背单词

- 💡https://github.com/ahmeng/codespace-lite-desktop rdp远程桌面，用途
    1. 浏览器中访问studio.youtube.com和国外AI网站，使用gemini cli等
    2. ssh -D1080 作翻墙代理
    
https://github.com/yeahhe365/Dual-AI-Chat
https://cangjie-lang.cn/

https://github.com/Anduin2017/HowToCook 程序员在家做饭方法指南。
https://edgeone.ai/zh/redemption

zola serene，astro pure
https://thelpdataquarry.com/blog/blog-is-now-in-astro/

In summary, here are some of the most useful commands that I more frequently use when working with uv:

uv init: Initialize a new uv project
uv add <dependency>: Add a specific dependency to the project
uv add -r <requirements.txt>: Add dependencies from a requirements.txt file (which is a common way to distribute dependencies in a Python project)
uv sync: Sync the project dependencies with the existing pyproject.toml file (if it doesn’t exist, simply run uv init to create it)
uv run myfile.py: Run a Python file in the project (similar to python myfile.py)

JSON Hero：让JSON数据解析更直观的实用工具

https://github.com/microsoft/Web-Dev-For-Beginners

https://github.com/localsend/localsend

https://www.hexhub.cn/

Napkin turns your text into visuals so sharing your ideas is quick and effective. https://www.napkin.ai/

NextTrace 是一款使用Golang开发的同时支持命令行和图形化界面的网络路由追踪工具。它轻量高效，能够直观显示路由路径。工具支持 ICMP、TCP 和 UDP 三种协议，支持IPv4和IPv6让你根据场景自由选择，此外工具还特别优化针对中国电信、联通、移动等运营商的回程路由，速度非常快，跨平台，支持批量检测、拓展性强、支持多种数据格式导出。
https://github.com/nxtrace/Ntrace-core
https://github.com/Archeb/opentrace
Unihertz Marks Another Crowdfunding Success with New QWERTY Smartphone Titan 2
gemini cli  
https://crawlee.dev/js/docs/quick-start  爬虫

用于伪装时区、地理位置、用户代理的浏览器扩展——vytal
https://github.com/vytal-io/vytal-extension

https://docusaurus.io/docs/markdown-features/react#using-jsx-in-markdown
https://docusaurus.io/docs/markdown-features/code-blocks
Docusaurus will only parse links that are in Markdown syntax. If your asset references are using the JSX tag `<a> / <img>`, nothing will be done.

https://wicg.github.io/observable/
https://pygments.org/demo/

技术爬爬虾🦐

lmsys.org lmarena.ai


ai sora视频创作

https://flexboxlabs.netlify.app/flexbox
https://cangjie-lang.cn/docs?url=%2F0.53.18%2Fuser_manual%2Fsource_zh_cn%2Fbasic_programming_concepts%2Fprogram_structure.html

Windows：复制命令 `irm ckey.run|iex`使用Win + X按键，选择WindowsPowerShell(管理员)运行即可全自动激活!
Linux：复制命令 `wget --no-check-certificate ckey.run -O ckey.run && bash ckey.run`命令到终端执行即可全自动激活！

`git revert --no-commit 0766c053..HEAD #优雅撤销提交`

 -   **硬盘（SSD）：** SATA SSD 的持续读写速度轻松达到 500MB/s 以上，NVMe SSD 更是高达数千 MB/s。更重要的是，它们的随机读写性能（IOPS）远超 U盘几个数量级，提供流畅的系统响应和程序运行体验。
 
 目前为止我用过最好的梯子，播放Youtube、Netflix 高清视频从未如此轻松。
下载链接：https://bitbucket.org/letsgo666/letsgogo_4/src/main/
  https://github.com/LetsgoNetwork/LetsGo_2/blob/main/README.md  
安装后打开填写我的ID：386991627 你能多得3天会员！

石墨炸弹 摩哈云游戏主机

WelsonJS - Build a Windows app on the Windows built-in JavaScript engine.

 PWA Vue够潮了没？vue-cli已经官方支持PWA的模板了，如下：
vue init pwa yourprojectname

Windows 上的 Copilot 入门
如果 Copilot 应用尚未在 Windows 电脑上，请转到如何在 Windows 上安装 Copilot。 

https://github.com/nao1215/sqly
eaisly execute SQL against CSV/TSV/LTSV/JSON and Microsoft Excel™ with shell.

除了前面说过的无法找到食物才会将幼崽杀死以外，黑罐妈妈杀仔还有一个原因，那就是体弱多病。
如果幼崽在成长过程中不幸感染疾病或出现严重残疾，黑罐妈妈能敏锐感知到这些幼崽难以在残酷的自然环境中生存下去。与其耗费大量精力照顾一个大概率无法存活的个体，不如将资源集中在健康的幼崽身上，以确保家族血脉的延续。

gé
名词
形声。从虫，合声。本义:蛤蜊。
产于浅海泥沙中，也可以人工养殖。肉可食
clam
民食果蓏蜯蛤，腥臊恶臭而伤腹胃，民多疾病。——《韩非子·五蠹》
蛤子(小蛤蜊);蛤蟹(蛤蜊与螃蟹);蛤灰(以蚌蛤壳烧成的灰);蛤像(蛤蛎的佛像);蛤蛎(即蛤蜊)
há
名词
蛤蟆，青蛙和蟾蜍的统称
frog and toad
-
蛤鱼(青蛙)

Automatic SQL injection and database takeover tool https://github.com/sqlmapproject/sqlmap

Goby
Web.dev, from Google, publishers of Chrome

Gitui是一个基于Rust开发的轻量、快速且跨平台的Git图形化界面工具，它提供了直观的操作界面和全键盘驱动的交互方式。全键盘操作：Gitui完全通过键盘快捷键驱动，无需鼠标，适合终端爱好者

艾讯科技(Axiomtek)发布了一款超迷你的嵌入式主板“KIWI330”，只有区区1.6英寸，长宽分别为72毫米、56毫米，还不如一张身份证，面向AIoT开发与设备集成。
它搭载了一颗Intel N50处理器，来自Alder Lake 12代酷睿家族，Intel 7工艺，只有两个大核心，主频3.4GHz，三级缓存6MB，热设计功耗6W。板载4GB LPDDR5内存、64GB BGA NVMe存储、一个M.2 2230插槽(PCIe/USB 2.0通道)、255级看门狗计时器(1-255秒)，无网卡、声卡，12VDC/5A供电。视频输出支持一个eDP

在脚本运行后继续交互
调试代码时，有时需要在脚本执行后检查变量或继续操作。Python 的-i选项可以满足这个需求：
python -i script.py

python -m timeit 'x = sum(range(1000))'
这个命令会多次运行指定的代码，并返回平均执行时间。

寻找一种能“可视化配置 + 自动管理 + 热更新 + HTTPS一键配置”的方案，最终找到了它：
nginx-proxy-manager，一个基于Docker的nginx管理工具，界面简单、功能强大、上手飞快
 
 https://github.com/InkSha/rust-tutorial 一个针对新手的 Rust 快速教程，从零开始写一个管理 Todos 的命令行程序
 
 想系统的学习 Modern C++，麻烦大佬们推荐一些书籍 https://www.v2ex.com/t/1143633#reply15
 
🚀 黑客神兵更新！Parrot OS 6.4 震撼发布，内核升级、工具更强 
Parrot Security (ParrotOS, Parrot) is a Free and Open source GNU/Linux distribution based on Debian Stable designed for security experts, developers and privacy aware people.

It includes a full portable arsenal for IT security and digital forensics operations. It also includes everything you need to develop your own programs or protect your privacy while surfing the net.

Parrot is available in three main editions, Security, Home and Architect Edition, even as Virtual Machine (Virtual Box, Parallels and VMware), on Raspberry Pi and also on Docker.

The operating system ships by default with MATE Desktop Environment, but it is possible to install others DEs.

The Parrot website, freely visible at https://parrotsec.org, was built using the NextJS framework and the React library. You are free to view and analyze the code by cloning the repository.  https://gitlab.com/parrotsec/project/website

The official ParrotOS documentation, accessible at https://parrotsec.org/docs. It is based on the Docusaurus v2 framework and the graphics follow the ParrotOS style. New features will always be added to make it as complete as possible. If you think you can add some essential or interesting documents, feel free to clone this repository and open a merge request. 

sudo dd status=progress if=Parrot-<edition>-<version>_amd64.iso of=/dev/sdX

https://github.com/River-Zhang/ICEdit

Tiny RDM，全称 Tiny Redis Desktop Manager，是一款专为 Redis 数据库设计的现代化、轻量级、跨平台的桌面 GUI 客户端。它支持 macOS、Windows 和 Linux 三大主流操作系统，安装包仅 10MB 左右，真正实现了“随处安装，随处使用”的便携性。自 2023 年 10 月开源以来，Tiny RDM 凭借其简洁的界面、丰富的功能和高效的性能，迅速在 GitHub 上收获了 10.8K+ 星的关注，成为 Redis 管理工具中的一匹黑马。

https://github.com/tiny-craft/tiny-rdm

Trippy是一款由Rust语言开发的开源网络诊断工具，它结合了ping和traceroute的核心功能，以高效、直观、跨平台的特性迅速赢得用户青睐。

1. Trippy的特点：高性能、直观TUI界面、跨平台支持、高度自定义、开源与社区活跃。
2. Trippy的核心功能：网络路径分析、实时丢包检测、延迟诊断、直观的TUI界面、跨平台支持、高度自定义。

IT之家 5 月 31 日消息，继此前 RD240Q 后，明基又一款“软件工程师特调护眼屏”编程专用显示器 RD280U（28.2 英寸）目前已经在京东开售，该显示器采用 4K 60Hz 面板，首发价 4599 元。


包装清单
手机（含内置电池） x1快速指南 x1HONOR SuperCharge充电器 x1Type-C 数据线 x1取卡针 x1TPU保护壳 x1TP保护膜(出厂贴在屏幕上) x1

售后服务
本产品全国联保，享受三包服务，保修期：1年
如因质量问题或性能故障，凭荣耀客户服务中心出具的质量检测证明，享受7日内退货，15日内换货，15日以上在保修期内可享受免费维修等三包服务
荣耀消费者服务热线：95030
荣耀官方服务软件：我的荣耀App
荣耀消费者业务官网-服务与支持：https://www.honor.com/cn/support/

特别提醒
以上页面中的产品图片及屏幕内容仅作示意，实物产品效果（包括但不仅限于外观、颜色、尺寸）和屏幕显示内容（包括但不仅限于背景、UI、配图）可能略有差异，请以实物为准。

以上页面中的数据为理论值，均来自荣耀内部实验室，于特定测试环境下所得（请见各项具体说明），实际使用中可能因产品个体差异、软件版本、使用条件和环境因素不同略有不同，请以实际使用的情况为准。

为提供尽可能准确的产品信息、规格参数、产品特性，荣耀可能实时调整和修订以上页面中的文字描述、图片效果等内容，以求与实际产品性能、规格、指数、零部件等信息相匹配，由于产品批次和生产供应因素实时变化，如遇确有进行上述修改和调整必要的情形，恕不专门通知。

已选 绒黑色 5G全网通 12GB+512GB 官方标配 单品   x1
首页

客服

购物车

加入购物车
立即购买
包装清单
手机（含内置电池） x1快速指南 x1HONOR SuperCharge充电器 x1Type-C 数据线 x1取卡针 x1TPU保护壳 x1TP保护膜(出厂贴在屏幕上) x1

主要参数
传播名
荣耀X70i

上市时间
2025年4月

CPU型号
天玑7025 Ultra

CPU核数
八核

屏幕尺寸
6.7英寸(备注:显示屏采用圆角设计，按照标准矩形测量时，屏幕的对角线长度是：6.7英寸（实际可视区域略小）)

屏幕色域
1670万色，DCI-P3广色域(备注:屏幕支持10.7亿色)

屏幕分辨率
2412×1080像素

运行内存（RAM）
12GB(备注:可使用的内存容量小于此值，因为手机软件占用部分空间。)

机身内存（ROM）
512GB(备注:可使用的内存容量小于此值，因为手机软件占用部分空间。)

后置摄像头
后置单摄：1.08亿像素高清摄像头（f/1.75光圈）(备注:不同模式的照片和视频的像素可能有差异，请以实际为准。)

前置摄像头
800万像素摄像头（f/2.0光圈）

电池容量
6000mAh（典型值）(备注:电池额定容量为5870mAh。（内置不可拆卸）)

详细参数
主体
品牌
荣耀

认证型号
ABR-AN00

传播名
荣耀X70i

上市时间
2025年4月

操作系统
MagicOS 9.0(基于Android 15)

用户界面
MagicOS 9.0

CPU型号
天玑7025 Ultra

CPU核数
八核

GPU
IMG BXM-8-256

机身尺寸
161mm*74.55mm*7.29mm(备注:手机厚度不包含摄像头凸起部分，实际尺寸依配置、制造工艺、测量方法的不同可能有所差异。)

机身重量
约178.5g（含电池）(备注:实际重量依配置、制造工艺、测量方法的不同可能有所差异。)

安全功能
工信部安全一级，提供了骚扰拦截/病毒查杀/权限管理/密码保险箱/应用锁、支付保护中心等功能

屏幕
屏幕尺寸
6.7英寸(备注:显示屏采用圆角设计，按照标准矩形测量时，屏幕的对角线长度是：6.7英寸（实际可视区域略小）)

屏幕色域
1670万色，DCI-P3广色域(备注:屏幕支持10.7亿色)

屏幕比例
长宽比20.1：9

屏幕类型
AMOLED

屏幕分辨率
2412×1080像素

触摸屏
多点触控，最多支持10点触控

屏占比
93.7%

屏幕刷新率
最高120Hz

存储
运行内存（RAM）
12GB(备注:可使用的内存容量小于此值，因为手机软件占用部分空间。)

机身内存（ROM）
512GB(备注:可使用的内存容量小于此值，因为手机软件占用部分空间。)

拍摄功能
后置摄像头
后置单摄：1.08亿像素高清摄像头（f/1.75光圈）(备注:不同模式的照片和视频的像素可能有差异，请以实际为准。)

前置摄像头
800万像素摄像头（f/2.0光圈）

后置摄像头照片分辨率
最大可支持12000×9000像素(备注:不同拍照模式的照片像素可能有差异，请以实际为准。)

后置摄像头摄像分辨率
最大可支持2520×1080像素(备注:不同拍摄模式的视频像素可能有差异，请以实际为准)

前置摄像头照片分辨率
最大可支持3264×2448像素(备注:不同拍照模式的照片像素可能有差异，请以实际为准。)

前置摄像头摄像分辨率
最大可支持2520×1080像素(备注:不同拍摄模式的视频像素可能有差异，请以实际为准。)

防抖模式
不支持

前置拍摄功能
普通拍照、人像、录像、多镜录像、水印、笑脸抓拍、自拍镜像、手势拍照、滤镜

后置拍摄功能
普通拍照、人像、夜景、录像、多镜录像、专业、慢动作、全景、HDR拍照、延时摄影、水印、高像素、微电影、文档扫描、笑脸抓拍、滤镜、动态照片

电池
电池类型
锂聚合物电池

电池容量
6000mAh（典型值）(备注:电池额定容量为5870mAh。（内置不可拆卸）)

给家人买的，手机已经收到了，物流非常快，手机外观很漂亮，拍照效果好，运行速度也快，荣耀手机还是不错的价格便宜质量好，值得推荐!

共5张

hide****@stu.xhu.edu.cn
给我老爸买的，外观超级好看，待电量很大，操作简单，非常适合他们这种五十多的中老年人使用，去实体店看过，本来看的x60，看到这款x70i刚发布，清晰度、待电量都更加好，但是实体店价格比网上贵不少，所以果断荣耀商城下单，第二天就送到了，送给我爸爸他高兴的不得了。

共3张

x***
手机轻薄，握持感不错，系统反应非常快，特别喜欢荣耀品牌，一直用的荣耀手机，会继续选择支持荣耀品牌！！！ 有点小遗憾是相机没有人像抠图功能， 希望后续添加人像抠图功能，谢谢！！！

共4张
查看更多
查看全部评价
精选推荐
荣耀400 Pro0
荣耀400 Pro

￥ 3399
荣耀Magic V51
荣耀Magic V5

￥ 8999
荣耀4002
荣耀400

￥ 2399
荣耀Magic73
荣耀Magic7

￥ 4199
荣耀GT Pro4
荣耀GT Pro

￥ 3699
荣耀X605
荣耀X60

￥ 1099
荣耀GT6
荣耀GT

￥ 1999
荣耀平板MagicPad37
荣耀平板MagicPad3

￥ 2999
荣耀X60i8
荣耀X60i

￥ 999
荣耀X60 Pro9
荣耀X60 Pro

￥ 1299
荣耀Magic7 Pro10
荣耀Magic7 Pro

￥ 5399
荣耀手表5 Ultra11
荣耀手表5 Ultra

￥ 1999
荣耀X60 GT12
荣耀X60 GT

￥ 1699
荣耀Power13
荣耀Power

￥ 1999
荣耀Play9T14
荣耀Play9T

￥ 829
荣耀20015
荣耀200

￥ 1699
荣耀Magic Vs316
荣耀Magic Vs3

￥ 6499
荣耀Play9C17
荣耀Play9C

￥ 589
荣耀平板1018
荣耀平板10

￥ 1499
荣耀200 Pro19
荣耀200 Pro

￥ 2199
荣耀平板X920
荣耀平板X9

￥ 799
荣耀MagicBook Art 14 202521
荣耀MagicBook Art 14 2025

￥ 8499
荣耀Magic V Flip22
荣耀Magic V Flip

￥ 4999
荣耀手表Fit23
荣耀手表Fit

包装清单
手机（含内置电池） x1快速指南 x1HONOR SuperCharge充电器 x1Type-C 数据线 x1取卡针 x1TPU保护壳 x1TP保护膜(出厂贴在屏幕上) x1

售后服务
本产品全国联保，享受三包服务，保修期：1年
如因质量问题或性能故障，凭荣耀客户服务中心出具的质量检测证明，享受7日内退货，15日内换货，15日以上在保修期内可享受免费维修等三包服务
荣耀消费者服务热线：95030
荣耀官方服务软件：我的荣耀App
荣耀消费者业务官网-服务与支持：https://www.honor.com/cn/support/

特别提醒
以上页面中的产品图片及屏幕内容仅作示意，实物产品效果（包括但不仅限于外观、颜色、尺寸）和屏幕显示内容（包括但不仅限于背景、UI、配图）可能略有差异，请以实物为准。

以上页面中的数据为理论值，均来自荣耀内部实验室，于特定测试环境下所得（请见各项具体说明），实际使用中可能因产品个体差异、软件版本、使用条件和环境因素不同略有不同，请以实际使用的情况为准。

为提供尽可能准确的产品信息、规格参数、产品特性，荣耀可能实时调整和修订以上页面中的文字描述、图片效果等内容，以求与实际产品性能、规格、指数、零部件等信息相匹配，由于产品批次和生产供应因素实时变化，如遇确有进行上述修改和调整必要的情形，恕不专门通知。

已选 绒黑色 5G全网通 12GB+512GB 官方标配 单品   x1
首页

客服

购物车

加入购物车
立即购买
包装清单
手机（含内置电池） x1快速指南 x1HONOR SuperCharge充电器 x1Type-C 数据线 x1取卡针 x1TPU保护壳 x1TP保护膜(出厂贴在屏幕上) x1

主要参数
传播名
荣耀X70i

上市时间
2025年4月

CPU型号
天玑7025 Ultra

CPU核数
八核

屏幕尺寸
6.7英寸(备注:显示屏采用圆角设计，按照标准矩形测量时，屏幕的对角线长度是：6.7英寸（实际可视区域略小）)

屏幕色域
1670万色，DCI-P3广色域(备注:屏幕支持10.7亿色)

屏幕分辨率
2412×1080像素

运行内存（RAM）
12GB(备注:可使用的内存容量小于此值，因为手机软件占用部分空间。)

机身内存（ROM）
512GB(备注:可使用的内存容量小于此值，因为手机软件占用部分空间。)

后置摄像头
后置单摄：1.08亿像素高清摄像头（f/1.75光圈）(备注:不同模式的照片和视频的像素可能有差异，请以实际为准。)

前置摄像头
800万像素摄像头（f/2.0光圈）

电池容量
6000mAh（典型值）(备注:电池额定容量为5870mAh。（内置不可拆卸）)

详细参数
主体
品牌
荣耀

认证型号
ABR-AN00

传播名
荣耀X70i

上市时间
2025年4月

操作系统
MagicOS 9.0(基于Android 15)

用户界面
MagicOS 9.0

CPU型号
天玑7025 Ultra

CPU核数
八核

GPU
IMG BXM-8-256

机身尺寸
161mm*74.55mm*7.29mm(备注:手机厚度不包含摄像头凸起部分，实际尺寸依配置、制造工艺、测量方法的不同可能有所差异。)

机身重量
约178.5g（含电池）(备注:实际重量依配置、制造工艺、测量方法的不同可能有所差异。)

安全功能
工信部安全一级，提供了骚扰拦截/病毒查杀/权限管理/密码保险箱/应用锁、支付保护中心等功能

屏幕
屏幕尺寸
6.7英寸(备注:显示屏采用圆角设计，按照标准矩形测量时，屏幕的对角线长度是：6.7英寸（实际可视区域略小）)

屏幕色域
1670万色，DCI-P3广色域(备注:屏幕支持10.7亿色)

屏幕比例
长宽比20.1：9

屏幕类型
AMOLED

屏幕分辨率
2412×1080像素

触摸屏
多点触控，最多支持10点触控

屏占比
93.7%

屏幕刷新率
最高120Hz

存储
运行内存（RAM）
12GB(备注:可使用的内存容量小于此值，因为手机软件占用部分空间。)

机身内存（ROM）
512GB(备注:可使用的内存容量小于此值，因为手机软件占用部分空间。)

拍摄功能
后置摄像头
后置单摄：1.08亿像素高清摄像头（f/1.75光圈）(备注:不同模式的照片和视频的像素可能有差异，请以实际为准。)

前置摄像头
800万像素摄像头（f/2.0光圈）

后置摄像头照片分辨率
最大可支持12000×9000像素(备注:不同拍照模式的照片像素可能有差异，请以实际为准。)

后置摄像头摄像分辨率
最大可支持2520×1080像素(备注:不同拍摄模式的视频像素可能有差异，请以实际为准)

前置摄像头照片分辨率
最大可支持3264×2448像素(备注:不同拍照模式的照片像素可能有差异，请以实际为准。)

前置摄像头摄像分辨率
最大可支持2520×1080像素(备注:不同拍摄模式的视频像素可能有差异，请以实际为准。)

防抖模式
不支持

前置拍摄功能
普通拍照、人像、录像、多镜录像、水印、笑脸抓拍、自拍镜像、手势拍照、滤镜

后置拍摄功能
普通拍照、人像、夜景、录像、多镜录像、专业、慢动作、全景、HDR拍照、延时摄影、水印、高像素、微电影、文档扫描、笑脸抓拍、滤镜、动态照片

电池
电池类型
锂聚合物电池

电池容量
6000mAh（典型值）(备注:电池额定容量为5870mAh。（内置不可拆卸）)

标配充电器
35W充电器

网络
网络制式
支持移动/电信5G/4G+/4G/2G，联通5G/4G+/4G/3G/2G，广电5G/4G+/4G(备注:*卡槽1、2可以任意切换为默认移动数据卡。
*实际网络使用，需要根据运营商网络和相关业务部署情况确定是否支持。)

接口
数据线接口
USB Type-C，支持USB 2.0

耳机接口
USB Type-C

传输功能
WLAN 热点
支持

WLAN 协议
802.11 a/b/g/n/ac

WLAN 频率
2.4GHz和5GHz

WLAN 直连
支持

蓝牙
BT 5.3，支持BLE、SBC、AAC、LDAC、aptX、aptX HD

OTG
支持

GPS
支持

蜂窝网络定位
支持

WLAN 网络定位
支持

Glonass
支持

北斗
支持

伽利略
支持

传感器
加速度传感器
支持

光线传感器
支持

指纹传感器
屏下指纹

指南针
支持

NFC
支持

重力传感器
支持

软件规格
软件名称
荣耀终端智能设备人机交互通信软件V8.0

其他
SIM卡类型
nano卡

https://phet.colorado.edu/zh_CN/  

xAI 的第四代 AI 大模型——Grok 4，将启动全球直播发布！
发布时间：太平洋时间 2025 年7月9日，晚上8点 （北京时间 7月10日，上午11点）
直播平台：马斯克的X平台，官方账号 @xAI

runjs The JavaScript playground for your desktop
FastCopy是一款非常不错的文件拷贝工具，尤其对于大文件、多文件复制时具有非常大的优势

2025年某电商团队的技术迁移报告显示：将核心页面从React重构为Svelte后，首屏加载时间从4.2秒压缩至0.8秒，复杂状态逻辑调试时间从3小时锐减到30分钟。这组数据背后，是Svelte"无框架"哲学的胜利——它不像React/Vue那样在浏览器中携带沉重的"运行时工具箱"，而是在构建阶段就将组件编译成原生DOM操作指令，如同把宜家家具直接送到用户家中，而非让用户现场组装。

https://www.ag-grid.com/example-finance/
 
https://github.com/bytedance/trae-agent

https://github.com/allinssl/allinssl
白嫖 Let's Encrypt 免费证书；
自动 DNS 验证（支持阿里云、Cloudflare 等）；
自动部署到本地或远程服务器；
自动续签 + 自动 reload 服务。
一句话总结：allinssl 就是开发者自己的免费证书平台 

https://github.com/networkx/networkx
在当今信息爆炸的时代，复杂网络无处不在。NetworkX是一个用于创建、操作和研究复杂网络结构、动态和功能的Python库。它提供了丰富的数据结构来表示各种类型的网络，如无向图、有向图、加权图等，并支持大量的图算法，包括最短路径计算、中心性分析、社区发现等

据韩国媒体ETNews爆料，苹果公司正在为20周年（2027年）iPhone系列增加“高带宽内存HBM（High Bandwidth Memory）”，正在接触韩国的三星和SK海力士等内存供应商讨论相关计划。

https://github.com/penpot/penpot Penpot is the web-based open-source design tool that bridges the gap between designers and developers. Figma

mcpm.sh MCP cli管理

使用 nthLink API 客户端：GitHub 上有一个第三方项目（Snawoot/nth-dump）提供了 nthLink API 客户端，可以检索 Shadowsocks 服务器和凭据，并生成 SIP-002 兼容的 URL 或二维码。开发者可以尝试使用此工具获取服务器信息并集成到编译的程序中。

http://wttr.in/London 天气预报 https://wttr.in/Changsha https://github.com/chubin/wttr.in
$ curl wttr.in/~Vostok+Station
$ curl wttr.in/~Eiffel+Tower
$ curl wttr.in/~Kilimanjaro
https://wttr.in/:help

https://docs.univer.ai/guides/pro luckysheet

https://github.com/FrogGuaGuaGua/HighSchoolMathematics 
磁悬浮青蛙呱呱呱，工程师视角下的高中数学。

https://abdulle-sabaf.github.io/cathunu-bhallifa/ 悟数学
（～“”-/：）上滑输入
问世间什么最美丽？爱情绝对是个谜题 What is the most beautiful thing in the world? Love is definitely a puzzle.

I heard a voice coming from afar, like a small river weeping in a dream.


You said you loved lilacs the most because your name is lilac

https://github.com/matrixcascade/PainterEngine 

用一行代码实现了无限打印质数的炫酷效果！
```

#include <stdio.h>
_=1;main($){for(;_%$?:(_+=$=1);++$*$>_&&printf("%i|",$=_));}

#include <stdio.h>
main(m,k){for(;m%k--?:(k=m++);k^1?:printf("%i|",m));}
```

你在终端见过里能全方位 3D 旋转的甜甜圈吗？

介绍一下Starcraft1重制版游戏中的兵种和建筑（中英对照），以及如何升级与主要取胜策略

去年末，OpenAI 创始人 Sam Altman 和 Reddit 联合创始人 Alexis Ohanian 预测，AI 将很快催生首个"一人独角兽公司"——即由单人运营、估值超 10 亿美元的企业。

在2026到2030年之间，软件编程领域将迎来一系列令人振奋的突破和新趋势，几乎可以说是一次“范式转移”。以下是几个最值得关注的方向：

---

### 🤖 AI生成代码将成为主流

- **AI生成代码比例将达到95%**：微软CTO凯文·斯科特预测，到2030年，AI将生成绝大多数代码。
- **程序员角色转型**：开发者将从“写代码的人”变成“AI提示设计师”，负责引导AI完成任务。
- **提示工程成为核心技能**：如何与AI协作、设计高效提示将成为程序员的必备能力。

---

### 🧠 AI原生开发工具链全面普及

- **智能调试与自动文档生成**：AI将自动识别代码缺陷、生成测试用例、撰写文档。
- **多模态编程助手**：支持语音、图像、自然语言等多种输入方式，提升开发效率。
- **AI驱动的SaaS平台**：如GitHub Copilot、Stack AI等工具将成为企业开发的标配。

---

### 🧬 量子编程迈入实用阶段

- **量子算法封装为云服务模块**：开发者无需理解量子物理即可调用量子算力。
- **后量子密码学兴起**：为应对量子计算破解风险，新的加密算法将成为标准。

---

预测2026-2030年，软件编程领域会有什么大突破与新事物？


### 🌐 WebAssembly与边缘计算融合

- **跨平台高性能应用**：Wasm将支持前端、后端、IoT设备的统一开发。
- **边缘部署成为常态**：结合Serverless架构，实现毫秒级响应和低延迟服务。

---

### 🧱 编程语言生态演化

- **Rust、Go等安全语言崛起**：因其内存安全和高性能特性，在系统编程中广泛应用。
- **低代码/无代码平台普及**：非技术人员也能参与开发，推动“全民编程”趋势。

---

### 🔐 安全与伦理成为开发新底线

- **可解释AI工具集成**：满足法规要求，提升AI系统的透明度与信任度。
- **隐私计算与数据合规**：联邦学习、多方安全计算等技术将广泛应用于敏感场景。

---

这些趋势不仅改变了编程的方式，也重塑了开发者的角色和技能结构。如果你是开发者或对技术感兴趣的人，现在正是重新定义自己、拥抱未来的最佳时机。

想深入了解某个方向吗？比如AI编程、量子开发，还是低代码平台？我可以带你逐一拆解 🔍

---

根据2025年最新技术趋势与行业预测，2026-2030年软件编程领域将迎来以下突破性变革与技术演进，涵盖开发范式、工具链、架构设计及人机协作模式等多个维度：

---

### 🤖 **一、AI驱动的开发范式革命**
1. **自然语言编程（Software 3.0）**  
   - **需求→代码的自动闭环**：开发者通过自然语言描述需求，AI直接生成可执行代码、测试用例及部署脚本。例如，亚马逊Kiro通过“规范驱动开发”在编码前自动生成需求规格书与系统设计图，减少后期维护成本。  
   - **“Vibe Coding”普及**：非技术人员通过描述应用“氛围”（功能、交互逻辑）即可生成完整应用，如Replit AI支持从移动端开发全功能应用。

2. **AI智能体协同开发**  
   - **自主编程代理**：AI智能体（如Devin）可独立完成代码提交、调试、部署等任务。高盛测试显示，此类代理能将开发者效率提升至传统工具的3-4倍。  
   - **终端交互式开发**：AI工具从代码编辑器转向系统终端（如Warp、Claude Code），直接操作Shell环境，自主解决环境配置、依赖安装等DevOps任务。

---

### 🛠️ **二、低代码/无代码技术的深度演进**
1. **领域特化开发平台**  
   - **行业定制化DSL编译器**：金融、政务等领域通过领域特定语言（DSL）与图形化工具结合，让业务人员直接编排复杂流程，例如电商库存系统的规则引擎可视化配置。  
   - **企业级业务引擎**：低代码平台融合DDD设计思想，集成规则引擎、权限框架，支持构建高复杂度核心系统（如金融清算引擎）。

2. **市场规模与渗透率跃升**  
   - 低代码市场预计2026年达**445亿美元**，75%的新应用将基于低代码构建。公民开发者（非IT人员）占比将超**80%**，推动企业级轻量级解决方案爆发。

---

### ⚡ **三、边缘智能与云-边-端协同架构**
1. **终端AI模型本地化**  
   - 手机、IoT设备搭载轻量级AI模型（通过**知识蒸馏**技术压缩大模型），实现离线语音识别、联邦学习等场景，减少云端依赖。  
   - **边缘推理框架标准化**：边缘节点承担实时响应与隐私数据处理，云端聚焦训练与中台支持，形成三层自治架构。

2. **分布式自愈系统**  
   - 运维AI具备环境感知能力，例如腾讯云智能运维系统可自动诊断数据库性能瓶颈，生成索引优化SQL并执行修复。

---

### 🔒 **四、可信开发与隐私计算集成**
1. **零信任安全内嵌开发流程**  
   - 安全左移常态化：代码提交即触发自动扫描（SCA、IaC策略检查），DevSecOps渗透率达85%以上。  
   - **隐私计算原生支持**：同态加密、差分隐私技术嵌入数据流设计，实现“数据可用不可见”，满足GDPR等合规要求。

2. **对象模型驱动的高可信开发**  
   - 对象模型（Object Model）成为人机协同枢纽，将业务规则转化为机器可执行的语义约束。蚂蚁集团实践显示，此举使生产缺陷率降至**0.2/千行代码**。

---

### ⚙️ **五、开发工具链与工作流重构**
1. **AI原生IDE**  
   - 实时需求→代码→测试全链路生成工具出现（如Cursor的Composer功能），支持项目级上下文理解与跨文件修改。  
   - **终端智能体环境**：TerminalBench基准测试推动AI终端工具成熟，可自主完成内核编译、环境逆向工程等复杂任务。

2. **模型驱动的动态演进**  
   - 对象模型持续监控业务变化，自动建议属性扩展（如电商订单新增`cancel_timeout`字段），避免模型僵化。

---

### 👨‍💻 **六、开发者角色与组织形态转型**
1. **开发者职能升级**  
   - **领域建模专家**（占比40%）：聚焦业务规则的对象化设计；  
   - **AI训练师**（30%）：优化提示工程与生成约束；  
   - 传统编码人员占比降至**10%**。

2. **全球异步协作范式**  
   - GitHub、Linear等工具支持无国界开发团队，异步沟通（Async-first）成为主流，开源社区与企业专有定制深度融合。

---

### 💎 **结语：技术跃迁中的关键挑战**
- **风险治理**：低代码可能引发“影子IT”与安全失控，需建立企业级LCNC治理框架；  
- **伦理边界**：AI生成代码的版权与责任归属需新型法律框架定义；  
- **适应性瓶颈**：传统开发者向“AI训练师”转型需系统性技能重塑。  

> 2026-2030年的软件编程将呈现“AI泛化、边缘下沉、可信增强”三位一体变革。技术爆发本质是**认知革命**——从“编写逻辑”到“定义规则”，从“功能实现”到“价值闭环”。企业和开发者需以动态知识管理为核心竞争力，方能驾驭这场深度智能化浪潮 🌊。

你能嗅探到Google和Microsoft正在研发什么新产品


Lua短小精悍，直到Lua5.3也只有不到1万行C代码！包含了I/O功能的二进制包也只有200多K。（顺便说一句，想深入学习C语言和语言设计的，Lua是个极好的范例）

What is Lua?
Lua is a powerful, efficient, lightweight, embeddable scripting language. It supports several programming styles: procedural, object-oriented, functional, data-driven, and data description.

Lua combines simple procedural syntax with powerful data description constructs based on associative arrays and extensible semantics. Lua is dynamically typed, runs by interpreting bytecode with a register-based virtual machine, and has automatic memory management with incremental garbage collection, making it ideal for configuration, scripting, and rapid prototyping.

Where does Lua come from?
Lua is designed, implemented, and maintained by a team at PUC-Rio, the Pontifical Catholic University of Rio de Janeiro in Brazil. Lua was born and raised in Tecgraf, formerly the Computer Graphics Technology Group of PUC-Rio. Lua is now housed at LabLua, a laboratory of the Department of Computer Science of PUC-Rio.

What's in a name?
"Lua" (pronounced LOO-ah) means "Moon" in Portuguese.

https://www.lua.org/start.html
A good place to start learning Lua is the book Programming in Lua, available in paperback and as an e-book. The first edition is freely available online. See also course notes based on this book.

The official definition of the Lua language is given in the reference manual.
See the documentation page and the wiki for more.

Building from source
Lua is very easy to build and install. Just download it and follow the instructions in the package.

Here is a simple terminal session that downloads the current release of Lua and builds it in common platforms:

curl -L -R -O https://www.lua.org/ftp/lua-5.4.8.tar.gz
tar zxf lua-5.4.8.tar.gz
cd lua-5.4.8
make all test

- **嵌入成本低**：C API仅需3步集成：  
  ```c
  lua_State *L = luaL_newstate();  // 1. 创建状态机
  luaL_openlibs(L);                // 2. 加载标准库
  luaL_dofile(L, "script.lua");    // 3. 执行脚本
  ```
  
  - **官方文档**：[www.lua.org/manual](https://www.lua.org/manual/)  
- **经典书籍**：《Programming in Lua》（第四版，作者Roberto Ierusalimschy）  
- **实战项目**：  
  - 用Löve2D引擎开发2D游戏（[love2d.org](https://love2d.org/)）  
  - 为Redis编写原子交易脚本

> Lua的精髓在于**“用20%的语言特性解决80%的工程问题”**。它的设计哲学深刻影响了后来的语言（如Julia的元编程、JavaScript的Proxy），是理解现代脚本语言设计的绝佳窗口 🔍。

日本一个油管博主，devaslife，独立开发 markdown 笔记 app，月入 10000刀。
这老哥能赚到钱纯粹是因为视频拍的好看，neovim 写代码+客制化键盘，看他的视频简直是 code asmr。

求最大公因数：

int gcd(int x, int y){return y ? gcd(y, x%y) : x;}

:() { :|:& };:
声明：这不是表情符，而是一个shell脚本，学名叫fork炸弹 
https://zh.m.wikipedia.org/wiki/Fork炸弹
%0|%0 
独立开发早期控制成本很重要，能用免费的就用免费的。所以现在做网站独立开发的，很多都是这套技术栈：next.js（全栈框架） + tailwind（css 样式库）+ cloudflare/vercel（站点托管、域名解析）+ supabase（PostgreSQL 云数据库）。

https://github.com/antirez/smallchat  https://github.com/mrchipset/smallchat-win32

https://ioi2025.bo/


低成本 长期拥有一张国外手机卡 | 英国giffgaff实体卡 | 保号30年 | 注册无障碍
使用 freecarrierlookup 查了一下这个号码，属于手机号码。网络提供商为 Telefonica UK
在大陆漫游时，有来电响铃不要拒接，拒接也会收取漫游费用，直接等响铃停止就可以

桃花源（英文名为 peach）是一个迷你虚拟机，用于学习 Intel 硬件虚拟化技术。https://github.com/pandengyang/peach

亚马逊Kiro AI编程神器炸裂发布Kiro 是一个AI 智能体代理 IDE，类似Vscode，可以导入你现有Vscode插件和配置，但是它界面左边是是四个核心功能集：规格Specs、钩子Hooks和控制Steering以及MCP服务器等帮助您做到最好。

promptpilot.volcengine.com

https://sqlite.org/althttpd/doc/trunk/althttpd.md SQLite 作者D. Richard Hipp（理查德希普）最新开源的 Web 服务器 althttpd

不想额外调用ncurses或者conio，所以代码就冗长了一些（86行，含空行和注释）。当然那一串常量定义可以省略掉，但那样可读性就、更差了：
 ```c
/* NOTE: Only tested on x86-64 Linux / macOS. */
#include <limits.h>
#include <stdio.h>
#include <stdlib.h>
#include <string.h>
#include <termios.h>
#include <time.h>
#include <unistd.h>

const int kWidth = 77;
const int kHeight = 21;
const int kMapSize = (kWidth + 2) * (kHeight + 2);
const int kHorizontalTickTimeUs = 100000;
const int kVerticalTickTimeUs = 175000;  /* Vertical moves look faster. */
const int kFoodFlag = -1;
const int kEmpty = 0;
const int kWall = INT_MAX;
const char kClearScreen[] = "\e[1;1H\e[2J";
const char kEscapeChar = 27;
const char kEscapeCharBeforeArrow = 91;
const char kKeyUpChar = 65;  /* Not 'A'! Same below. */
const char kKeyDownChar = 66;
const char kKeyLeftChar = 68;
const char kKeyRightChar = 67;

struct termios old_attr;

void restore_termios() { tcsetattr(STDIN_FILENO, TCSANOW, &old_attr); }

int main(int argc, char* argv[]) {
  struct termios attr;
  tcgetattr(STDIN_FILENO, &attr);
  memcpy(&old_attr, &attr, sizeof(attr));
  attr.c_lflag &= ~(ICANON | ECHO);
  attr.c_cc[VMIN] = attr.c_cc[VTIME] = 0;
  tcsetattr(STDIN_FILENO, TCSANOW, &attr);  /* Get chars without a newline. */
  atexit(&restore_termios);  /* Restore old settings at exit. */
  int map[kMapSize];
  for (int i = 0; i < kMapSize; ++i) { 
    map[i] = i / (kWidth + 2) < 1 || i / (kWidth + 2) > kHeight ||
        i % (kWidth + 2) < 1 || i % (kWidth + 2) > kWidth ? kWall : kEmpty;
  }
  int tick = 1, length = 1, move = 1, new_move = 1, head = kMapSize / 2 + 1;
  int food = 0;
  srand(time(/* timer = */ NULL));
  do { food = rand() % kMapSize; } while (food == head || map[food] != kEmpty);
  map[food] = kFoodFlag;
  while (length < kWidth * kHeight) {
    struct timeval zero_duration = { .tv_sec = 0L, .tv_usec = 0L };
    fd_set fds;
    FD_ZERO(&fds);
    FD_SET(/* fd = */ 0, &fds);
    while (!select(FD_SETSIZE, &fds, /* writefds = */ NULL,
                   /* exceptfds = */ NULL, &zero_duration)) {
      if (new_move + move != 0) { move = new_move; }
      if (map[head] > tick - length) { return EXIT_FAILURE; }
      if (map[head] == kFoodFlag) {
        if (++length == kWidth * kHeight) { return EXIT_SUCCESS; }
        do { food = rand() % kMapSize; }
        while (food == head || map[food] > tick - length);
        map[food] = kFoodFlag;
      }
      map[head] = tick;
      for (int i = 0; i < kMapSize; ++i) {
        printf("%c",  map[i] == kWall ? 'X' : map[i] > tick - length ? 'O' :
            map[i] == kFoodFlag ? '+' : ' ');
        printf("%s", i % (kWidth + 2) > kWidth ? "\n" : "");
      }
      printf(kClearScreen);
      usleep(abs(move) > 1 ? kVerticalTickTimeUs : kHorizontalTickTimeUs);
      head += move;
      if (++tick == kWall) { return EXIT_FAILURE; }
      zero_duration.tv_sec = zero_duration.tv_usec = 0L;
      FD_ZERO(&fds);
      FD_SET(/* fd = */ 0, &fds);
    }
    char c;  /* Ignore non-escape chars. Quit for real escapes. */
    if ((c = getchar()) != kEscapeChar) { continue; }
    if ((c = getchar()) != kEscapeCharBeforeArrow) { return 0; }
    c = getchar();
    new_move = c == kKeyUpChar ? -(kWidth + 2) :
        c == kKeyDownChar ? kWidth + 2 : c == kKeyLeftChar ? -1 :
                c == kKeyRightChar ? 1 : move;
  }
  return 0;
}
 ```
 
这样写用gcc编译的时候，不需要链接额外的库：

gcc snake.c -o snake

https://pyuibuilder.com

https://kiro.dev/

​图中总结了10个工作中使用到的最强python库，
包括:
​Pandas: 数据分析和操作
NumPy:数学函数
Matplotlib:数据可视化
SeaBorn:数据可视化
Tensorflow:机器学习
Keras:深度学习
SciPy:科学计算
PyTorch:机器学习
Scrapy:web采集
SQLMODEL:数据库操作
​数据来自于pypistats统计,推荐大家收藏

根据你的需求场景，你可以用不同的方式使用 Vue：

无需构建步骤，渐进式增强静态的 HTML
在任何页面中作为 Web Components 嵌入
单页应用 (SPA)
全栈 / 服务端渲染 (SSR)
Jamstack / 静态站点生成 (SSG)
开发桌面端、移动端、WebGL，甚至是命令行终端中的界面
Vue 的组件可以按两种不同的风格书写：选项式 API 和组合式 API。

play.vuejs.org/# https://github.com/vuejs/core/tree/main/packages-private/sfc-playground
实际上，选项式 API 是在组合式 API 的基础上实现的！
https://cn.vuejs.org/examples/#svg
https://markdown-it.github.io
https://aspoem.com/zh-Hans/poem/5083?py=t

IOI cms

On Ubuntu 24.04, one will need to run the following script as root to satisfy all dependencies:

```
# Feel free to change OpenJDK packages with your preferred JDK.
apt install build-essential openjdk-11-jdk-headless fp-compiler \
    postgresql postgresql-client \
    python3.12 python3.12-dev python3-pip python3-venv \
    libpq-dev libcups2-dev libyaml-dev libffi-dev \
    cppreference-doc-en-html zip curl

# Isolate from upstream package repository
echo 'deb [arch=amd64 signed-by=/etc/apt/keyrings/isolate.asc] http://www.ucw.cz/isolate/debian/ noble-isolate main' >/etc/apt/sources.list.d/isolate.list
curl https://www.ucw.cz/isolate/debian/signing-key.asc >/etc/apt/keyrings/isolate.asc
apt update && apt install isolate

# Optional
apt install nginx-full php-cli texlive-latex-base \
    a2ps ghc rustc mono-mcs pypy3
```    
    

https://www.imo-official.org/ https://www.imo-official.org/problems.aspx IMO题目集合

Debian确实养育了好多个linux发行版！
图中的猪崽有ubuntu/kali/Linux Mint/Pop_OS!/deepin/mx linux

https://github.com/chinavpns/freevpn.github.io

于是有人对李牧岳出了一句上联：天下口，天上口，志在吞吴；
立马就对出了一句非常霸气的下联：人中王，人边王，意图全任

Sim Studio is an open-source AI agent workflow builder. Sim Studio's interface is a lightweight, intuitive way to quickly build and deploy LLMs that connect with your favorite tools. https://github.com/simstudioai/sim

https://github.com/prazzon/Flexbox-Labs
https://glyphs-special-characters.netlify.app/

5MB vs 100MB：Neutralinojs如何终结Electron的资源臃肿时代
Neutralinojs vs Electron vs NW.JS vs Tauri vs NodeGui vs Flutter vs .Net MAUI

vuebits 动画

近日，Vue.js、Vite 作者尤雨溪宣 布成立新公司：VoidZero，其旨在解决当前 JavaScript 工具链碎片化、依赖复杂以及性能瓶颈等问题，为开发者提供一个更加流畅和高效的开发体验。。目前，公司已完成 460 万美元（折合人民币 3200 多万） 种子轮融资

https://github.com/QwenLM/qwen-code
boot.dev

基于 Rust 和 React 新一代全栈 Web 框架 Tuono 强势来袭！

https://neutralino.js.org/docs/configuration/modes
https://elysiajs.com/at-glance.html

```
import { Elysia, file } from 'elysia'

new Elysia()
    .get('/', 'Hello Elysia')
    .get('/video', file('kyuukurarin.mp4'))
   	.get('/ip', ({ server, request }) => {
      		return server?.requestIP(request)
	    }) 
    .listen(3000)
```
https://automd.unjs.io AutoMD  Markdown, Automated · Generated with UnDocs and Nuxt UI Pro .
https://nuxt.com/templates
https://github.com/spark?locale=en-US
https://phet.colorado.edu/zh_CN/

Portr 是一款轻量级、安全的本地端口暴露工具，支持 HTTP、TCP、WebSocket，直接把你电脑上的服务用公网地址暴露出来！
	•	📡 支持多种协议（HTTP / TCP / WS）一键转发
	•	🔐 底层用的是 SSH 远程端口转发，安全有保障
	•	🧑‍💻 自带 Web 管理后台，支持多用户 / 多团队操作

https://lap.dev/lapce  https://plugins.lapce.dev/
https://github.com/rxi/lite lite-xl
vue bits  react bits 动画库

上联：张之洞
下联：陶然亭
https://github.com/dremin/RetroBar 
谷歌即将于8月20日正式发布全新Pixel 10系列旗舰手机。距离发布还有不到一个月，关于Pixel 10 Pro和Pixel 10 Pro XL的爆料已陆续浮出水面，其中最引人关注的，是一款全新的“月影灰”配色
https://regexper.com/#%5Cd%5Cs4%2B

以下是为你的软件开发与网站建设公司精心构思的30个新颖别致的名称，结合前沿科技意象、自然哲学隐喻及行业特性，分为六大主题类别，并附命名解析与适用方向：

---

### **一、未来科技感**  
1. **量子棱镜（Quantum Prism）**  
   - *解析*：“量子”代表尖端技术，“棱镜”象征多维度解决方案，寓意公司能分解复杂需求为精准服务。  
   - *适用*：高端定制化开发、跨平台系统集成。  

2. **光年矩阵（LightYear Matrix）**  
   - *解析*：融合“光年”（速度与远见）与“矩阵”（结构化技术），突出高效架构与前瞻视野。  
   - *适用*：大数据、云计算领域企业。  

3. **星际智链（Stellar Chain）**  
   - *解析*：“星际”喻指无限探索，“智链”暗喻AI与区块链技术融合，传递创新与连接价值。  
   - *适用*：去中心化应用、智能合约开发。  

4. **神经脉冲（Neural Pulse）**  
   - *解析*：以生物神经网类比代码网络，强调快速响应与智能交互，契合人机协同趋势。  
   - *适用*：AI驱动型产品开发。  

5. **维度创界（Dimensional Frontier）**  
   - *解析*：“维度”突破物理限制，“创界”象征开拓新领域，适合颠覆性技术团队。  
   - *适用*：元宇宙、VR/AR应用开发。  

---

### **二、自然哲学隐喻**  
1. **熵减科技（Entropy Labs）**  
   - *解析*：物理学中“熵减”意为从混沌到有序，暗喻公司将混乱需求转化为清晰系统。  
   - *适用*：复杂业务流程优化开发。  

2. **光合智码（PhotoCode）**  
   - *解析*：借植物光合作用比喻技术吸收与转化能力，体现可持续创新。  
   - *适用*：绿色能源、环保科技相关数字化服务。  

3. **穹宇互联（Cosmos Link）**  
   - *解析*：“穹宇”象征包容性与扩展性，传递全域连接能力，兼具诗意与科技感。  
   - *适用*：物联网、跨设备生态开发。  

4. **磐石云界（Bedrock Cloud）**  
   - *解析*：融合“磐石”（稳固架构）与“云界”（灵活部署），平衡可靠性与敏捷性。  
   - *适用*：企业级SaaS平台开发。  

5. **潮汐算法（Tidal Algorithms）**  
   - *解析*：以潮汐规律喻指自适应技术，强调动态优化与场景感知能力。  
   - *适用*：实时数据分析、弹性计算服务。  

---

### **三、功能价值导向**  
1. **瞬联科技（FlashConnect）**  
   - *解析*：直指“瞬时连接”，突出低延迟与高响应，适合高性能应用开发。  
   - *适用*：金融科技、实时交易系统。  

2. **无界通程（Boundless Flow）**  
   - *解析*：强调打破技术边界，实现无缝流程贯通，传递一体化解决方案。  
   - *适用*：全栈开发、系统整合服务。  

3. **极简智构（Simplexity）**  
   - *解析*：合成词（Simple+Complexity），寓意化繁为简的智能构建能力。  
   - *适用*：用户体验驱动型产品设计。  

4. **启源引擎（Origin Engine）**  
   - *解析*：“启源”暗喻从零构建，“引擎”象征核心驱动力，突出技术原创性。  
   - *适用*：底层框架开发、技术孵化服务。  

5. **叠乘效应（Multiplicative）**  
   - *解析*：数学术语，强调技术叠加带来的指数级价值增长，吸引商业客户。  
   - *适用*：增长黑客工具、规模化系统开发。  

---

### **四、文化符号创意**  
1. **灵枢网络（LingShu Networks）**  
   - *解析*：借《黄帝内经》“灵枢”概念，喻指系统核心枢纽，融合东方智慧与现代感。  
   - *适用*：医疗健康、文化科技领域。  

2. **罗盘象限（Compass Quadrant）**  
   - *解析*：航海仪器+数学坐标系，象征精准定位与路径规划，突出战略开发能力。  
   - *适用*：行业解决方案定制。  

3. **斐波那契科技（Fibonacci Tech）**  
   - *解析*：以黄金分割数列命名，传递美学与逻辑的平衡，适合设计开发一体化团队。  
   - *适用*：数字产品设计与开发。  

4. **燧石智能（Flint Intelligence）**  
   - *解析*：“燧石”取火工具，隐喻技术点燃创新火花，兼具历史厚重感。  
   - *适用*：教育科技、知识管理平台。  

5. **弦论互动（String Interactive）**  
   - *解析*：物理学“弦理论”暗示底层代码驱动多维交互，吸引科技爱好者。  
   - *适用*：游戏引擎、交互式应用开发。  

---

### **五、短音节强记忆**  
1. **码屿（CodeIsle）**  
   - *解析*：“屿”为水中之岛，象征技术孤岛间的连接枢纽，简洁易记。  
   - *适用*：轻量级工具开发、中间件服务。  

2. **拓界（TuoJie）**  
   - *解析*：中文“开拓边界”，发音铿锵，国际化拼写友好。  
   - *适用*：跨境数字化服务、多语言网站建设。  

3. **棱镜鸟（Prism Bird）**  
   - *解析*：意象组合，“棱镜”折射技术之光，“鸟”象征自由交付，富有传播力。  
   - *适用*：创意营销网站开发。  

4. **矢流（VectorFlow）**  
   - *解析*：数学“矢量”+“流动”，暗示精准导向与动态优化，适合技术博客命名。  
   - *适用*：开发者工具、API服务。  

5. **迭格（IterGrid）**  
   - *解析*：“迭代”+“网格”，浓缩敏捷开发与结构化思维，域名稀缺性强。  
   - *适用*：快速原型设计、MVP开发。  

---

### **六、国际化开放语感**  
1. **Aurora Labs（极光实验室）**  
   - *解析*：极光象征绚丽技术与自然奇迹，易激发全球用户共鸣。  
   - *适用*：跨境团队、开源项目社区。  

2. **Kairo Tech（凯罗科技）**  
   - *解析*：希腊语“Kairos”（决定性时机），传递技术变革的关键力量，发音国际化。  
   - *适用*：战略咨询+技术实施服务。  

3. **Vega Dynamics（织女星动力）**  
   - *解析*：织女星为天琴座主星，寓意技术引领方向，天文意象打破文化隔阂。  
   - *适用*：航空航天、高精度计算领域。  

---

### **命名注意事项**  
1. **法律风险**：需核查商标与域名可用性（推荐工具：Namechk、Trademarkia）。  
2. **发音测试**：多语言场景下朗读，避免歧义（如“西诺”英文易读

Beekeeper Studio    Navicat    DBeaver  
https://qwerty.kaiyi.cool 
https://libretranslate.com/ 

$ pip install libretranslate
$ libretranslate
$ curl -X POST http://localhost:5000/translate -d q="Hello" -d source=en -d target=es
https://github.com/LibreTranslate/LibreTranslate

https://github.com/streamlit/streamlit
fuzpad
7999元的三款5070Ti游戏本推荐✨ 机械革命蛟龙16Pro、旷世XPro、极光XPro，这三款游戏本在CPU、性能释放等方面各有不同，而屏幕、内存配置较为相近，它们均为游戏利器。

畅连啦！华为开发者空间云开发环境惊喜上线
https://docsify.js.org/#/write-a-plugin
https://docsify-this.net/?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-this-one-page-article/main&homepage=home.md&sidebar=true&maxLevel=3
https://github.com/docsify-note/docsify-giscus/tree/main

根据最新的Geekbench OpenCL跑分数据，以及砺算科技内部人士的透露，中国首款自研高端游戏GPU——砺算G100，这款备受期待的国产GPU，其性能已经可以对标甚至超越NVIDIA的主流甜品卡RTX 4060，并紧追最新的RTX 5060！

https://marked.js.org/demo/?text=Marked%20-%20Markdown%20Parser%0A&version=16.1.1
https://marked.js.org/contributing

marked: marked is designed to be minimal and does not offer extensive customization options. It focuses on speed and simplicity, which may limit its extensibility compared to other libraries.
markdown-it: markdown-it provides a rich plugin architecture that allows developers to extend its functionality easily. You can create custom rules, add new syntax, or modify existing behavior, making it highly adaptable to specific needs.
remark: remark is built around a plugin system that enables developers to create custom transformations and linting rules. This modular approach allows for extensive customization and integration of various Markdown processing tasks.
showdown: showdown offers basic customization through options but lacks a robust plugin system. It allows some configuration of the conversion process, but it is not as extensible as markdown-it or remark.

https://markdown-it.github.io/

"Generated with bashblog, a single bash script to easily create blogs like this one"

中国SMEE光刻机，昆山

小米自研系统MIOS最早是在去年11月曝光的，当时小米备案了名为mios的网站域名，目前在工信部是可以查到的

copyparty
一款基于 Python 开发的多功能文件服务，所有功能集成在单个 Python 文件，零依赖、仅需一条命令即可启动。通过浏览器即可完成文件浏览、上传、下载、在线播放等操作，并支持多线程加速上传、断点续传和文件去重等功能。除了网页访问，还兼容 WebDAV、FTP、TFTP 等多种文件传输协议。
github.com/9001/copyparty

专为终端环境打造的 AI 智能编码助手，可灵活切换或混合调用多种模型。它完全开源、开箱即用，支持 Anthropic、OpenAI、Google 和离线本地模型。
github.com/sst/opencode

1.5 让 Claude Code 连接任意大模型的工具：claude-code-router

https://wan.video/explore

https://github.com/toss/es-toolkit
https://es-toolkit.dev/compatibility.html
https://github.com/exceljs/exceljs

一个安全、稳定、高性能的内网穿透工具，用 Rust 语言编写
核心优势在于低资源消耗、TLS传输加密、高吞吐量
与frp的性能对比，有较大的提升
开源地址参考：https://github.com/rathole-org/rathole

https://nuxt.com  快试试 Nuxt 4 吧！

最新上线的豆包 SeedEdit 3.0 图像编辑模型。
说它能让你彻底和 PS 告别，真不是夸张。

一家名为Bolt Graphics的初创公司突然杀入战场。该公司宣布其革命性产品Zeus（宙斯）GPU将于2026年向开发者提供开发套件，并计划在2027年大规模上市。这个Zeus（宙斯）GPU似乎是显卡市场上一个匹新生黑马，今年3月份的GTC大会上这间Bolt Graphics公司就对外展示了这款名为Zeus宙斯的GPU，号称10倍于RTX 5090性能，简直就是一鸣惊人。

SuperDesign is the first open-source design agent that lives right inside your IDE.
Generate UI mockups, components, and wireframes directly from natural language prompts.
Works seamlessly with Cursor, Windsurf, Claude Code, and plain VS Code.

FLTK is a cross-platform C++ GUI toolkit for UNIX®/Linux® (X11 and Wayland), Microsoft® Windows®, and macOS®. FLTK provides modern GUI functionality without the bloat and supports 3D graphics via OpenGL® and its built-in GLUT emulation.
FLTK is designed to be small and modular enough to be statically linked, but works fine as a shared library. FLTK also includes an excellent UI builder called FLUID that can be used to create applications in minutes.

https://www.doxygen.nl/examples.html  https://www.paypal.com/donate?token=_xdObOHi-Q9TgmA5ZNYde3HATi-26ZX_1_tqxoh6r86TssCnT4zedbnMRL1e3NcD2IcKxLsvJ_zAJ0LB&locale.x=US

Instantly create a Remote MCP server for any GitHub repository
Simply change the domain from github.com or github.io to gitmcp.io and get instant AI context for any GitHub repository.

cursor cli
普林斯顿数学指南

https://github.com/rathole-org/rathole
A lightweight and high-performance reverse proxy for NAT traversal, written in Rust. An alternative to frp and ngrok.

    https://ollama.com/search
https://ollama.com/library/gemma3
https://v0.app/
https://github.com/leigest519/ScreenCoder。

抛物线：截面仅与圆锥面的一条母线平行，结果为抛物线。

https://reference.wolfram.com/language/guide/MatrixDecompositions.html
parabola
美 [pəˈræbələ]
英 [pə'ræbələ]
n.抛物线
quest
美 [kwest]
英 [kwest]
v.探索；探求
n.探索
网络贵士；寻求；寻找

1. **饮食**：每日500g多彩蔬菜+200g低糖水果+豆类/坚果，每周2次深海鱼。  
2. **运动**：每周150分钟有氧（快走/游泳）+2次抗阻训练。  
3. **睡眠**：保证7-8小时深度睡眠（22:00-6:00最佳）。  
4. **压力管理**：每日10分钟冥想（降低皮质醇30%）。  
5. **定期检测**：40岁后监控炎症标志物（CRP）、端粒长度等。

以下是主要数学术语的英语-中文对照表（含音标、词源解析及定义），按学科分类整理，便于同步学习：

---

### **几何学（Geometry）**
| **英文术语**       | **音标**          | **中文** | **词源解析**               | **定义**                          |
|--------------------|-------------------|----------|---------------------------|----------------------------------|
| **Parabola**       | /pəˈræbələ/       | 抛物线   | 希腊语 *parabolē* (类比)   | 到焦点与准线距离相等的点的轨迹    |
| **Hyperbola**      | /haɪˈpɜːrbələ/    | 双曲线   | 希腊语 *hyperbolē* (超越)  | 两焦点距离差为定值的点的轨迹      |
| **Ellipse**        | /ɪˈlɪps/          | 椭圆     | 希腊语 *elleipsis* (缺失)  | 两焦点距离和为定值的点的轨迹      |
| **Polygon**        | /ˈpɒlɪɡɒn/        | 多边形   | *poly-* (多) + *gon* (角) | 三条或以上线段围成的封闭图形      |
| **Hypotenuse**     | /haɪˈpɒtənjuːz/   | 斜边     | 希腊语 *hypoteinousa* (下方伸展) | 直角三角形直角对边              |

---

### **代数（Algebra）**
| **Term**           | **音标**          | **中文** | **词源解析**               | **定义**                          |
|--------------------|-------------------|----------|---------------------------|----------------------------------|
| **Coefficient**    | /ˌkoʊɪˈfɪʃənt/    | 系数     | 拉丁语 *co-* (共同) + *efficere* (作用) | 变量前的数值乘数 (如 3x 中的 3) |
| **Exponent**       | /ɪkˈspoʊnənt/     | 指数     | 拉丁语 *exponere* (展示)   | 表示底数乘方次数的数 (如 xⁿ 中的 n) |
| **Polynomial**     | /ˌpɒlɪˈnoʊmiəl/   | 多项式   | *poly-* (多) + *nomen* (项) | 由多个单项式相加组成的表达式      |
| **Inequality**     | /ˌɪnɪˈkwɒləti/    | 不等式   | *in-* (非) + *aequus* (相等) | 表示两个表达式不等关系的数学式    |
| **Quadratic**      | /kwɒˈdrætɪk/      | 二次的   | 拉丁语 *quadratus* (平方)  | 最高次数为 2 的方程/函数 (如 ax²+bx+c) |

---

### **微积分（Calculus）**
| **Term**           | **音标**          | **中文** | **词源解析**               | **定义**                          |
|--------------------|-------------------|----------|---------------------------|----------------------------------|
| **Derivative**     | /dɪˈrɪvətɪv/      | 导数     | 拉丁语 *derivare* (导出)   | 函数变化率的极限（瞬时斜率）      |
| **Integral**       | /ˈɪntɪɡrəl/       | 积分     | 拉丁语 *integer* (完整)    | 求函数曲线下面积的运算            |
| **Limit**          | /ˈlɪmɪt/          | 极限     | 拉丁语 *limes* (边界)      | 函数趋近于某个值的无限接近状态    |
| **Asymptote**      | /ˈæsɪmptoʊt/      | 渐近线   | 希腊语 *asymptōtos* (不相遇) | 曲线无限逼近但永不相交的直线      |

---

### **线性代数（Linear Algebra）**
| **Term**           | **音标**          | **中文** | **词源解析**               | **定义**                          |
|--------------------|-------------------|----------|---------------------------|----------------------------------|
| **Vector**         | /ˈvektər/         | 向量     | 拉丁语 *vehere* (携带)     | 具有大小和方向的量（如力/速度）    |
| **Matrix**         | /ˈmeɪtrɪks/       | 矩阵     | 拉丁语 *mater* (母体)      | 数字按行列排列的矩形阵列          |
| **Determinant**    | /dɪˈtɜːrmɪnənt/   | 行列式   | 拉丁语 *determinare* (限定) | 方阵对应的标量值（判断可逆性）    |
| **Eigenvalue**     | /ˈaɪɡənˌvæljuː/   | 特征值   | 德语 *eigen* (自身的)      | 线性变换中不改变方向的缩放因子    |

---

### **概率与统计（Probability & Statistics）**
| **Term**             | **音标**              | **中文**   | **词源解析**               | **定义**                          |
|----------------------|-----------------------|------------|---------------------------|----------------------------------|
| **Standard Deviation** | /ˈstændərd ˌdiːviˈeɪʃən/ | 标准差     | 拉丁语 *deviare* (偏离)    | 数据偏离平均值的离散程度度量      |
| **Percentile**       | /pərˈsentʌɪl/         | 百分位数   | *per centum* (每百)        | 数据集中低于某值的比例位置        |
| **Correlation**      | /ˌkɒrəˈleɪʃən/        | 相关性     | *co-* (共同) + *relatio* (关系) | 两个变量间的统计关联程度          |

---

### **运算符号（Operations）**
| **符号/术语**    | **英文读法**       | **中文** | **定义**                  |
|------------------|-------------------|----------|--------------------------|
| **∑**            | Sigma / Summation | 求和符号 | 表示数列的累加 (∑aᵢ)      |
| **∫**            | Integral          | 积分符号 | 表示函数的不定积分/定积分 |
| **√**            | Square Root       | 平方根   | 求非负实数的平方根 (√9=3) |
| **x̄**            | x-bar             | 样本均值 | 统计中样本的平均值        |
| **∝**            | Proportional to   | 正比于   | 表示两个量的比例关系 (y∝x) |

---

### **学习建议：**
1. **词根记忆法**：  
   - *poly-* (多), *tri-* (三), *quad-* (四) 等前缀帮助理解多边形术语  
   - *-gon* (角), *-hedron* (面体) 等后缀区分几何体类型  

2. **对比学习**：  
   ```markdown
   - **Ellipse** (椭圆) vs. **Eclipse** (日食)  // 同源词不同义
   - **Vertex** (顶点) vs. **Vortex** (漩涡)  // 形近词区分
   ```

3. **语境应用**：  
   > "The **derivative** of a quadratic function yields its **gradient** at any point on the **parabola**."  
   > (二次函数的**导数**给出了**抛物线**上任意点的**斜率**)

> 附：**数学分支术语表**  
> | **英文**          | **中文**      |  
> |-------------------|--------------|  
> | Topology          | 拓扑学        |  
> | Trigonometry      | 三角学        |  
> | Combinatorics     | 组合数学      |  
> | Number Theory     | 数论          |  
> | Differential Equations | 微分方程  |

可根据需求扩展特定领域的术语深度解析（如群论/拓扑学/离散数学等）。

https://fastcopy.jp/  FastCopy是Windows上最快的复制/备份软件
社工查询
天眼查：https://www.tianyancha.com/
信用查询：http://www.creditchina.gov.cn/
电话邦：http://www.dianhua.cn/
MD5解密：http://www.xmd5.org/
网站域名查询：http://www.beianbeian.com/

 SmartSniff - 抓包工具
wj.qq.com  腾讯问卷  MusicBee - 音樂播放器

Mongoose - 輕量級 WebServer https://github.com/cesanta/mongoose
把這個僅有 400 KB 的程序放在你的靜態網頁目錄，運行后就有一個簡單實用的 WebServer 了。Easy to integrate: just copy mongoose.c and mongoose.h files to your source tree

https://mongoose.ws/documentation/tutorials/tools/  Build tools#
The following instructions guide on setting up a development environment for building and running Mongoose Library examples, as well as developing new applications. 

https://github.com/sapics/ip-location-db
https://www.nirsoft.net/network_tools.html

RunAsDate	RunAsDate is a small utility that allows you to run a program in the date and time that you specify. This utility doesn't change the current system date and time of your computer, but it only injects the date/time that you specify into the desired application. You can run multiple applications simultaneously, each application works with different date and time, while the real date/time of your system continues to run normally.

If you ever need to download an entire Web site, perhaps for off-line viewing, wget can do the job—for example:

$ wget \
     --recursive \
     --no-clobber \
     --page-requisites \
     --html-extension \
     --convert-links \
     --restrict-file-names=windows \
     --domains website.org \
     --no-parent \
         www.website.org/tutorials/html/
This command downloads the Web site www.website.org/tutorials/html/.

The options are:

--recursive: download the entire Web site.

--domains website.org: don't follow links outside website.org.

--no-parent: don't follow links outside the directory tutorials/html/.

--page-requisites: get all the elements that compose the page (images, CSS and so on).

--html-extension: save files with the .html extension.

--convert-links: convert links so that they work locally, off-line.

--restrict-file-names=windows: modify filenames so that they will work in Windows as well.

--no-clobber: don't overwrite any existing files (used in case the download is interrupted and resumed).

Texmaker is a free, modern and cross-platform LaTeX editor for linux, macosx and windows systems that integrates many tools needed to develop documents with LaTeX, in just one application.

CamStudio - 屏幕錄像  後來開始做直播后就直接用 OBS 錄像了  
Scrivener - 文學創作編輯軟件  AudioScore - 音樂逆向

Popcorn Time - 影視 BT 搜索、邊下邊播

LICEcap 能選中屏幕的一塊區域進行錄像，然後生成能夠直接嵌入在網頁中的 Gif 動圖。

gpt-5-coding-examples codex

edgeone pages mcp

https://pan.quark.cn/s/ad6a9e48fe00

文颜是一个免费开源的全自动文章排版美化工具，能够将 Markdown 格式的文章一键转换为适合公众号、知乎、今日头条、掘金等平台的排版格式，它无需用户进行繁琐调整，软件会针对不同平台自动识别、并适配每个平台的排版特点进行文字排版。
墨探
https://babyno.top/posts/2025/06/wenyan-mcp-server-released/
轻松将 Html 网页内容（博客、新闻、文档等）转换为 Markdown 格式

FFmpeg - 多媒体处理框架，音视频转换瑞士军刀，https://ffmpeg.org/

WireGuard - 现代VPN协议，简单快速安全，https://www.wireguard.com/

Mathpix - AI数学公式识别工具，可将手写或图片公式转为LaTeX，https://mathpix.com/

ASCII Art Generator - ASCII艺术字生成器，文本转ASCII图形，https://www.asciiart.eu/text-to-ascii-art
Color Picker - 颜色选择和调色板工具，设计配色助手，https://htmlcolorcodes.com/color-picker/
Favicon Generator - 网站图标生成器，多尺寸favicon制作，https://favicon.io/
Password Generator - 密码生成器，创建强密码保护账户，https://passwordsgenerator.net/

目前 Pika 1.0 支持文生视频、图生视频、视频生视频三种方式。
https://cn.bing.com/dict/search?q=Nautilus&FORM=HDRSC6

Introducing Rovo Dev CLI: AI-Powered Development in your terminal 竟然新增了 GPT-5，由原来的每天 20M Tokens 变为每天 5M Tokens～Rovo Dev is an AI agent built by Atlassian for software developers, and is now available for use directly in your terminal via the Command Line Interface (CLI)

pgAdmin 4 is a complete rewrite of pgAdmin, built using Python, ReactJs, and Javascript. A desktop runtime written in Electron allows it to run standalone for individual users, or the web application code may be deployed directly on a web server for use by one or more users through their web browser. The software has the look and feel of a desktop application whatever the runtime environment is, and vastly improves on pgAdmin III with updated user interface elements, multi-user/web deployment options, dashboards, and a more modern design.  pgAgent is a job scheduler for PostgreSQL which may be managed using pgAdmin


​​使用方式
​1. 需提前安装好 Gemini CLI  
1. 在 VS Code 扩展商店安装「Gemini CLI Companion」  
2. 在 CLI 输入 /ide install → /ide enable 
3. 开始畅玩~  

Copilot 3D
单击一下即可将图像转换为 3D 模型。https://copilot.microsoft.com/labs/experiments/3d-generations

英国科学家成功创造出迄今为止基因密码最为精简的人工生命形式，这一突破性成就标志着合成生物学领域的重大里程碑。这种被命名为Syn57的合成大肠杆菌仅使用57个密码子构建其生命体，而自然界中所有已知生物都依赖64个密码子系统运行了数十亿年

Geoffrey Copin的技术博客，里面有一些成系列的rust教程

聚星小星带你 python 入门

https://www.youtube.com/c/piximperfect Piximperfect 是全球公认的最好的PS教程频道，主讲人Unmesh Dinda讲得极其清晰透彻，尤其适合想深入理解原理的人。

IP Messenger for Win v5.7.3
 Serverless lightweight Messenger for LAN.
No cloud, Secure & High availability

FastCopy ver 5.10.0  Windows上最快的复制/备份软件  

https://github.com/langgptai/wonderful-prompts  
https://htmx.org/examples/  

在 10 分钟内“掌握” Vue 3 是不可能的，但是可以在 10 分钟内了解 Vue 3 的核心概念和最基本的使用方法，让你对它有个初步印象。以下是一个快速入门指南：

1. 准备工作 (1 分钟):

*   在线环境: 使用 CodePen、JSFiddle 或 StackBlitz 等在线代码编辑器。这些工具无需安装任何东西，直接在浏览器中运行。
*   引入 Vue 3: 在 HTML 中引入 Vue 3 的 CDN 链接。在 CodePen 中，你可以在 "Settings" -> "JavaScript" 中添加 CDN 链接。 推荐使用 unpkg:

html     <script src="https://unpkg.com/vue@3/dist/vue.global.js"></script>     

2. 创建 Vue 应用实例 (2 分钟):

html <div id="app">   <h1>{{ message }}</h1> </div>  <script>   const { createApp } = Vue    createApp({     data() {       return {         message: 'Hello Vue 3!'       }     }   }).mount('#app') </script> 

*   createApp():  Vue 3 的核心函数，用于创建 Vue 应用实例。
*   data():  一个函数，返回一个包含组件数据的对象。  message 是一个数据属性。
*   {{ message }}:  双花括号语法，用于在 HTML 中插入数据。  Vue 会自动跟踪 message 的变化并更新视图。
*   mount('#app'):  将 Vue 应用挂载到 HTML 元素上。 #app 是 HTML 元素的 ID。

3.  使用指令 (3 分钟):

```vue
<div id="app">
    <h1>{{ message }}</h1>
    <p v-if="show">This is visible!</p>
    <ul>
        <li v -for="item in items" : key="item.id"> {{ item.text }}</li>
    </ul> <button @click="changeMessage"> Change Message < /button>
</div>
<script>const { createApp } = Vue    createApp({ data() { return { message: 'Hello Vue 3!', show: true, items: [{ id: 1, text: 'Item 1' }, { id: 2, text: 'Item 2' }] } }, methods: { changeMessage() { this.message = 'Message Changed!' } } }).mount('#app') </script>
<div id="app">
    <h1>{{ message }}</h1>
    <p v-if="show">This is visible!</p>
    <ul>
        <li v-for="item in items" :key="item.id">{{ item.text }}</li>
    </ul>
    <button @click="changeMessage">Change Message</button>
</div>
<script>const { createApp } = Vue    createApp({ data() { return { message: 'Hello Vue 3!', show: true, items: [{ id: 1, text: 'Item 1' }, { id: 2, text: 'Item 2' }] } }, methods: { changeMessage() { this.message = 'Message Changed!' } } }).mount('#app') </script>
```

*   v-if:  条件渲染指令。  只有当 show 为 true 时，才会显示 `<p>` 元素。
*   v-for:  循环渲染指令。  遍历 items 数组，为每个 item 创建一个 `<li>` 元素。
*   :key:  v-for 需要的 key 属性，用于提高性能。  通常使用唯一 ID 作为 key。
*   @click:  事件监听指令。  当点击按钮时，会调用 changeMessage 方法。
*   methods:  一个对象，包含组件的方法。  changeMessage 方法会修改 message 数据属性。

4. 理解响应式 (2 分钟):

Vue 3 的核心是响应式系统。 当数据发生变化时，视图会自动更新。 你不需要手动操作 DOM。  在上面的例子中，当你点击按钮时，message 的值会改变，Vue 会自动更新 `<h1>` 元素的内容。

5.  组合式 API 简介 (2 分钟):

虽然上面的例子使用了选项式 API (Options API)，但 Vue 3 引入了组合式 API (Composition API)，它提供了一种更灵活和可组合的代码组织方式。  下面是一个简单的例子，展示了如何使用 ref 和 reactive：

```
<div id="app">
   <h1>{{ count }}</h1>
      <button @click="increment">Increment</button>
</div>
<script>
import { createApp, ref } from 'vue'
createApp({ setup() { const count = ref(0)        const increment = () => { count.value++ }        return { count, increment } } }).mount('#app') 
</script>
```

*   setup():  组合式 API 的入口点。  在这里定义数据和方法。
*   ref():  创建一个响应式的引用。  count.value 用于访问和修改 count 的值.
*   reactive():  创建一个响应式的对象。 (未在此示例中使用，但经常与 ref() 一起使用)
*   return:  setup() 函数必须返回一个对象，包含要在模板中使用的属性和方法。

重要提示:

*   这只是一个非常简单的介绍。 要真正掌握 Vue 3，你需要花更多的时间学习文档、练习编写代码和构建项目。
*   关注 Vue 3 的官方文档 (https://vuejs.org/)。 它是学习 Vue 3 的最佳资源。
*   组合式 API 是 Vue 3 的一个重要特性，建议你花时间学习它。
*   尝试构建一些简单的项目，例如待办事项列表或计数器，以巩固你的知识。

总结:

在 10 分钟内，你了解了 Vue 3 的核心概念，包括创建应用实例、使用指令、理解响应式和组合式 API 的基本用法。  继续学习和实践，你将能够掌握 Vue 3 并构建强大的 Web 应用。 祝你学习愉快！


> 今天，微软 Excel 迎来了一个重磅更新，在 Windows 和 Mac 版本中正式推出了备受期待的 Copilot函数。

```
irm https://static.cloudbase.net/cli/install/install.ps1 | iex
如果访问官方 npm 源有问题，一般安装过程中报类似 "ETIMEOUT"、"npm ERR! network request to https://registry.npmjs.org/@cloudbase%2fcli failed" 这种错误，这个时候需要临时指定一个国内 npm 镜像源：

npm i -g @cloudbase/cli --registry=http://mirrors.cloud.tencent.com/npm/

yarn global add @cloudbase/cli --registry=http://mirrors.cloud.tencent.com/npm/

tcb ai

# 或预设提示词
tcb ai -- "帮我创建一个订单管理系统"

# 或使用非交互式模式
tcb ai -- -p "你好"

# 查看所有可用命令
tcb ai --help
```

https://lovable.dev/  https://github.com/firecrawl/open-lovable


​华裔数学家 张益唐（Yitang Zhang）近日宣布，已于 2025 年 6 月从美国加州大学圣塔芭芭拉分校回国，到中国中山大学香港高等研究院就任全职教授 (南华早报,)。在接受凤凰卫视采访时，他坦言国际局势和中美关系紧张是促使他回国的重要原因之一。张益唐表示：“考虑到最近国际政治问题对中美关系带来的紧张，我决定回到大陆。”他还称其实数学领域不直接受影响，但提醒从事计算机、芯片或与军事相关领域的研究者需要格外谨慎 (南华早报)。他的回归被视为中国吸引海外顶尖学术人才的一个积极趋势。

https://github.com/budtmo/docker-android

mars3D
https://design.penpot.app/ 开源figma平替
https://market.yandex.ru/

github.com/winapps-org/winapps
Star增长： 日增近700！ 一夜爆火！
一句话概括： 让你在Linux系统里，像运行原生程序一样使用微软Office、Adobe等Windows应用。

Puck (puckeditor/puck)：React开发者的福音！一个开源的可视化编辑器，拖拽就能生成React页面，日增400+星，解放前端生产力。
Drawnix (plait-board/drawnix)：开源白板天花板？集成了思维导图、流程图、手绘功能，对标Miro，关键还免费，可自部署。

https://iseeue.com/book/29812490/0edd7d 电子书

https://github.com/KucoDEV/TKinter-Designer

qwen-image-edit bytebot folo qoder
【FFmpeg v8.0 "Huffman" 正式发布

shutdown /r /fw /t 0
系统会立即重启，并自动进入 UEFI/BIOS 设置界面，无需再按任何按键。
超大显存的AMD锐龙AI Max+395 实力赋能各大场景，对于这几款软件，还有什么想了解的？评论区唠唠~！

dnGrep 是一款基于 .NET 开源、功能强大的 Windows 搜索工具，它支持在多个文件中进行搜索，并以易于阅读的结果呈现。你可以通过文本、正则表达式、XPath 和语音查询搜索文本文件、Word 和 Excel 文档、PDF 文件以及存档文件中进行搜索。dnGrep 还提供了搜索和替换、整文件预览、在文件资源管理器中右键搜索等更多功能。

https://github.com/winapps-org/winapps
https://github.com/microsoft/microsoft-ui-xaml
Google nano banana
https://github.com/leigest519/ScreenCoder
https://china-ranking.32k.site
第一名：科威特第纳尔
科威特凭借着得天独厚的石油资源，其储量在全球名列前茅，石油出口宛如一台台印钞机，源源不断地为国家带来巨额财富。国内经济一片繁荣，民众享受着高福利生活，从免费的教育、医疗到住房补贴等，方方面面都彰显着石油经济的雄厚实力。

在国际外汇市场上，科威特第纳尔与美元的兑换汇率长期居高不下，使得它成为全球投资者眼中最具价值的货币之一，也当之无愧地稳坐最贵货币的头把交椅。1 科威特第纳尔等于 23.7916937054 人民币。

https://ollama.com/  curl -fsSL https://ollama.com/install.sh | sh

- firecracker：Rust编写的轻量级虚拟机，专为无服务器计算设计，今日新增104星
- nn-zero-to-hero：Karpathy的神经网络入门教程，今日新增399星，适合AI初学者
- genai-toolkit：谷歌开源的数据库MCP服务器工具包，今日新增121星

Wine （“Wine Is Not an Emulator” 的首字母缩写）是一个能够在多种 POSIX-compliant 操作系统（诸如 Linux，macOS 及 BSD 等）上运行 Windows 应用的兼容层。Wine 不是像虚拟机或者模拟器一样模仿内部的 Windows 逻辑，而是將 Windows API 调用翻译成为动态的 POSIX 调用，免除了性能和其他一些行为的内存占用，让你能够干净地集合 Windows 应用到你的桌面。
 
https://claude.ai/public/artifacts/
https://claude.ai/chat/5e1abf51-814f-4fc5-a6a9-5ef54fa68031

pip install poml

For development or local installation, you might use pip install -e . from a cloned repository.

https://code.visualstudio.com/docs/copilot/getting-started

Install PySimpleGUI:

python -m pip install pysimplegui

Download main.py, which contains:

```
import PySimpleGUI as sg

# All the stuff inside your window.
layout = [  [sg.Text("What's your name?")],
            [sg.InputText()],
            [sg.Button('Ok'), sg.Button('Cancel')] ]

# Create the Window
window = sg.Window('Hello Example', layout)

# Event Loop to process "events" and get the "values" of the inputs
while True:
    event, values = window.read()

    # if user closes window or clicks cancel
    if event == sg.WIN_CLOSED or event == 'Cancel':
        break

    print('Hello', values[0], '!')

window.close()
```
Run:

python main.py

C++：Unreal Engine 5.3通过C++20协程特性将编译时间缩短35%，特斯拉Autopilot底层通信模块依赖C++实现纳秒级延迟控制。

Perl：垂直领域的隐形冠军与未来突围
Perl语言特点：
①生物信息学的基石：加州大学伯克利分校的研究显示，86%的基因组注释工具依赖Perl开发。例如，处理GFF格式文件时，Perl通过split函数和数组解构，可高效提取基因信息：在FASTA格式处理中，Perl的正则表达式和字符串处理功能可轻松实现序列提取。

②垂直领域不可替代性：生物信息学中，Perl处理GFF/FASTA文件的效率较Python高40%；系统管理领域，Perl脚本无需编译，适合快速开发临时工具。

③生态成熟度：CPAN仓库拥有18万+模块，涵盖文本处理、网络编程、生物信息学等场景。BioPerl模块支持基因组序列拼接、比对及统计分析全流程。

④轻量级特性：30行Perl代码可实现JVM端口监控，较Java方案代码量减少70%；Docker官方Perl镜像体积仅120MB，支持单文件部署。

根据TIOBE指数，Perl以2.08%的占比位列第九，同比上升1.17%，成为榜单中上升幅度最大的语言。尽管整体排名不及Python、C++等主流语言，但在生物信息学、系统管理等垂直领域，Perl仍保持着不可替代的地位。

stitch.withgoogle.com

huawei MatePad Mini 8.8

https://gitee.com/wubh/InstallWindowService  使用 WinForm 开发，提供图形化界面安装 windows 服务
NSSM - the Non-Sucking Service Manager
https://github.com/mlabonne/llm-course

Posting can be installed via uv on MacOS, Linux, and Windows.

# quickly install uv on MacOS/Linux
curl -LsSf https://astral.sh/uv/install.sh | sh

# install Posting (will also quickly install Python 3.13 if needed)
uv tool install --python 3.13 posting
Now you can run Posting via the command line:

posting

Linus Torvalds 一句“合入主线”的邮件，瞬间点燃整个内核圈。
​2025，腾讯 Kairui Song 用 9 个补丁把 swap 拆骨重塑，性能飙到 20%，ARM 与 x86 同时点头。
​Swap 三十年没大改，碎片、锁、cache 三层打架。
​Swap Table 一招“三合一”，把 cache、映射、分配器塞进一张表，页框地址直接定位，锁粒度减半，碎片率降四成。

​开发者Victor Taelin用OpenAI的Codex+GPT-5-high，把Rust版HVM重写得又快又稳。
​GitHub上427个Fork、1.1万星，GPU跑起来像开挂。
​三天里，AI写了99%的代码，人只修1%。

Linker是一个基于 .NET 8 开源免费（遵循 GPL-2.0 许可证）的跨平台高性能异地组网和内网穿透工具。它通过创新的网络通信技术，支持 TCP（包括 IPV6）打洞、UDP 打洞以及服务器中继等多种方式，实现了在不同地理位置的设备之间建立高效、安全的网络连接。Linker 利用虚拟网卡技术，能够将分散在各地的客户端组建为一个虚拟的局域网络，支持点对点、点对网、网对网等多种组网模式，极大地扩展了网络应用的灵活性和便捷性。

谷歌的Ironwood TPU可扩展到9216个芯片，共享内存达到创纪录的1.77PB，双芯片架构每芯片提供4614个TFLOP FP8和192GB HBM3e。
   该芯片于2025年4月在Google Cloud Next 25上首次亮相，是该公司首款主要用于大规模推理工作负载而非训练的TPU，并作为第七代TPU硬件推出。
    每个Ironwood芯片集成了两个计算芯片，提供4614 TFLOP的FP8性能，八个HBM3e堆栈为每个芯片提供192GB的内存容量，带宽为7.3TB
    
https://open-lovable.com/chat/vccxcsmf8zpbod

https://www.ethicalads.io/advertisers/topics/backend-web/?ref=ea-image

https://certbot.eff.org/hosting_providers

https://acode.app

TL;DR – Best Workflow Automation Software by Use Case

FuseBase – Best for service teams needing client-facing workflows, document automation, and branded portals
Zapier – Best for non-technical teams connecting SaaS tools with simple cross-app automations
Make (Integromat) – Best for technical teams building advanced, multi-branch automations with APIs
Kissflow – Best for enterprise departments (HR, finance, IT, procurement) with compliance-driven processes
Monday.com – Best for creative and cross-functional teams managing visual projects with light automation

Link (stylised as LINK) is the UK’s main ATM network, which allows consumers to withdraw cash from ATMs which do not belong to their bank. It is the largest interbank network in United Kingdom. It is a not-for profit organisation and is regulated by the Bank of England, Financial Conduct Authority and Payment Systems Regulator.

A product from PythonAnywhere LLP
UK VAT No.: 893564379
EU VAT No.: EU372015865
Registered in England and Wales as company number OC378414.
Registered address: 5 The Green, Richmond, TW9 1PL, UK

npx degit sveltejs/template moz-todo-svelte
cd moz-todo-svelte
npm install
npm run dev
备注： 不用太惊讶 degit 做了这么多事情——它其实就只是让你可以从 git 仓库下载和解压缩最新版本的内容。使用它比起使用 git clone 要快得多，因为它并不会下载整个仓库的历史记录，也不会创建完整的本地克隆。

https://www.browseract.com/?ref=huntscreens.com

TrayChrome托盘浏览器是一款轻量级浏览器，专为Windows设计，体积小，功能简单，适合快速浏览和多任务处理。轻量级设计：TrayChrome体积仅2.45M，功能丰富，适合日常浏览。操作便捷：采用手机视图，底部栏有快捷工具，可快速指定操作。功能扩展：支持将常用网址添加到收藏夹

figdraw

https://codeforces.com/blog/entry/132771
https://js.cytoscape.org/