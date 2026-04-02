# Misstar Tools R2D 🛠️

小米路由器 R2D 的 Misstar Tools（MT工具箱）离线插件合集。

> ⚠️ 注意：目前 GitHub 上几乎找不到可用的 MT 工具箱资源了，本仓库为离线安装版，解压即用。

## 📦 包含插件

| 插件文件名 | 说明 |
|-----------|------|
| `koolproxy` | Koolproxy 广告过滤 |
| `ss` | 代理插件 |
| `kms` | KMS 激活服务器 |
| `ftp` | VSFTP 服务器 |
| `aliddns` | 阿里云域名解析 |
| `pptpd` | PPTP VPN 服务器 |
| `adm` | 阿呆喵广告过滤 |
| `webshell` | 在线 Shell |
| `rm` | 远程管理 |
| `wake` / `wake(仅输入)` | 网络唤醒 |

## 🚀 安装方法

### 1. 离线安装（推荐）

1. 下载本仓库，将 `R2D` 目录和 `offline_install.sh` 复制到路由器硬盘
2. SSH 登录路由器后执行：

```bash
cd /extdisks/sda1
chmod +x offline_install.sh
./offline_install.sh
```

### 2. 手动安装单个插件

```bash
# 安装
/etc/misstar/scripts/appmanager add ftp
/etc/misstar/scripts/appmanager add kms
/etc/misstar/scripts/appmanager add koolproxy

# 卸载
/etc/misstar/scripts/appmanager del ftp
```

## 🙏 致谢

- 感谢 @Mi_140164255 制作离线版插件
- 感谢四爷把离线文件上传到论坛

## ⚖️ 免责声明

本仓库仅供学习交流使用，请勿用于商业用途。
