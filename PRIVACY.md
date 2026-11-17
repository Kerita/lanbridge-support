# LanBridge Privacy Policy · 岚桥隐私政策

Effective 2026-11-17 · 生效日期 2026-11-17

## English

**On your Mac.** LanBridge reads app and process names, paths, signing identifiers and bundle identifiers to match the apps you select. Proxy settings and rules are stored on your Mac. Recent events and traffic counters are kept for the current session. macOS manages access to and retention of network extension logs.

**Network traffic.** Matched TCP connections send destination information and traffic through the HTTP CONNECT proxy you configure. That proxy and the destination service handle the data under their own policies. LanBridge leaves TLS encryption intact. HTTP CONNECT itself does not encrypt the connection from LanBridge to the proxy. UDP, QUIC, loopback and unmatched traffic keep their original routes. If you click Test Proxy, LanBridge sends a CONNECT handshake to chatgpt.com:443 through your proxy without sending credentials or requesting a web page.

**Data collection and purchases.** LanBridge has no developer-operated traffic servers, account system, ads, or third-party tracking SDKs. It does not send your rules, app list, connection logs, or browsing traffic to the developer. Apple handles App Store purchases. GitHub hosts these public documents and issues under its own [privacy statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement).

**Support and controls.** If you open a public issue, GitHub and the developer can see the information you post. Share only what is needed to resolve the issue. You can pause forwarding, remove rules in LanBridge, and manage the remaining network configuration and system logs through macOS. For questions, use the [support page](README.md).

## 简体中文

**设备上的处理。** 岚桥读取应用与进程的名称、路径、签名标识和 Bundle ID，以匹配你所选的目标。代理设置和规则保存在此 Mac 上。最近事件和流量计数保留在当前会话中。网络扩展系统日志由 macOS 管理访问权限与保留时间。

**网络流量。** 匹配的 TCP 连接通过你指定的 HTTP CONNECT 代理发送目标信息与流量。代理和目标服务按各自的政策处理数据。岚桥保留 TLS 加密。HTTP CONNECT 本身不加密岚桥到代理的连接。UDP、QUIC、本地回环和未匹配流量走原路径。点击「测试代理」时，岚桥通过代理向 chatgpt.com:443 发送 CONNECT 握手，不发送凭据或请求网页。

**数据收集与购买。** 岚桥没有开发者运营的转发服务器、账号系统、广告或第三方追踪 SDK。应用不会把规则、应用列表、连接日志或浏览流量发送给开发者。App Store 购买由 Apple 处理。GitHub 按其[隐私声明](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement)托管这些公开文档和反馈。

**支持与控制。** 在 GitHub 提交公开反馈时，开发者和 GitHub 能看到你发布的内容。请只提供解决问题所需的信息。你可以在岚桥中暂停转发和删除规则，并通过 macOS 管理剩余网络配置和系统日志。有关隐私的问题请通过[支持页面](README.md)联系开发者。
