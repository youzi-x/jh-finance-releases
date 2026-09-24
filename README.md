# 惊鸿财务管理系统 · 官方安装包发布与在线升级通道

![Version](https://img.shields.io/badge/version-v1.0.0-blue.svg)
![Platform](https://img.shields.io/badge/platform-Windows%2064--bit-brightgreen.svg)
![License](https://img.shields.io/badge/license-Commercial-orange.svg)

企业级全功能财务管理系统，支持多账套物理隔离、凭证填制与审核记账、科目账表、现金流量表、固定资产折旧核算、期末自动损益结转，以及畅捷通 T+ 风格的多周期自动化灾备快照与一键恢复。

---

## 🚀 客户端安装包高速下载 (v1.0.0 正式版)

| 下载线路 | 安装包文件名 | 下载链接 | 推荐指数 |
| :--- | :--- | :--- | :--- |
| **国内加速线路 1** | `JingHongFinance_Setup_v1.0.0.exe` | [点击高速下载 (ghproxy 节点)](https://ghproxy.net/https://github.com/youzi-x/jh-finance-releases/releases/download/v1.0.0/JingHongFinance_Setup_v1.0.0.exe) | ⭐⭐⭐⭐⭐ (国内首选) |
| **国内加速线路 2** | `JingHongFinance_Setup_v1.0.0.exe` | [点击高速下载 (gh-proxy 节点)](https://gh-proxy.com/https://github.com/youzi-x/jh-finance-releases/releases/download/v1.0.0/JingHongFinance_Setup_v1.0.0.exe) | ⭐⭐⭐⭐⭐ (备用高速) |
| **国内镜像线路 3** | `JingHongFinance_Setup_v1.0.0.exe` | [点击高速下载 (gitmirror 节点)](https://raw.gitmirror.com/youzi-x/jh-finance-releases/releases/download/v1.0.0/JingHongFinance_Setup_v1.0.0.exe) | ⭐⭐⭐⭐ (电信联通) |
| **GitHub 官方源** | `JingHongFinance_Setup_v1.0.0.exe` | [GitHub Releases 直链](https://github.com/youzi-x/jh-finance-releases/releases/download/v1.0.0/JingHongFinance_Setup_v1.0.0.exe) | ⭐⭐⭐ (海外用户) |

- **安装包大小**: 约 145 MB
- **安装包 MD5 校验码**: `67017eb6781310c8c597d8cfbb9148db`

---

## 🛠️ 安装与快速上手说明

1. **一键安装**:
   - 下载并双击运行 `JingHongFinance_Setup_v1.0.0.exe`；
   - 点击“下一步”，选择安装目录（推荐 `D:\JingHongFinance` 或 `C:\JingHongFinance`）；
   - 点击“一键安装”，等待解压部署完毕即可。

2. **服务管理器功能**:
   - 安装完成后自动生成桌面图标 **【财务系统服务管理器】**；
   - **服务管理**: 支持一键启动/停止/重启全部核心微服务、数据库服务与缓存服务，实时监控运行状态；
   - **端口管理**: 支持自由修改 Web/API 服务端口（默认 80）、MySQL 端口（默认 3307），智能检测端口占用冲突；
   - **数据库配置 (分离部署)**:
     - **本地一体化模式**: 使用系统自带的 MySQL 5.7 便携运行时；
     - **分离部署模式**: 支持连接企业现有局域网或云端 MySQL 服务器，提供一键测试连接与数据结构同步；
   - **在线智能更新**: 内置国内多镜像加速通道，点击“立即检查在线新版本”即可一键热更新，自动备份与无损热升级。

3. **系统登录凭据**:
   - 快速访问地址: `http://localhost:80/`
   - **系统管理员**: 账号 `admin`，密码 `admin123`
   - **业务做账人员**: 账号 `operator`，密码 `admin123`

---

## 🔄 在线版本清单 (Version Manifest)

服务管理器自动读取并校验版本清单地址：
- 官方源: `https://raw.githubusercontent.com/youzi-x/jh-finance-releases/main/version.json`
- 国内加速源: `https://ghproxy.net/https://raw.githubusercontent.com/youzi-x/jh-finance-releases/main/version.json`
