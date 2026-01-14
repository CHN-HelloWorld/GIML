# 原神 Mod 启动器 (GIML)

⚡ **Genshin Impact Mod Launcher** - 专为原神设计的 Mod 防报错启动工具

**✅ 6.3 版本可用**

<div align="center">
  <img src="icon.png" alt="GIML Icon" width="200">
  
  <p>
    <img src="https://img.shields.io/badge/version-2.1.0-blue.svg" alt="Version">
    <img src="https://img.shields.io/badge/platform-Windows-lightgrey.svg" alt="Platform">
    <img src="https://img.shields.io/badge/license-Proprietary-red.svg" alt="License">
    <a href="https://github.com/CHN-HelloWorld/GIML/releases/latest"><img src="https://img.shields.io/github/downloads/CHN-HelloWorld/GIML/total" alt="Downloads"></a>
  </p>
</div>

---

<div align="center">

### 💬 QQ 交流群：[1075913947](https://qm.qq.com/q/qYrUfeigeI)

**欢迎加群交流使用经验 · 反馈问题 · 获取更新通知**

</div>

---

## ⚠️ 重要说明

- **适用对象**：支持 XXMI 的 GIMI 加载器和 3DMigoto 程序两种模式（兼容 d3dxSkinManage 的 work 目录）
- **兼容性提示**：本启动器在大部分设备上有效规避游戏报错，尚未完全确定兼容性问题的根本原因。如果您的设备无法正常使用，请耐心等待后续版本更新。

## 📷 程序界面

> **提示**: 以下为程序界面展示，包含主界面、设置界面和运行效果

<div align="center">

<!-- 主界面 -->
<details open>
<summary><b>📱 主界面</b></summary>
<br>
<img src="RunImage1.png" alt="主界面" width="80%">
</details>

<!-- 设置界面 -->
<details>
<summary><b>⚙️ 设置界面</b></summary>
<br>
<img src="RunImage2.png" alt="设置界面1" width="80%">
<br><br>
<img src="RunImage3.png" alt="设置界面2" width="80%">
</details>

<!-- 运行效果 -->
<details>
<summary><b>✨ 运行效果</b></summary>
<br>
<img src="ResultImage.png" alt="运行效果" width="80%">
</details>

</div>

## 🖥️ 系统要求

| 项目 | 要求 |
|---|---|
| 操作系统 | Windows 10/11 |
| 权限要求 | 管理员权限（创建软链接需要） |
| 显示支持 | 高 DPI 自适应，多显示器兼容 |

## 📥 下载与安装

