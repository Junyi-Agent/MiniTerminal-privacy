# MiniTerminal Privacy Policy / 隐私政策

Last updated / 最后更新：2026-11-22

[English](#english) · [简体中文](#简体中文)

## English

MiniTerminal is an SSH and Mosh terminal for iPhone and iPad. The developer runs no servers, and the app contains no analytics, advertising or tracking code. The developer receives no data from the app.

**On your device.** Hosts, settings, snippets, known host keys and the event log are stored only on your device. Passwords, private keys, one-time code secrets and your Anthropic API key are stored in the iOS Keychain.

**SSH and Mosh servers.** The app connects directly to the servers you add. What you type and what the servers send back travel only between your device and those servers.

**iCloud (optional, off by default).** If you turn on iCloud Sync, hosts, identities without their secrets, snippets, known hosts and some settings are stored in your private iCloud database. If you also turn on Sync Passwords and Keys, passwords and keys are stored in iCloud Keychain. Apple stores this data under your Apple Account. The developer cannot read it.

**Agent (optional).** The Agent only works with an Anthropic API key that you enter. When you use it, your messages and the information the agent reads to answer you are sent to Anthropic's API (api.anthropic.com) under your key. That information can include terminal text, host names and settings. Anthropic's privacy policy applies to that data: <https://www.anthropic.com/legal/privacy>. Passwords and private keys are never sent.

**Location.** If you turn on Keep Connected in Background, the app runs location updates so iOS keeps it running and your session stays connected. Locations are discarded right away. They are not stored, logged or sent anywhere.

**Camera.** The camera is used only to scan the QR code of a one-time code you add. Images are not stored or sent.

**Face ID.** Face ID is checked by iOS. The app never sees your biometric data.

**Children.** The app is not directed at children and collects no data from anyone.

**Changes.** Changes to this policy are published here, and the commit history shows every earlier version.

**Contact.** Open an issue in this repository.

## 简体中文

MiniTerminal 是 iPhone 和 iPad 上的 SSH 和 Mosh 终端。开发者不运营任何服务器，App 里没有统计、广告或追踪代码。开发者收不到 App 里的任何数据。

**存在你的设备上的。** 主机、设置、命令片段、已知主机密钥和事件日志只存在你的设备上。密码、私钥、一次性验证码的密钥和你的 Anthropic API key 存在 iOS 钥匙串里。

**SSH 和 Mosh 服务器。** App 直接连接你添加的服务器。你输入的内容和服务器返回的内容只在你的设备和这些服务器之间传输。

**iCloud（可选，默认关闭）。** 打开 iCloud 同步后，主机、不含秘密的身份信息、命令片段、已知主机和部分设置会存进你的 iCloud 私有数据库。如果同时打开「同步密码和私钥」，密码和私钥会存进 iCloud 钥匙串。这些数据由 Apple 存在你的 Apple 账户下，开发者无法读取。

**Agent（可选）。** Agent 只有在你填入自己的 Anthropic API key 后才能用。使用时，你的消息和 agent 为回答你而读取的信息会用你的 key 发送到 Anthropic 的 API（api.anthropic.com）。这些信息可能包括终端里的文字、主机名和设置。这部分数据适用 Anthropic 的隐私政策：<https://www.anthropic.com/legal/privacy>。密码和私钥不会被发送。

**位置。** 打开「后台保持连接」后，App 会接收位置更新，让 iOS 保持 App 运行，会话就不会断开。收到的位置会立即丢弃，不保存、不写日志、不发送到任何地方。

**相机。** 相机只用来扫描你添加的一次性验证码的二维码。拍到的图像不保存也不发送。

**Face ID。** Face ID 由 iOS 验证，App 拿不到你的生物识别数据。

**儿童。** 本 App 不面向儿童，也不收集任何人的数据。

**变更。** 本政策的改动会发布在这里，提交历史保留了以往每个版本。

**联系方式。** 在本仓库开一个 issue。
