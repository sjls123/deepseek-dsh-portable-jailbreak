# DeepSeek 破甲程序 · 便捷式 DSH 一键启动

> **破甲 / 破甲程序 / DeepSeek 破甲 / DSH 破甲 / 便携式一键启动 / one-click installer**
> Windows x64 单文件安装包 `DSH-Setup.exe`，双击即装，无需配置环境。

## 这是什么

**便捷式 DeepSeek 破甲程序**，针对 DSH（DeepSeek Harness）宿主的便携版一键安装器。
下载 `DSH-Setup.exe` → 双击 → 下一步 → 重启 DSH，补丁立即生效。

关键词：DeepSeek 破甲 · 破甲程序 · DSH 破甲 · 便携式 · 一键启动 · 一键安装 · dsh purge · deepseek jailbreak · portable installer。

## 一键启动 / Quick Start

1. 下载 [`DSH-Setup.exe`](https://github.com/sjls123/deepseek-dsh-portable-jailbreak/releases/download/v1.1.92/DSH-Setup.exe)
2. 双击运行，按向导下一步
3. 安装完成后完整重启 DSH 宿主，改动即生效

## 文件校验 / Checksum

| 项 | 值 |
|---|---|
| 文件名 | `DSH-Setup.exe` |
| 大小 | 2,219,008 字节（2.12 MB） |
| SHA256 | `6C9AE1D5B88397231AD46204728EC2CF86B77FAEB4D84794A79E47BA16A78BD8` |
| 平台 | Windows 10 / 11 x64 |

```powershell
Get-FileHash .\DSH-Setup.exe -Algorithm SHA256
```

## 系统要求

- Windows 10 / 11 x64
- 已安装 DeepSeek Harness（dsh）宿主
- 安装后需完整重启 dsh 使补丁生效

## 卸载 / 回滚

安装器保留原始文件备份，卸载时按其卸载项还原；手动回滚使用对应版本的 `purge_revert` 流程。

## 相关

- 发行包：https://github.com/sjls123/deepseek-dsh-portable-jailbreak/releases
- 问题反馈：https://github.com/sjls123/deepseek-dsh-portable-jailbreak/issues

## 免责

本仓库仅用于本地环境自用与备份，按原样提供，不附带任何担保。
