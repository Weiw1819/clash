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

内核名称|	开发组织/作者|	特点	|协议支持	|开源
Xray-core|	XTLS 组织 |	V2Ray 超集，性能优化，支持 XTLS/REALITY |	VMess/VLESS/Trojan/Shadowsocks + REALITY|	✅
sing-box|	SagerNet (Project S)	|现代化架构，模块化设计，支持链式代理 |	全协议（含 Hysteria2/TUIC/REALITY/WireGuard）|	✅
Mihomo	|MetaCubeX |	Clash.Meta 增强版，规则引擎强大	VMess/VLESS/Trojan/Shadowsocks + Hysteria2/TUIC|	✅
v2fly-core|	v2fly 社区|	V2Ray 官方维护分支，稳定但功能保守	|基础协议（VMess/VLESS/Trojan/Shadowsocks）|	✅
clash|	Dreamacro	|原版 Clash，轻量级	| 基础协议（SS/VMess/Trojan）|	✅



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
