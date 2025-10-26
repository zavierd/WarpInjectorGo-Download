# 📥 Warp Token Injector - 下载页面

> [![最新版本](https://img.shields.io/github/v/release/zavierd/WarpInjectorGo-Download)](https://github.com/zavierd/WarpInjectorGo-Download/releases/latest) | [![下载次数](https://img.shields.io/github/downloads/zavierd/WarpInjectorGo-Download/total)](https://github.com/zavierd/WarpInjectorGo-Download/releases)

## 🎉 v3.0.0 现代化打包系统

**重大升级 - 全新打包体验**：

### 🎨 专业应用图标
- ✅ 炫酷宇宙猫咪图标 🐱✨
- ✅ macOS: 标准 .app 应用包
- ✅ Windows: 带图标的 EXE 文件
- ✅ 完整的版本信息和元数据

### 📦 macOS 用户福音
- ✅ **专业 DMG 安装器** - 拖拽安装，就像正规应用
- ✅ 标准 .app 应用包 - 集成到 Applications
- ✅ 双击即可运行 - 无需解压 tar.gz

### 🪟 Windows 用户升级
- ✅ **带图标的可执行文件** - 专业感十足
- ✅ 文件属性完整 - 版本、公司、版权信息
- ✅ 便携 ZIP 包 - 包含所有辅助脚本

---

## 🚀 快速下载

### Windows 版本

[![下载 Windows 版本](https://img.shields.io/badge/Windows-下载-blue?style=for-the-badge&logo=windows)](https://github.com/zavierd/WarpInjectorGo-Download/releases/latest/download/WarpClient-Windows.zip)

**下载地址**（自动获取最新版）：
```
https://github.com/zavierd/WarpInjectorGo-Download/releases/latest/download/WarpClient-Windows.zip
```

**说明**: 
- 文件名: `WarpClient-Windows.zip`
- 使用 `latest` 链接自动下载最新版本

**新特性**：
- 🌟 **带炫酷图标的 EXE**
- 📋 完整版本信息（公司、版权、描述）
- 📦 极简打包（只含 exe + 简洁说明）

**ZIP 包内容**：
```
├── WarpClient.exe      # 带图标的可执行文件
└── 使用说明.txt        # 简洁使用指南
```

**系统要求**：
- Windows 10/11 (64位)
- 首次运行需要管理员权限（安装证书）

---

### macOS Intel 版本

[![下载 macOS Intel](https://img.shields.io/badge/macOS_Intel-下载-black?style=for-the-badge&logo=apple)](https://github.com/zavierd/WarpInjectorGo-Download/releases/latest/download/WarpClient-macOS-Intel.dmg)

**下载地址**（自动获取最新版）：
```
https://github.com/zavierd/WarpInjectorGo-Download/releases/latest/download/WarpClient-macOS-Intel.dmg
```

**说明**: 
- 文件名: `WarpClient-macOS-Intel.dmg`
- 适用于 **macOS 13.0+** (Intel 芯片)
- macOS 12 及以下请看 Q1 或 Q8

**新特性**：
- 🌟 **专业 DMG 安装器** - 双击挂载，拖拽安装
- 🍎 标准 .app 应用包
- 🎨 炫酷应用图标
- 📦 极简打包（只含必要文件）

**DMG 包内容**：
```
├── WarpClient.app          # 应用程序
├── Applications (快捷方式)  # 拖拽安装用
└── 使用说明.txt            # 简洁使用指南
```

**系统要求**：
- ✅ macOS 13.0+ (Intel 芯片)
- ⚠️ macOS 12 及以下：加入 QQ 群获取兼容版本（群号：1067109752）
- 首次运行可能需要右键 → 打开

---

### macOS Apple Silicon 版本

[![下载 macOS M1/M2](https://img.shields.io/badge/macOS_M1/M2/M3-下载-black?style=for-the-badge&logo=apple)](https://github.com/zavierd/WarpInjectorGo-Download/releases/latest/download/WarpClient-macOS-M1.dmg)

**下载地址**（自动获取最新版）：
```
https://github.com/zavierd/WarpInjectorGo-Download/releases/latest/download/WarpClient-macOS-M1.dmg
```

**说明**: 
- 文件名: `WarpClient-macOS-M1.dmg`
- 适用于 **macOS 11.0+** (Apple Silicon: M1/M2/M3/M4)
- 原生 ARM 编译，性能最优

**新特性**：
- 🌟 **专业 DMG 安装器** - 原生 Apple Silicon 支持
- 🍎 标准 .app 应用包
- 🎨 炫酷应用图标
- ⚡ 原生性能优化
- 📦 极简打包（只含必要文件）

**DMG 包内容**：
```
├── WarpClient.app          # 应用程序
├── Applications (快捷方式)  # 拖拽安装用
└── 使用说明.txt            # 简洁使用指南
```

**系统要求**：
- macOS 11.0+ (Apple Silicon: M1/M2/M3/M4)
- 首次运行可能需要右键 → 打开

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
- 安装证书到系统存储区（LocalMachine\Root）
- 所有 Windows 用户共享，无需重复安装
- **仅首次需要，后续无需管理员权限** ✅

#### 3. 使用步骤
```
1. 以管理员身份启动程序
2. 填写服务器地址和邮箱（或使用默认配置）
3. 点击"浏览"选择 Warp 安装路径
4. 点击"激活账号"
5. 点击"安装证书" ← 关键步骤
6. 看到"证书已安装到本地计算机"提示 ✅
7. 点击"启动服务"
8. ✅ 完成！后续无需管理员权限
```

#### 4. Windows 特别说明
- Warp 路径通常在：`C:\Users\{用户名}\AppData\Local\Programs\Warp\Warp.exe`
- 证书安装后，后续启动直接双击即可
- 包含辅助脚本：`test_cert.bat`, `remove_cert.bat`

---

### macOS 用户（新安装方式）

#### 1. 下载 DMG

根据你的系统选择：
- **macOS 13+, Intel 芯片**: `WarpClient-macOS-Intel.dmg`
- **macOS 11+, M 芯片**: `WarpClient-macOS-M1.dmg`
- **macOS 12 及以下**: 加入 QQ 群 **1067109752** 获取 `WarpClient-macOS-Intel-macOS12.dmg`

#### 2. 打开 DMG
```bash
# 双击 .dmg 文件，DMG 会自动挂载
```

#### 3. 拖拽安装
```
1. 打开 DMG 窗口
2. 将 WarpClient.app 拖拽到 Applications 文件夹
3. 完成安装！
```

#### 4. 首次运行
```bash
# 方式 1: 从 Applications 文件夹打开
# 找到 WarpClient.app，右键 → 打开（仅首次需要）

# 方式 2: 命令行移除隔离属性
xattr -d com.apple.quarantine /Applications/WarpClient.app
```

#### 5. 使用步骤
```
1. 启动 WarpClient.app
2. 填写服务器地址和邮箱（或使用默认配置）
3. 点击"激活账号"
4. 点击"安装证书"
5. 输入 macOS 密码授权
6. 点击"启动服务"
7. ✅ 完成！
```

---

## 🆕 版本历史

> 💡 **提示**: 所有下载链接自动指向最新版本，无需手动更新

### v3.0.0 (2025-10-26) - 现代化打包系统

**重大改进**:
- 🎨 专业应用图标（炫酷宇宙猫咪）
- 📦 macOS DMG 安装器（拖拽安装）
- 🪟 Windows 带图标 EXE（完整版本信息）
- 🏗️ 项目结构重组和清理
- 📚 完善的构建文档
- ✨ 极简打包（移除所有冗余文件）

**打包内容简化**:
- Windows: 只含 `WarpClient.exe` + `使用说明.txt`
- macOS: 只含 `WarpClient.app` + `Applications` + `使用说明.txt`
- 移除所有辅助脚本和冗长说明
- 详细文档在下载页面，避免重复

**破坏性变更**:
- 文件命名更新：`WarpClient-*.zip/dmg`
- macOS 改用 DMG（不再是 tar.gz）
- Windows EXE 嵌入图标和元数据
- 不再包含辅助脚本（test_cert.bat 等）

---

### v2.5.3 (2025-10-25) - 日志优化版

**日志策略优化**：
- ✅ 移除调试日志代码
- ✅ 日志覆盖模式（每次启动重新记录）
- ✅ 固定日志文件名（warp-injector.log）
- ✅ 减少磁盘占用

---

### v2.5.2 - 稳定性增强版

**Windows用户福音**：
- ✅ 证书智能安装（自动选择最佳位置）
- ✅ 普通用户也能正常使用
- ✅ 优先用户存储，降级系统存储

**连接稳定性优化**：
- ✅ HTTP连接池复用
- ✅ 智能重试机制（网络抖动自动恢复）
- ✅ Keep-Alive长连接

---

## 🔧 常见问题

### Q1: macOS 12 及以下版本如何获取？
**A**: 加入 QQ 群获取兼容版本
- 群号：**1067109752**
- 提供 macOS 10.13 - 12.x 兼容版本
- 或联系管理员单独获取

### Q2: macOS 提示"无法打开"或"不能与此版本的macOS配合使用"？
**A**: 首次打开需要：
1. **右键 → 打开**（推荐，绕过安全检查）
2. 或命令行移除隔离属性：
```bash
xattr -d com.apple.quarantine /Applications/WarpClient.app
```

**如果仍然提示系统版本不兼容**:
- 确认你的 macOS 版本（系统偏好设置 → 关于本机）
- macOS 13+ 下载 Intel 或 M1 版本
- macOS 12 及以下加入 QQ 群：**1067109752**

### Q3: Windows 首次启动失败？
**A**: 必须"以管理员身份运行"，用于安装系统级证书

### Q4: macOS 如何卸载？
**A**: 
```bash
# 1. 删除应用
rm -rf /Applications/WarpClient.app

# 2. 清理证书（可选）
# 在系统钥匙串中搜索 "Warp Injector"并删除
```

### Q5: 激活失败？
**A**: 检查：
- 服务器地址是否正确
- 网络连接是否正常
- 邮箱格式是否正确

### Q6: 如何清理所有数据？
**A**: 使用隐藏清理功能：
1. 快速点击底部"作者 zavier"3次
2. 确认清理
3. 重启 Warp 客户端

### Q7: 许可证过期了怎么办？
**A**: 点击"刷新有效期"按钮，同步管理员延期的最新状态

### Q8: 如何获取 macOS 12 兼容版本？
**A**: 
- 加入 QQ 群：**1067109752**
- 群文件中提供 `WarpClient-macOS-Intel-macOS12.dmg`
- 适用于 macOS 10.13 - 12.x

### Q9: Windows 图标显示问题？
**A**: v3.0.0+ 版本已内嵌图标，如果看不到：
- 检查是否下载的最新版本
- 尝试刷新文件资源管理器

---

## 💡 提示与技巧

### Windows 用户
- 📁 建议安装位置：`C:\Program Files\WarpClient\`
- 🔑 首次管理员权限仅用于安装证书
- 🔄 后续启动无需管理员权限

### macOS 用户
- 📁 标准安装位置：`/Applications/WarpClient.app`
- 🔍 可在 Spotlight 中搜索 "WarpClient"
- 🗑️ 卸载只需删除 .app 文件

---

## 📄 许可证

MIT License

---

**下载即用，开箱即用！** 🎉

---

## 🔗 相关链接

- [GitHub 主仓库](https://github.com/zavierd/WarpInjectorGo)
- [构建指南](https://github.com/zavierd/WarpInjectorGo/blob/main/BUILD.md)
- [项目结构](https://github.com/zavierd/WarpInjectorGo/blob/main/PROJECT_STRUCTURE.md)
- [更新日志](https://github.com/zavierd/WarpInjectorGo/releases)
