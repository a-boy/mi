## 2020

金属镓滴上一滴使其它金属石块等变得脆碎

马云在杭州开的的sky zoo智能宾馆

洛杉矶的玻璃滑梯


拖动房车外挂 吊床支架

Boxstarter leverages Chocolatey packages to automate the installation of software and create repeatable, scripted Windows environments. Chocolatey makes installing software very easy with no user intervention. 

https://chocolatey.org/ 

Set-ExecutionPolicy Bypass -Scope Process -Force; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))

iwr https://chocolatey.org/install.ps1 -UseBasicParsing | iex

package {['virustotaluploader', 'googlechrome', 'notepadplusplus', '7zip', 'ruby', 'charles', 'grepwin', 'stexbar', 'inkscape', 'gitextensions', 'pandoc', 'snagit', 'nodejs', ]: ensure => latest, source => 'https://chocolatey.org/api/v2/', }


@powershell -NoProfile -ExecutionPolicy Bypass -Command "[System.Net.WebRequest]::DefaultWebProxy.Credentials = [System.Net.CredentialCache]::DefaultCredentials; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))" && SET PATH="%PATH%;%ALLUSERSPROFILE%\chocolatey\bin"

Chocolatey Software, Inc.

6021 SW 29th St

Suite A #302

Topeka, KS 66614

Add us to your address book

package {'screentogif': ensure => '2.2.160907', source => 'https://chocolatey.org/api/v2/', } package {'dotnet4.5.2': ensure => latest, }


Hotkeys are sometimes referred to as shortcut keys because of their ability to easily trigger an action (such as launching a program or keyboard macro). In the following example, the hotkey Win+N is configured to launch Notepad. The pound sign [#] stands for the Win key, which is known as a modifier:

#n::
Run Notepad
return
In the final line above, return serves to finish the hotkey. However, if a hotkey needs to execute only a single line, that line can be listed to the right of the double-colon. In other words, the return is implicit:

#n::Run Notepad
To use more than one modifier with a hotkey, list them consecutively (the order does not matter). The following example uses ^!s to indicate Control+Alt+S:

^!s::
Send Sincerely,{enter}John Smith  ; This line sends keystrokes to the active (foremost) window.
return

Replace Notepad

If you want to replace the Windows NotePad with BowPad, you can do that by modifying the registry:

Start regedit.exe

go to HKLM\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Image File Execution Options and create a new key named notepad.exe

under the notepad.exe key, create a new string value named Debugger and set the value to "c:\program files\BowPad\BowPad.exe" /z

翻译工具:

Poedit
Virtaal
https://github.com/translate/virtaal Easy-to-use and powerful offline translation tool http://virtaal.translatehouse.org

https://tools.stefankueng.com/

Z3  madoko.net

Contact
 daan@microsoft.com

Microsoft Research Lab – Redmond
Microsoft Building 99,
14820 NE 36th Street,
Redmond, Washington, 98052
USA

https://zenpen.io/
https://www.buymeacoffee.com/tholman


深圳市德山信通电子公司

前KUbuntu开发人员Jonathan Riddell今天宣布他的KDE neon基于Linux的操作系统现在可用于Pinebook 64位ARM笔记本电脑。Pinebook笔记本电脑现已上市两年左右，是Chromebook的轻量级低成本替代产品。它是由中国公司Pine64开发的，该公司生产的是PINE A64单板电脑，旨在成为著名的树莓派(Raspberry Pi)的替代品。 https://www.linuxprobe.com/kde-neon-pinebook.html

Pine A64开发板是一款64位四核单板电脑，这款开发板在2015年底曾经登上Kickstarter众筹平台，并在2016年年中开始出货，它的以15美元的低价称自己是树莓派杀手。这款开发板在众筹中表现抢眼，共筹集到来自36,000名爱好者的170万美元， 但发货之后的评价却是哀鸿遍野。

卡片式电脑Raspberry Pi问世以来，已然成为了科技和教育界的宠儿，同时，类似的新品也开始接连涌现出来。像是9美元的CHIP、BBC出品的Micro:bit以及国产的龙芯处理器智龙开发板等。
基于树莓派的Pi-Top！

sudo phonecall -n 10086 -o speaker --volumn .5 > record.mp3

腾讯发布听歌识曲App“Q音探歌”，据网络爆料，微信开始内测名为“视频号”的新功能，其位置在微信发现页“朋友圈”下方。网络流传截图显示，一个微信号可以创建一个视频号，在开通页面中，微信建议企业或机构使用非私人微信号进行开通。

曝Android 11已登陆Google Pixel 4
Google App中的“Google Labs”将恢复

目前韩国市场上拥有Tmax、Hancom和Invesume等已经基于Linux开发的操作系统

谷歌与WordPress母公司开发新闻发布平台Newspack

2019年12月31日，经过youtube认证的华为公司账号在youtube上发布了一个名为《HUAWEI NEWS》的“新闻”节目。
该视频时长4分钟，在视频包装和形式上，很像美国人熟悉的有线电视新闻节目。而在内容定位上，更像是一个华为官方自媒体，向全世界发布华为的信息和态度。

视频地址： https://www.youtube.com/watch?v=q9GTwOhj8v0

