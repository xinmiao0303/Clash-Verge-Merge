# Clash Verge Merge

用于 Clash Verge 的 Merge 合并配置，主要包含 DNS、fake-ip 过滤和地理数据库更新设置。

## 文件

- [Merge.txt](./Merge.txt)：原始配置文件，内容为 YAML 格式，保留上传时的文件名和内容。
- [LICENSE](./LICENSE)：MIT 开源许可证。

[查看或下载 Merge.txt 原始文件](https://raw.githubusercontent.com/xinmiao0303/Clash-Verge-Merge/main/Merge.txt)

## 配置概览

- 使用 `rule` 模式，启用统一延迟和 TCP 并发，关闭 IPv6。
- 使用 `fake-ip`，为国内域名、局域网域名及配置中列出的部分服务返回真实 IP。
- 配置国内 DNS 与境外 DoH 的解析策略。
- 启用地理数据库自动更新，更新间隔为 24 小时。

仓库不包含代理节点或订阅信息；使用时请结合自己的客户端配置和网络环境。

## 许可证

本项目使用 [MIT License](./LICENSE)。
