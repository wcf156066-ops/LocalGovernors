委任托管地方官 v0.1 安装说明
适用于 Windows 上的 Steam 版《全面战争：三国》。
首次安装
1. 在本页底部的 Assets（附件） 下载 LocalGovernors-0.1-Windows-Offline.zip。请认准这个文件名，GitHub 自动生成的 Source code (zip) 是仓库源码压缩包。
2. 关闭游戏、游戏启动器和 TK Mod Manager，把 ZIP 完整解压到一个文件夹。
3. 双击解压后的 Install.cmd，按提示完成安装。
4. 保持 Steam 运行，从桌面的 「地方官委任 0.1」 快捷方式启动游戏。
安装包已包含 MOD 本体、TK Mod Manager 和 Script Extender，下载后可以离线安装。如果你同时订阅了本 MOD，启动配置里只启用一份。要断网游玩，请提前设置好 Steam 离线模式。
原来的工坊 MOD 会怎么办？
安装包没有附带作者电脑的工坊订阅列表、MOD 开关或加载顺序。 安装时只读取你自己电脑上的配置。

安装器优先沿用已有的「地方官委任」专用配置，其次读取当前启用的 TK Mod Manager 配置，最后尝试导入官方启动器的记录。已有 MOD 的开关和相对顺序会一并导入。如果没有旧配置，就只启用本 MOD 和所需的脚本扩展器。
安装后怎么添加其他工坊 MOD？
1. 在 Steam 创意工坊订阅想用的 MOD，等下载完成。
2. 按 Win + R，输入下面这一行，回车打开 TK Mod Manager。
   %LOCALAPPDATA%\LocalGovernors\TKModManager\TKModManager.exe
3. 选择 LocalGovernors-0.1 配置，勾选新 MOD，按各 MOD 作者的说明调整加载顺序。
4. 继续用桌面的 「地方官委任 0.1」 快捷方式启动，无需重装。以后在官方启动器里改的开关和排序，需要在这份专用配置里另行调整。
从旧版升级
如果安装器提示游戏目录里已有同名但版本不同的 ib_recruit_lock.pack，按提示找到旧文件，把它移到游戏目录之外备份，再运行新版 Install.cmd
