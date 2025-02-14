# Cursor 账号管理工具

[English](README.EN.md) | 简体中文

> 本项目是基于 [@wqjuser](https://github.com/wqjuser) 的 Cursor 账号管理工具的修改版本。

## ⚠️ 免责声明

本项目仅供学习和研究使用，旨在研究 Cursor IDE 的设备标识机制。**强烈建议购买 [Cursor](https://cursor.sh/) 正版授权**以支持开发者。

使用本工具可能存在以下风险：
- 违反 Cursor 使用条款
- 账号被封禁
- 软件授权失效
- 其他未知风险

如果您认可 Cursor 的价值，请支持正版，为软件开发者的工作付费。

## 重要提示

1. 本工具完全免费，请勿用于商业用途或销售
2. 普通用户请勿使用功能4（批量注册），需要专业代理配置

## 使用说明

### Windows用户
1. 从右侧 Releases 下载最新版本的 `CursorPro.exe`
2. 双击运行，程序会自动申请管理员权限

### Mac用户
1. 从右侧 Releases 下载最新版本的 `CursorPro`
2. 打开终端，进入下载目录
3. 执行以下命令：
```bash
chmod +x CursorPro
sudo ./CursorPro
```

## 功能说明

### 1. 一键注册并享用
- 自动注册新账号并登录
- 自动修改必要文件
- 需要已安装Chrome浏览器
- 需要已登录过任意Cursor账号

### 2. 仅修改文件
- 仅修改必要文件
- 不会注册新账号
- 适合已有账号的用户

### 3. 恢复原始文件
- 恢复到修改前的状态
- 用于修改失败时回退

### 4. 随机批量注册（⚠️ 仅限高级用户）
- 需要配置代理软件（支持Clash/V2rayN）
- 需要正确配置代理参数
- 普通用户请勿使用此功能

## 注意事项

1. 首次使用需要管理员权限
2. 使用功能4时：
   - Clash用户需要启用外部控制
   - V2rayN用户需要开启HTTP代理

## 常见问题

1. 程序无法运行
   - Windows用户请右键以管理员身份运行
   - Mac用户请使用sudo运行

2. 功能1无法使用
   - 确保已安装Chrome浏览器
   - 确保曾经登录过Cursor账号

3. 功能4连接失败
   - 检查代理软件是否正常运行
   - 确认代理配置是否正确

## 免责声明

本工具仅供学习和研究使用，请勿用于商业用途。使用本工具所产生的一切后果由使用者自行承
担。

项目基于以下开源项目：
- 原始整合项目：[@wqjuser](https://github.com/wqjuser)
- [cursor-auto-free](https://github.com/chengazhen/cursor-auto-free) - 作者：[@chengazhen](https://github.com/chengazhen)
- [cursor-reset](https://github.com/hamflx/cursor-reset) - 作者：[@hamflx](https://github.com/hamflx)
- 文件修改功能：[crazy](https://linux.do/t/topic/404579)

## 许可证

MIT License

