# 📥 Warp Token Injector - 下载页面

> 最新版本：**v2.5.3** | 更新时间：2025-10-25

## 🎉 v2.5.2 稳定性增强版

**Windows用户福音 - 无需管理员权限**：
- ✅ 证书智能安装（自动选择最佳位置）
- ✅ 普通用户也能正常使用
- ✅ 优先用户存储，降级系统存储

**连接稳定性优化（v2.5.1）**：
- ✅ HTTP连接池复用
- ✅ 智能重试机制（网络抖动自动恢复）
- ✅ Keep-Alive长连接

**AI流式传输（v2.5.0）**：
- ✅ 端到端流式传输（零延迟）
- ✅ AI对话立即开始逐字输出
- ✅ 性能最优化

---

## 🚀 快速下载

### Windows 版本

[![下载 Windows 版本](https://img.shields.io/badge/Windows-下载-blue?style=for-the-badge&logo=windows)](https://github.com/zavierd/WarpInjectorGo-Download/releases/latest/download/warp-injector-windows-amd64.zip)

**下载地址**：
```
https://github.com/zavierd/WarpInjectorGo-Download/releases/latest/download/warp-injector-windows-amd64.zip
```

**系统要求**：
- Windows 10/11 (64位)
- 首次运行需要管理员权限（仅一次）

---

### macOS Intel 版本

[![下载 macOS Intel](https://img.shields.io/badge/macOS_Intel-下载-black?style=for-the-badge&logo=apple)](https://github.com/zavierd/WarpInjectorGo-Download/releases/latest/download/warp-injector-macos-intel.tar.gz)

**下载地址**：
```
https://github.com/zavierd/WarpInjectorGo-Download/releases/latest/download/warp-injector-macos-intel.tar.gz
```

**系统要求**：
- macOS 10.15+ (Intel 芯片)
- 首次运行需要移除隔离属性

---

### macOS Apple Silicon 版本

[![下载 macOS M1/M2](https://img.shields.io/badge/macOS_M1/M2-下载-black?style=for-the-badge&logo=apple)](https://github.com/zavierd/WarpInjectorGo-Download/releases/latest/download/warp-injector-macos-m1.tar.gz)

**下载地址**：
```
https://github.com/zavierd/WarpInjectorGo-Download/releases/latest/download/warp-injector-macos-m1.tar.gz
```

**系统要求**：
- macOS 11.0+ (Apple Silicon: M1/M2/M3)
- 首次运行需要移除隔离属性

---

## 📖 使用指南

### Windows 用户

#### 1. 下载和解压
```powershell
# 下载后解压到任意目录
# 例如：C:\WarpClient\
```

#### 2. 首次启动（需要管理员权限）
```powershell
# 右键点击 WarpClient.exe
# 选择"以管理员身份运行"
```

**为什么需要管理员？**
- 安装证书到系统存储区（所有用户共享）
- **仅首次需要，后续无需管理员权限**

#### 3. 使用步骤
```
1. 启动程序（自动填充服务器地址和邮箱）
2. 点击"激活账号"按钮
3. 激活成功后，点击"安装证书"
4. 证书装好后，点击"启动服务"
5. ✅ 完成！Warp 客户端可以正常使用
```

#### 4. Windows 特别说明
- 首次启动前需要**手动选择 Warp 客户端路径**
- 点击"浏览"按钮，找到 Warp 的安装目录
- 通常在：`C:\Users\{用户名}\AppData\Local\Programs\Warp\Warp.exe`

---

### macOS 用户

#### 1. 下载和解压
```bash
# Intel 芯片
tar -xzf warp-injector-macos-intel.tar.gz

# Apple Silicon (M1/M2/M3)
tar -xzf warp-injector-macos-m1.tar.gz
```

#### 2. 设置权限
```bash
# 移除隔离属性
xattr -d com.apple.quarantine warp-injector-macos-*

# 添加执行权限（如果需要）
chmod +x warp-injector-macos-*
```

#### 3. 启动程序
```bash
# Intel 芯片
./warp-injector-macos-intel

# Apple Silicon
./warp-injector-macos-m1
```

#### 4. 使用步骤
```
1. 启动程序（自动填充服务器地址和邮箱）
2. 点击"激活账号"按钮
3. 激活成功后，点击"安装证书"
4. 证书装好后，点击"启动服务"
5. ✅ 完成！Warp 客户端可以正常使用
```


## 🔧 常见问题

### Q1: Windows 首次启动失败？
**A**: 必须"以管理员身份运行"，用于安装系统级证书

### Q2: macOS 提示"无法打开"？
**A**: 运行命令移除隔离属性：
```bash
xattr -d com.apple.quarantine WarpClient-macOS
```

### Q3: 激活失败？
**A**: 检查：
- 服务器地址是否正确
- 网络连接是否正常
- 邮箱格式是否正确

### Q4: 如何清理所有数据？
**A**: 使用隐藏清理功能：
1. 快速点击底部"作者 zavier"3次
2. 确认清理
3. 重启 Warp 客户端

### Q5: 许可证过期了怎么办？
**A**: 点击"刷新有效期"按钮，同步管理员延期的最新状态

---

## 📄 许可证

MIT License

---

**下载即用，开箱即用！** 🎉

---

## 🔗 相关链接

- [GitHub 仓库](https://github.com/zavierd/WarpInjectorGo)
- [完整文档](https://github.com/zavierd/WarpInjectorGo/blob/main/README.md)
- [更新日志](https://github.com/zavierd/WarpInjectorGo/blob/main/CHANGELOG.md)
- [UI优化说明](https://github.com/zavierd/WarpInjectorGo/blob/main/UI_OPTIMIZATION_SUMMARY.md)

