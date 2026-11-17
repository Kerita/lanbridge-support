# LanBridge for Mac · 岚桥

LanBridge forwards TCP connections from selected Mac apps through an HTTP CONNECT proxy you provide. It supports Apple silicon Macs running macOS 14 or later, with English and Simplified Chinese interfaces.

## Getting help

Use [GitHub Issues](https://github.com/Kerita/lanbridge-support/issues/new) to contact the developer. Include your macOS version, LanBridge version, steps to reproduce, and the error message. Issues are public. Remove credentials, proxy addresses, hostnames, private paths, and personal information from screenshots or logs.

Set your **Default Proxy**, then choose **Add App or Process**. Follow any macOS prompts to approve the network extension. **Test Proxy** checks whether your proxy accepts an HTTP CONNECT handshake. Open **Diagnostics** to check whether your application traffic is being forwarded. Existing connections may need to reconnect after a rule changes.

UDP, QUIC, loopback and unmatched traffic keep their original routes. Use **Pause All** to pause forwarding.

## 简体中文

岚桥将所选 Mac 应用的 TCP 连接转发到你提供的 HTTP CONNECT 代理。需要 Apple 芯片 Mac 和 macOS 14 或更高版本，支持简体中文和英语。

请通过 [GitHub Issues](https://github.com/Kerita/lanbridge-support/issues/new) 联系开发者。请注明 macOS 和岚桥版本、复现步骤及报错。反馈公开可见，上传截图或日志前请移除密码、代理地址、域名、私有路径和个人信息。

设置「默认代理」后点击「添加应用或进程」，按 macOS 提示批准网络扩展。「测试代理」用于检查代理连通性，「诊断」可查看转发情况。修改规则后，已有连接可能需要重新建立。UDP、QUIC、本地回环和未匹配流量走原路径。可用「暂停全部」暂停转发。

[Privacy Policy · 隐私政策](PRIVACY.md)
