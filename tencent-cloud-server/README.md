# Tencent Cloud Server

连接用户的腾讯云服务器，用于管理 OpenClash 和其他服务。

## 服务器信息

- **IP**: 43.167.159.119
- **用户**: root
- **系统**: OpenCloudOS
- **连接方式**: SSH 密钥认证（已配置）

## 连接命令

```bash
ssh root@43.167.159.119
```

## 服务

### OpenClaw
AI Agent 管理框架，支持聊天频道（Telegram、Discord）、浏览器自动化、网关服务。
- 版本：2026.3.2
- 需要先加载 nvm：`source ~/.nvm/nvm.sh`
- 常用命令：`openclaw gateway start`、`openclaw doctor`、`openclaw dashboard`

### 网站
服务器上托管了另一个网站（具体待确认）。

## 使用方式

当用户要求：
- "连接云服务器"
- "连接服务器"
- "连上服务器"
- "OpenClaw"
- "查看代理"
- "查看 OpenClaw 状态"

直接执行 SSH 连接：
```bash
ssh root@43.167.159.119
```

## 常用命令

连接后可执行：

```bash
# 查看系统资源
htop

# 查看磁盘
df -h

# 查看 Docker 容器（如有）
docker ps
```