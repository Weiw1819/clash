https://mihomoparty.net/clients/  
https://github.com/clash-download/Clash

1.代理协议
主流协议, 包括 Shadowsocks,ShadowsocksR,VMess, Vless, Trojan, Tuic, Socks, Http, Hysteria, Hysteria2, Wireguard, AnyTLS, Mieru 等.
Shadowsocks、NaïveProxy、VMess、VLESS、TUIC、WireGuard、Trojan、和Hysteria。  

2.代理内核  
Mihomo（原名 Clash Meta）是一款开源的网络代理核心（Proxy Core），由 MetaCubeX 组织维护开发。Mihomo 本身是一个纯命令行代理核心（Core），不包含图形界面（GUI）  
https://github.com/MetaCubeX/mihomo（27K）

sing-box  
sing-box 本身是纯命令行代理核心（Core），不包含图形界面，与 Mihomo/Clash 定位相同。但社区已开发多个图形化客户端（GUI） 封装 sing-box 内核，提供可视化操作体验。  
https://github.com/SagerNet/sing-box（30K）

|内核名称|	开发组织/作者|	特点	|协议支持	|开源 |
| :---: | :---: | :---: | :---: | :---: |
|Xray-core|	XTLS 组织 |	V2Ray 超集，性能优化，支持 XTLS/REALITY |	VMess/VLESS/Trojan/Shadowsocks + REALITY|	✅  |
|sing-box|	SagerNet (Project S)	|现代化架构，模块化设计，支持链式代理 |	全协议（含 Hysteria2/TUIC/REALITY/WireGuard）|	✅|  
|Mihomo	|MetaCubeX |	Clash.Meta 增强版，规则引擎强大|	VMess/VLESS/Trojan/Shadowsocks + Hysteria2/TUIC|	✅  |
|v2fly-core|	v2fly 社区|	V2Ray 官方维护分支，稳定但功能保守	|基础协议（VMess/VLESS/Trojan/Shadowsocks）|	✅  |
|clash|	Dreamacro	|原版 Clash，轻量级	| 基础协议（SS/VMess/Trojan）|	✅  |



3.代理软件  
v2rayN（C#）（WPF框架）  
https://github.com/2dust/v2rayN  

clash-party（Mihomo）（TypeScript）（Electron框架）  
https://github.com/mihomo-party-org/clash-party  
Electron 是一个开源的桌面应用开发框架，由 GitHub（现属 Microsoft）开发并维护。它允许开发者使用 Web 技术（HTML、CSS、JavaScript） 来构建跨平台的桌面应用程序，支持 Windows、macOS 和 Linux。https://github.com/electron/electron  

clash-verge-rev（Mihomo）（TypeScript）（Tauri框架）  
https://github.com/clash-verge-rev/clash-verge-rev  
Tauri 是一个现代、轻量级的开源框架，用于使用 Web 前端技术（HTML/CSS/JavaScript 或前端框架如 React、Vue、Svelte 等）构建安全、高性能的跨平台桌面应用程序。https://github.com/tauri-apps/tauri  
原仓库：https://github.com/zzzgydi/clash-verge  

sing-box-windows（sing-box）（Tauri框架）  
https://github.com/xinggaoya/sing-box-windows  

clash-nyanpasu（Tauri框架）  
https://github.com/libnyanpasu/clash-nyanpasu

GUI.for.SingBox（sing-box）（Wails框架）  
https://github.com/GUI-for-Cores/GUI.for.SingBox  
Wails 是一个使用 Go 语言 编写的开源框架，用于构建 轻量级、高性能的跨平台桌面应用程序。它允许开发者用 Go 编写后端逻辑，同时使用 现代 Web 前端技术（如 Vue、React、Svelte、SolidJS 等）构建用户界面，最终将前后端打包成一个原生可执行文件（无需浏览器或 Electron 运行时）。https://github.com/wailsapp/wails  

GUI.for.Clash（Mihomo）（Wails框架）  
https://github.com/GUI-for-Cores/GUI.for.Clash  

