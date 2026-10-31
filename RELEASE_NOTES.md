# Mansur 发行记录

## 99 网页在线翻译修复版 · 2026-10-31

[下载99安装包](https://github.com/mabin8121828-crypto/Mansur-Downloads/releases/download/v0.1.0-99/Mansur-Setup-0.1.0.99-Windows-x64.exe) · [99发行页](https://github.com/mabin8121828-crypto/Mansur-Downloads/releases/tag/v0.1.0-99)

当前下载为99，配套扩展0.3.12已于2026-10-31向两店提交同一更新包：Chrome待审核、Edge正在审阅；当前公开版仍为Chrome 0.3.11、Edge 0.3.3。整页英文译中文固定使用电脑端选中的在线API服务和模型；修复原文/包装回显、单段失败阻断页面及正确时间表达被误判。动态补译和原文恢复通过实际API路径检查；专业增强默认关闭，只发送必要上下文及命中词条。

已在目标电脑完成98卸载、99安装、阅读接入和最终卸载，99程序文件最终移除，2693项保护记录通过。Chrome测试版实际本地样句、Edge真实API整页片段与动态内容，以及Word实际选文回调通过。不是正式商店安装/自动更新或干净电脑首次安装验收。测试中的安装引导改选了本地模型，结束后已恢复原有模型选择；API服务与模型未更换。

安装包417264844字节，SHA256：`3df421b6c588cd7dd40b21d904c14894d8663404c21efb8f437d3f6c3982c4a0`。发布后完整匿名下载验证一致；仅公开安装包、校验值及公开说明，本机日志和个人数据不上传。以下为历史发布记录，不代表当前推荐版本。

## 97 安装卸载修复版 · 2026-10-31

[下载97安装包](https://github.com/mabin8121828-crypto/Mansur-Downloads/releases/download/v0.1.0-97/Mansur-Setup-0.1.0.97-Windows-x64.exe) · [97发行页](https://github.com/mabin8121828-crypto/Mansur-Downloads/releases/tag/v0.1.0-97)

当前推荐电脑端为97，配套扩展为0.3.11。统一安装向导与维护入口的版本校验，补齐账户阶段核验和诊断。最终安装包的实际修复安装、Chrome／Edge／Word试译和再次完整卸载已通过；2693项保护记录核对通过，个人设置、词库、历史和模型保留。最终卸载无需再次重启。全新电脑首次安装尚未单独测试，仍以预发布提供。

安装包417387235字节，SHA256：`c2e3b9a6240686fa5e041fe93da5e963e4a07750935c6b5c0294bed4fe6287e6`。完整匿名下载已验证。两店扩展审核独立进行：2026-10-30已提交0.3.11；根据2026-10-31提供的开发者后台截图，Chrome 0.3.11已公开发布，Edge 0.3.11仍在审核、当前公开版本为0.3.3。

历史安装包保持原文件与校验值；旧欢迎页若仍写92／94，请使用本页的97下载入口。历史版本及稳定Latest标签保留。

## 94 公开测试版 · 2026-10-30

[下载94安装包](https://github.com/mabin8121828-crypto/Mansur-Downloads/releases/download/v0.1.0-94/Mansur-Setup-0.1.0.94-Windows-x64.exe) · [94发行页](https://github.com/mabin8121828-crypto/Mansur-Downloads/releases/tag/v0.1.0-94)

Mansur 94 公开测试版 · Windows x64

本次上传已完成本地验证的原安装包，不重新编译或打包。目标电脑安装验收尚未完成，因此标记为预发布；92已验收版继续保留。

更新内容：
- 本地通用整页翻译加入有限可见上下文，区分状态栏Running（运行中）与运动Running（跑步），不要求开启专业增强。
- 关联表头或标签变化时重新处理，同词的不同语境隔离缓存，迟到译文不覆盖新内容。
- 专业增强由电脑端统一设置，默认关闭；开启后手动选择领域，并单独决定是否使用已导入词库，Chrome与Edge跟随同一设置。
- 保留课程动态翻页、公式及按钮内中文，补齐94安装、旧连接兼容和卸载保护边界。

配套与使用：
- 安装包内附本地浏览器扩展0.3.11；商店中的公开版本及审核进度独立管理，本次桌面上传不代表0.3.11已在两店上架。
- 适用于Windows 10 2004及以上／Windows 11、Intel或AMD x64。模型和语音资源按需另行准备；安装包不包含个人模型、词库、设置、历史或API密钥。
- 通用上下文和专业词库仅用于本地整页路径；在线API与划词保持已有规则，本地失败不会自动切换在线服务。
- 更改专业设置或词库后，刷新已打开网页。升级时按安装器提示处理旧版，需保留数据时不要勾选删除设置、词库、历史或模型。
- 安装包未进行数字签名，请按正常Windows流程处理提示；无需关闭安全功能。

验证范围：1715项程序自检、111项Python回归、116项真实浏览器合成后端检查，以及原生协议、安装器编译和卸载保护检查通过。20个固定合成样例的真实本地模型对照中，指定词义由孤立输入10/20提升到加入上下文20/20；这不是总体准确率，也不保证所有复杂表格或网页指令干扰均可识别。压缩完整性、包内清单与39个变更文件逐项哈希通过。尚未完成目标电脑安装、正式商店安装和自动更新验收。

文件：Mansur-Setup-0.1.0.94-Windows-x64.exe
大小：417285140字节
SHA256：e2e00ec633ccf2508caeb3e23511eaf035eeabb9b8014c643ae69ce7db09296c

以上为94发布时的历史记录；当前下载请使用页首97。旧发布继续保留，源码仓库继续保持私有。

## 92 已验收版

[92下载与发行说明](https://github.com/mabin8121828-crypto/Mansur-Downloads/releases/tag/v0.1.0-92)。92于2026-10-29由用户确认安装可用；GitHub稳定版Latest入口保持92。历史验收不自动适用于94。

## 历史发布：Mansur 87 · Windows x64 测试版

[直接下载 87 安装包](https://github.com/mabin8121828-crypto/Mansur-Downloads/releases/download/v0.1.0-87/Mansur-Setup-0.1.0.87-Windows-x64.exe) · [安装说明 / Installation guide](https://github.com/mabin8121828-crypto/Mansur-Downloads#readme)

使用已生成的 87 安装包原样发布，没有为上传重新打包。**本版实机安装、卸载和完整使用验收尚待完成，因此作为 Prerelease 提供。**

- Windows 10 2004+ / Windows 11，Intel / AMD x64。
- 文件：`Mansur-Setup-0.1.0.87-Windows-x64.exe`，416,915,620 字节（约 398 MiB）。
- SHA256：`7fe6d994a73c8b95c4e0e31e5499dba1a139ec03234a2ff0c9309a96fa379c8f`。
- 安装包未代码签名；请核对来源、校验值及随附协议。

本次修复：

1. 新下载模型使用 Mansur 产品目录下的 Models，历史下载记录不会覆盖新默认目录；已有模型优先复用，不自动移动或重复下载。
2. 向导版本号从当前程序读取，修正仍显示 83 的遗漏。
3. 卸载先释放自身文件检查持有的句柄，修正误报文件占用；保留失败提示、可重试恢复及个人数据分类选择，默认保留设置、词库、API 和模型。

已完成构建、安装档案完整性与 763 项桌面自动检查；新安装包未在实机执行，这些检查不代表用户场景均已通过。Chrome、Edge 的 Mansur 0.3.3 与 87 沿用相同协议，10 项模拟兼容检查通过；不因此改动或重复上传在审扩展包。正式商店安装仍待验收。

[既有 83 审核基线](https://github.com/mabin8121828-crypto/Mansur-Downloads/releases/tag/v0.1.0-83)保持原样，可继续用于已提交的审核说明。新版本不替换该链接或其历史验收结论。

普通打字不需要下载模型。可选模型另行确认后准备；内置下载优先使用国内 ModelScope 来源，速度与可用性取决于网络和来源服务。下载 Assets 中的 **EXE**；自动 Source code 压缩包仅为下载仓库文档。

公开协议对应本版 2026-10-25.1，旧版以各自随包协议为准。Mansur 自有代码 MIT，第三方组件和模型遵守原许可；对应源码材料随包。电脑端客服：**800693@QQ.com**。

## English

Version 87 is published unchanged as a prerelease. It fixes the model download directory, outdated setup-guide version label and a self-held file-check handle in uninstallation. The unsigned installer is 416,915,620 bytes. Build, archive-integrity and 763 desktop checks passed; actual installation, removal, data-preservation and complete usage acceptance are pending. Chrome and Edge Mansur 0.3.3 retain protocol compatibility (ten simulated checks), while actual browser/store acceptance remains pending. The existing 83 release stays available for submitted review instructions. Download the EXE, not automatic Source code archives. Optional models are separate downloads. See the repository's installation, privacy and license documents.
