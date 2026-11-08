# 便捷式 DeepSeek 破甲程序 · 一键启动

便携版 DSH（DeepSeek Harness）破甲/清洗一键安装程序。双击即装，无需配置环境。

## 一键启动

1. 下载右侧 **Releases** 里的 `DSH-Setup.exe`（或直接取仓库根目录同名文件）
2. 双击运行，按向导下一步
3. 安装完成后重启 DSH 宿主，改动即生效

## 文件校验

| 项 | 值 |
|---|---|
| 文件名 | `DSH-Setup.exe` |
| 大小 | 2,219,008 字节（2.12 MB） |
| SHA256 | `6C9AE1D5B88397231AD46204728EC2CF86B77FAEB4D84794A79E47BA16A78BD8` |
| 平台 | Windows x64 |

PowerShell 校验：

```powershell
Get-FileHash .\DSH-Setup.exe -Algorithm SHA256
```

## 系统要求

- Windows 10 / 11 x64
- 已安装 DeepSeek Harness（dsh）宿主
- 安装后需完整重启 dsh 使补丁生效

## 卸载 / 回滚

安装器会保留原始文件备份，卸载时按其卸载项还原；手动回滚请使用与版本号对应的 `purge_revert` 流程。

## 免责

本仓库仅用于本地环境自用与备份，按原样提供，不附带任何担保。