FlClash（Dart）（Flutter框架）  
https://github.com/chen08209/FlClash  
FlClash 是一个基于 Flutter（前端界面） 和 Go（核心网络引擎）技术栈开发的跨平台网络代理客户端。  
Flutter 是由 Google 开发并开源 的一套 UI 工具包（UI toolkit），用于构建 高性能、高保真、跨平台的原生应用。使用 Flutter，开发者可以用 一套代码库 同时为 iOS、Android、Windows、macOS、Linux 和 Web 平台开发应用。  https://github.com/flutter/flutter  

hiddify-app（Flutter框架）   
https://github.com/hiddify/hiddify-app  

karing（Flutter框架）  
https://github.com/KaringX/karing  

nekoray（Qt框架）  
https://github.com/MatsuriDayo/nekoray  

Qv2ray（Qt框架）  
https://github.com/Qv2ray/Qv2ray  

shadowsocks-qt5（Qt框架）  
https://github.com/shadowsocks/shadowsocks-qt5  

Avalonia新框架（C#）  
https://github.com/AvaloniaUI/Avalonia  

# Windows 桌面端开发框架对比（2026）

| 框架名称 | 技术栈 | 原生性 | 跨平台支持 | 性能 | 学习曲线 | 生态成熟度 | 适用场景 | 最新状态 |
|---------|--------|--------|------------|------|----------|------------|----------|----------|
| **WinUI 3** | C#/C++ + XAML | ✅ 完全原生 | ❌ 仅 Windows | ⭐⭐⭐⭐⭐ | 中等 | ⭐⭐⭐⭐ | 现代化 Windows 应用、Fluent Design | .NET 8+ 官方主推，UWP 继任者 |
| **WPF** | C# + XAML | ✅ 原生 | ❌ 仅 Windows（.NET Core 3.0+ 有限支持 Linux/macOS） | ⭐⭐⭐⭐ | 中等 | ⭐⭐⭐⭐⭐ | 企业级桌面应用、复杂 UI、数据密集型 | .NET 8 持续更新，长期支持 |
| **WinForms** | C# | ✅ 原生 | ❌ 仅 Windows（.NET Core 3.0+ 有限跨平台） | ⭐⭐⭐ | 低 | ⭐⭐⭐⭐⭐ | 传统业务系统、快速开发、简单 UI | .NET 8 持续维护，适合遗留系统迁移 |
| **.NET MAUI** | C# + XAML | ⚪ Windows 端基于 WinUI 3 | ✅ Windows/macOS/iOS/Android | ⭐⭐⭐⭐ | 中等 | ⭐⭐⭐ | 跨平台移动+桌面统一代码库 | .NET 8+ 稳定版，微软官方跨平台方案 |
| **Avalonia UI** | C# + XAML (.axaml) | ⚪ 自绘渲染（Skia） | ✅ Windows/Linux/macOS/iOS/Android/WebAssembly | ⭐⭐⭐⭐ | 中等 | ⭐⭐⭐ | 跨平台 .NET 应用、需 Linux 支持 | 开源活跃（MIT），.NET 8 兼容 |
| **Electron** | JavaScript/TypeScript + HTML/CSS | ❌ WebView 封装 | ✅ Windows/macOS/Linux | ⭐⭐ | 低（Web 开发者友好） | ⭐⭐⭐⭐⭐ | 富文本编辑器、IDE、需 Web 生态的工具 | 内存占用高，VS Code/Slack 采用 |
| **Tauri** | Rust（后端）+ Web（前端） | ⚪ 系统 WebView | ✅ Windows/macOS/Linux/Android/iOS | ⭐⭐⭐⭐⭐ | 高（需 Rust 基础） | ⭐⭐⭐ | 轻量级桌面应用、注重安全与性能 | 2.0 支持移动端，安装包体积小 |
| **Wails** | Go（后端）+ Web（前端：Vue/React/Svelte） | ⚪ 系统原生 WebView | ✅ Windows/macOS/Linux | ⭐⭐⭐⭐ | 中等（需 Go + Web 基础） | ⭐⭐⭐ | Go 开发者构建轻量级桌面应用、Electron 替代方案 | v3 开发中，新增多窗口/类型安全事件 [[26]] |
| **Flutter** | Dart | ⚪ 自绘引擎（Skia） | ✅ Windows/macOS/Linux/iOS/Android/Web | ⭐⭐⭐⭐ | 中等 | ⭐⭐⭐⭐ | UI 一致性要求高的跨平台应用 | Windows 支持已稳定，可调用 Win32/COM API |
| **Qt** | C++/Python/QML | ✅ 原生 | ✅ 全平台（含嵌入式） | ⭐⭐⭐⭐⭐ | 高 | ⭐⭐⭐⭐⭐ | 工业软件、高性能图形应用、嵌入式 | 商业+开源双授权，C++ 生态成熟 |
| **React Native for Windows** | JavaScript/TypeScript + React | ⚪ 原生组件桥接 | ✅ Windows/macOS/iOS/Android | ⭐⭐⭐ | 低（React 开发者） | ⭐⭐⭐ | 已有 React Native 移动端需扩展 Windows | 微软维护，适合 React 技术栈团队 |

