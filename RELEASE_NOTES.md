# Mansur 87 · Windows x64 测试版

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