1. 从 [Releases](https://github.com/CHN-HelloWorld/GIML/releases) 页面下载最新版本
2. 解压到任意目录
3. **右键点击程序** → **以管理员身份运行**

> ⚠️ **重要**: 必须以管理员身份运行，否则无法创建软链接！

## ✨ 主要特性

### 🔄 双模式支持

| 模式 | 适用场景 |
|---|---|
| GIMI 模式 | XXMI 的 GIMI 目录 |
| 3DMigoto 模式 | 3DMigoto 程序目录（兼容 d3dxSkinManage 的 work 目录）|

一键切换，配置互不干扰，自动保存。

### 🎮 集成 FPS 解锁器

- **内置帧率解锁**：无需额外配置，稳定可靠
- **多种窗口模式**：窗口化、无边框、全屏、独占全屏
- **智能帧率限制**：自动适配显示器最高刷新率
- **HDR 支持**：支持 HDR 显示模式
- **多显示器适配**：支持任意显示器启动、热插拔自动回退
- **分辨率管理**：窗口化/无边框可自定义，全屏自动匹配原生分辨率

> ⚠️ **公平游戏承诺**：程序会在千星奇遇、幽境危战、深境螺旋、幻想真境剧诗场景中自动恢复游戏原生帧率，仅在大世界探索时开放高帧率。严禁结合宏或作弊工具使用！

### ⚙️ 设置系统

**基础设置**：
- **DLL 版本选择**：遇到"与服务器断开连接"或者"非法工具错误"可尝试切换版本
- **防报错方案**：截流法 / 隐匿法 / 双生法（支持多选，默认全选）
- **截流法拦截模式**：基础模式 / 增强模式（勾选截流法后可选）
- **手动启动游戏**：仅启动 Mod 加载器，在 10 秒内手动启动游戏

**帧率与画面设置**：目标帧率、窗口模式、显示器选择、分辨率、HDR 等

## 📋 使用指南

### 首次配置

1. **以管理员身份启动程序**

2. **选择工作模式**
   - 默认为 GIMI 模式，点击切换按钮可切换至 3DMigoto 模式

3. **配置文件夹路径**

   | 模式 |选择目标路径| 必需内容 | 可选内容 |
   |---|---|---|---|
   | GIMI 模式 |XXMI 的 GIMI 目录| Core、Mods、ShaderCache、ShaderFixes 文件夹 | d3dcompiler_47.dll、d3dx_user.ini |
   | 3DMigoto 模式 |3DMigoto 程序目录（兼容 d3dxSkinManage 的 work 目录）| Mods、ShaderCache、ShaderFixes 文件夹 和 3DMigoto Loader.exe、d3dx.ini | d3dcompiler_46.dll、d3dx_user.ini |

4. **配置原神路径**
   - 选择原神可执行文件（`YuanShen.exe` 或 `GenshinImpact.exe`）

5. **高级设置（可选）**
   - 点击 **⚙️ 设置** 按钮配置 DLL 版本、防报错方案、帧率等

### 日常使用

配置完成后：**管理员运行** → **点击启动** → **3 秒后自动退出**

## ❓ 常见问题

### Q: 启动时提示"需要管理员权限"？

右键点击程序，选择"以管理员身份运行"。

### Q: 出现"与服务器断开连接"、“非法工具”错误？

#### 请尝试下面的方案
- 关闭一切杀毒软件，保证三种防报错方案全部勾选，若报错，可重新进游戏，再观察
- 可以尝试在"设置"→"基础"中切换不同的 DLL 版本，推荐优先选择较高版本号（如 0.7.0、0.6.8）。

### Q: 不同防报错方案有什么区别？

| 方案 | 特点 |
|---|---|
| 截流法 | 过滤传输流量 |
| 隐匿法 | 传统方案，稳定可靠 |
| 双生法 | 更轻量，启动更快，针对性强 |

**提示**：三种方案可同时勾选，默认全选以获得最佳防护效果。

### Q: 截流法的基础模式和增强模式有什么区别？

| 模式 | 特点 |
|---|---|
| 基础模式 | 不影响其他应用网络，但是效果一般 |
| 增强模式 | 影响微信等应用的网络连接，但是效果更佳 |

**提示**：默认使用基础模式。如果基础模式下仍然出现报错，可尝试切换到增强模式。**使用此方法不需要使用火绒拦截**

### Q：启动后不显示Mod？

请确认是否关闭了AI插帧功能

### Q：GIMI无法产出数据 & 找不到GIMI产出的数据 & GIMI产出的数据丢失？

产出的数据位于GIML的工作目录下而非您的GIMI目录，您可以使用GIML主页的“工作目录”按钮访问工作目录

### Q:游戏窗口不见 & 游戏崩溃

使用了不兼容的Mod，请排查您的Mod，并将不兼容的Mod移除

### Q:运行GIML没反应？

很抱歉您遇到了此问题，此问题是因为底层依赖库不支持您的设备，您目前**无法使用GIML**

### Q: 帧率应该设置多少？

建议根据显示器刷新率设置：60Hz→60FPS，144Hz→144FPS，240Hz→240FPS。程序会自动将上限设为显示器最高刷新率。

### Q: 为什么战斗场景帧率自动降低？

为维护公平游戏环境，程序会在特定场景（千星奇遇、幽境危战、深境螺旋等）自动恢复原生帧率，离开后自动恢复设置值。

### Q: 显示器相关问题

- **拔掉显示器后启动失败**：程序会自动切换到主显示器，第一次可能需要点击启动两次
- **切换显示器后分辨率变少**：正常现象，程序会根据当前显示器过滤合适选项
- **高分辨率 UI 异常**：检查 Windows 显示设置中的缩放比例

### Q: 启动器报错与游戏版本不兼容？

使用启动器的自动修复功能即可。

## 👨‍💻 项目信息

| 项目 | 信息 |
|---|---|
| 项目名称 | GIML (Genshin Impact Mod Launcher) |
| 版本 | 2.1.0 |
| 作者 | Aether |
| 许可证 | 专有软件许可证 (Proprietary License) |
| 更新时间 | 2026 年 1 月 14 日 |

## 🤝 反馈与支持

如遇问题或有建议，欢迎通过以下方式联系我们：

- **GitHub Issues**: [提交问题或建议](https://github.com/CHN-HelloWorld/GIML/issues)
- **QQ 交流群**: [1075913947](https://qm.qq.com/q/qYrUfeigeI)

## 📜 许可证

本软件为专有软件（闭源），仅供个人学习、研究和非商业用途使用。详见 [LICENSE](LICENSE) 文件。

| | 说明 |
|---|---|
| ✅ | 完全免费，禁止商业使用 |
| ✅ | 若付费购买，请凭此说明退款 |
| ⚠️ | 禁止反编译、修改或创建衍生作品 |
| ⚠️ | 请低调使用，严禁大肆宣传 |

---

**免责声明**: 本工具仅供学习和研究使用。使用 Mod 可能违反游戏服务条款，请自行承担风险。我们不提倡在正式服务器使用 Mod，建议仅在私人服务器使用。

**🙏 感谢所有为原神 Mod 社区做出贡献的开发者和玩家！**

---

## 💝 赞赏支持

**⚠️ 本启动器依赖游戏生态，请优先考虑支持游戏而不是本启动器！**

如果您觉得本项目对您有帮助，可以通过以下方式支持开发者：

<p align="center">
  <img src="Appreciation code.png" alt="赞赏码" width="300">
</p>

<p align="center">
  <em>您的支持是我们持续更新的动力！</em>
</p>