# Go 与 Rust 语言对比（2026）

| 维度 | Go (Golang) | Rust |
|------|-------------|------|
| **设计哲学** | 简洁、高效、高并发、开发者友好 | 内存安全、零成本抽象、无 GC 的高性能 |
| **内存管理** | 自动垃圾回收（GC）<br>• 延迟低（Go 1.23+ 暂停时间 < 100μs）<br>• 开发者无需手动管理 | 所有权（Ownership）+ 生命周期（Lifetime）<br>• 编译期保证内存安全<br>• 无 GC，运行时零开销 |
| **性能** | 高性能（优于 Python/Java），但略低于 C/C++/Rust<br>• 启动快、二进制小 | 接近 C/C++ 的极致性能<br>• 无运行时开销，适合高频交易、嵌入式、游戏引擎等 |
| **并发模型** | Goroutine + Channel（CSP 模型）<br>• 轻量（KB 级栈）、调度高效<br>• “不要通过共享内存通信，而要通过通信共享内存” | `async/await` + 多线程 + `Send/Sync` 标记<br>• 手动控制线程安全<br>• 并发正确性由编译器强制保证 |
| **学习曲线** | ⭐⭐（平缓）<br>• 语法极简（关键字仅 25 个）<br>• 几天可上手生产代码 | ⭐⭐⭐⭐⭐（陡峭）<br>• 所有权/生命周期概念需深入理解<br>• 初学者常遇“borrow checker”报错 |
| **编译速度** | 极快（秒级增量编译） | 较慢（尤其大型项目，依赖 LLVM 优化） |
| **二进制体积** | 小（静态链接，无外部依赖） | 中等（含标准库和 panic 处理，可通过 `strip` 优化） |
| **错误处理** | 显式返回 `error`（无异常）<br>• 鼓励检查每个错误 | `Result<T, E>` + `Option<T>`<br>• 强制处理所有可能失败路径 |
| **生态系统** | • Web 后端（Gin, Echo）<br>• CLI 工具（Cobra）<br>• 云原生（Kubernetes, Docker）<br>• 桌面（Wails, Fyne） | • 系统编程（操作系统、驱动）<br>• WebAssembly（Yew, Leptos）<br>• 区块链（Solana, Polkadot）<br>• 桌面（Tauri, Iced） |
| **典型应用场景** | • 微服务/API 服务<br>• DevOps 工具（如 Terraform）<br>• 高并发网络服务<br>• 轻量级桌面应用（Wails） | • 高性能数据库/引擎（如 DuckDB）<br>• 安全关键系统（浏览器引擎 Servo）<br>• 嵌入式/物联网<br>• 安全敏感的桌面应用（Tauri） |
| **工具链成熟度** | • `go mod`（依赖管理）<br>• 内置测试/格式化/性能分析<br>• IDE 支持极佳（VS Code, GoLand） | • `cargo`（包管理+构建+测试一体化）<br>• Clippy（代码 lint）<br>• rust-analyzer（智能补全）<br>• 生态活跃但配置较复杂 |
| **社区与企业采用** | Google、Cloudflare、Uber、字节跳动（后端主力） | Mozilla、Microsoft、Amazon（AWS Firecracker）、Discord（核心服务重写） |
| **适合开发者类型** | • 快速交付业务价值的团队<br>• 后端/DevOps 工程师<br>• 希望减少心智负担的开发者 | • 追求极致性能/安全的系统工程师<br>• 愿意投入学习成本换取长期可靠性<br>• 嵌入式/WebAssembly 开发者 |



