# 许可及对应源码位置 / Licenses and corresponding source

Mansur 自有代码及文档按 `legal/Mansur-MIT.txt` 授权。第三方组件和单独下载的模型保持各自许可证，本下载仓库不改变其授权条件。整个安装包并非仅适用 MIT。

本页协议对应 87（2026-10-25.1），旧版以各自安装包随附文件为准。私有源码仓库的访问范围不因本次发布改变。

以下组件路径相对于本版程序的版本目录；`Setup/legal/` 位于 Mansur 安装根目录：

- `LICENSE`、`NOTICE`、`THIRD_PARTY_NOTICES.md`：版权、来源及第三方许可边界。
- `notices/`、`licenses/`、`runtime/python/`：原始组件许可和具体说明。
- `notices/VOICE_RUNTIME.md`：本地朗读组件与 GPL 对应源码说明。
- `runtime/python/corresponding-source.zip`：随包语音组件、相关 Mansur worker、构建脚本与锁定清单等对应源码材料。
- `licenses/asr/libsndfile-1.2.2-noexternal-corresponding-source.zip`：独立 LGPL 音频库的对应源码、配置及重建材料。
- `Setup/legal/`：本次安装的使用条款、隐私说明和安装前阅读文本。

Mansur-owned code and documentation use MIT. Third-party components and separately downloaded models retain their respective licenses. GPL/LGPL corresponding-source materials and build information are included at the paths above. The complete installer must not be described as MIT-only. Applicable open-source rights are not reduced by the installation terms.

## 许可材料说明 / License materials — 2026-10-25

本页当前下载为 87 测试版，SHA256：

`7fe6d994a73c8b95c4e0e31e5499dba1a139ec03234a2ff0c9309a96fa379c8f`

维护者已于 2026-10-23 经微软官方流程获得并安装 Visual Studio Community 2022，记录了个人开发自有应用的后续获得依据。旧清单中“Visual Studio 资格待确认”反映此前阶段；不是本次仍未获得 Community 的结论，也不追认全部历史构建。微软组成仍按其适用[Community 条款](https://visualstudio.microsoft.com/license-terms/vs2022-ga-community/)和[再分发清单](https://learn.microsoft.com/en-us/visualstudio/releases/2022/redistribution)提供，不由 Mansur 的 MIT 重新授权。

本次构建核对了文件清单中许可、来源及对应源码材料的完整性（87 实机安装尚未验收）：GPL 语音对应源码位于 `runtime/python/corresponding-source.zip`，当前 Mansur Python worker 源码另随程序提供；LGPL 音频库完整对应源码位于上列 `licenses/asr/libsndfile-1.2.2-noexternal-corresponding-source.zip`，原许可、配置、重建及替换库说明一并保留。本版复用已锁定的这些档案，也未把模型权重许可改为代码许可。

本补充不宣称已独立复现所有模型转换、核实每个音色或训练素材的全部权利，亦不构成对全部第三方权利的全面认证。单独下载的模型仍须保留对应原始模型卡、条款、作者和转换来源；本补充不代表用户接受其外部协议。

客服与隐私联系 / Support and privacy: **800693@QQ.com**.
