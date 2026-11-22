# Subata-2.4.7-Lite

一个 Wizard101 Windows 启动器。**只需安装一份 Wizard101，就能用官网账号和 Steam 账号登录，或在「全部」中混合启动。** 安装器和启动器均支持中文与 English。

[Windows 下载页](http://101.43.174.221:3001/file/subataLite/index.html) · [GitHub Releases](https://github.com/adquantum/Subata-launcher/releases) · [English](#english)

![Subata Lite 混合登录与汉化选项](http://101.43.174.221:3001/file/subataLite/docs/login-zh.png)

## 第一步 · 从 Steam 安装 Wizard101

推荐通过 Steam 下载，通常更方便，也只需维护一份客户端。安装完成后先运行一次，让 Wizard101 下载齐游戏文件。如果已有能正常启动的美服 Wizard101，可以直接使用那份安装，Steam 或官网安装来源均可。请保持游戏版本与在线服务兼容。 [Wizard101 Steam 商店页](https://store.steampowered.com/app/799960/Wizard101/)

## 第二步 · 确认 Wizard101 游戏目录

1. 安装 Subata Lite。安装时选择的中文或英文会成为初始界面语言。之后可从标题栏切换。
2. Subata 首次启动会自动从 Steam 游戏库查找 Wizard101。游戏移动或重装后，登录时会再查找一次。
3. 需要手动选择时，在 Steam 库中打开 **管理 → 浏览本地文件**，再到 Subata 的 **设置 → 游戏设置 → Wizard101 → 选择路径**，选中该目录中的 **Wizard101.exe**。

![设置中的 Wizard101 游戏路径](http://101.43.174.221:3001/file/subataLite/docs/settings-zh.png)

## 第三步 · 按账号注册渠道登录

| 账号类型 | 登录时如何选择 |
| --- | --- |
| 在 Wizard101 官网注册的账号 | 添加或编辑账号时选 **官网**。即使游戏是从 Steam 下载的，仍选官网认证。 |
| 通过 Steam 注册或绑定的 Steam 渠道账号 | 选 **Steam**，并在 Steam 客户端登录对应的 Steam 账号。 |
| 两种账号都要使用 | 在 **全部** 中勾选多个账号后点 **登录**。所选账号各自按保存的渠道认证。 |
| 临时用一个账号 | 不勾选保存的账号，点击 **直接登录**，在表单里选择实际渠道。按需勾选记住账号。 |

两个渠道都可切换 **用 Steam 记录游玩时长**。Steam 账号取消勾选后以标准模式启动游戏，登录时仍由 Steam 签发票据。

看到「账号注册渠道不匹配」时，用提示旁的 **编辑渠道** 核对保存的渠道。Steam 下载来源和账号注册渠道是两个独立选项。

## 汉化补丁 · 应用后可从 Steam 或官网启动

| 游戏语言 | 应用的补丁 |
| --- | --- |
| 英文版 | 英文游戏界面，保留中文聊天支持 |
| 全中文 | 全量汉化 |
| 剧情中文 | 剧情汉化 |

在登录窗口选语言，按提示下载并校验补丁，再点 **登录** 让启动器把所选补丁应用到游戏安装目录。**应用成功后，从 Steam、官方启动器或 Subata 打开这同一份游戏，都会读取已汉化的游戏文件。** 仅安装 Subata 不会修改游戏语言。Steam 验证文件、游戏更新或修复可能覆盖补丁，遇到这种情况，在 Subata 重新应用即可。

101 发布服务暂时不可用时，可用 **离线模式** 切换已校验的本地补丁。Wizard101 游戏认证仍需联网，Steam 渠道仍需 Steam。

## English

**One Wizard101 installation works with both Official and Steam accounts.** We recommend installing the US version from Steam. Launch it once to finish downloading game files. Subata automatically looks for Wizard101 in your Steam libraries. To select it manually, use **Manage → Browse local files** in Steam, then select **Wizard101.exe** under **Settings → Game settings → Wizard101 → Choose path** in Subata.

Choose **Official** for an official-site account, regardless of where you downloaded the game. For a Steam-channel account, choose **Steam** and sign in to the matching Steam account. **All** lets you select both types. With no account selected, **Direct sign-in** accepts a temporary account. Either channel can disable **Track playtime in Steam**. Steam-channel sign-in still uses a ticket issued by Steam.

Choose **English**, **Full Chinese** or **Chinese Story**, update the patch if prompted, then sign in to apply it. The patch is written to the game's installation folder. It continues to work when you open that same installation through Steam or the official launcher. Reapply it if a game update or file verification overwrites it.

![English interface and game language options](http://101.43.174.221:3001/file/subataLite/docs/login-en.png)

Supports **64-bit Windows 10 and 11**. The installer runs per user and uses the Microsoft WebView2 Runtime. This repository distributes the Windows installer and its documentation.

