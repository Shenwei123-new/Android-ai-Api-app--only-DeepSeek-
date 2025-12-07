# AllCanDo - AI Assistant

[中文版](#allcando---ai-智能助手)

A powerful Android AI assistant app that integrates DeepSeek AI conversation, code programming, file management, and various practical tools.

## 📱 App Info

- **App Name**: AllCanDo
- **Package**: `com.ai.allcando`
- **Author**: Li Yang
- **Version**: v1.0.0
- **Min SDK**: 24 (Android 7.0)
- **Target SDK**: 34 (Android 14)
- **Language**: Java

## ✨ Features

### 🤖 AI Chat
- Integrated DeepSeek AI large language model
- Streaming response with real-time display
- Reasoning model support (shows thinking process)
- Chat history saving and search
- Multiple AI tool calls (file read/write, web search, calculator, etc.)

### 💻 IDE Programming Environment
- Built-in code editor with syntax highlighting
- AI programming assistant for automatic code modification
- Support for Python, Java, JavaScript, and more
- Code diff comparison and one-click apply
- Code undo functionality
- AI generation interrupt feature

### 📁 File Manager
- Dual-panel file browsing
- Copy, move, delete, rename operations
- Multi-select mode with swipe gesture
- Built-in image viewer and video player
- APK file extraction and browsing
- Path input and copy functionality
- Smooth operation animations

### 🔐 APK Signing Tool
- Support for BKS and JKS keystore formats
- Create and import keystores
- V1 signature scheme support
- View and verify APK signature info
- Remove APK signatures

### 📷 QR Code Tool
- Generate QR codes (supports Chinese)
- Scan QR codes (camera/image)
- Save and share QR codes

### 🛠️ Other Tools
- **Python Console**: Run Python code
- **Unit Converter**: Length, weight, temperature conversions
- **Color Picker**: RGB/HEX color selection
- **APK Extractor**: Extract installed app APKs
- **Hash Calculator**: MD5, SHA1, SHA256 calculation
- **Base64 Tool**: Encode/decode conversion
- **Device Info**: View device details

### 🎬 Media Playback
- **Video Player**: Fullscreen, speed control (0.5x-3.0x)
- **Image Viewer**: Zoom, rotate, fullscreen browsing

## 📂 Project Structure

```
├── app/
│   ├── src/main/
│   │   ├── java/com/ai/allcando/
│   │   │   ├── ui/                    # Activity screens
│   │   │   ├── data/                  # Data models and repositories
│   │   │   ├── network/               # Network services
│   │   │   ├── tools/                 # Tool classes
│   │   │   └── utils/                 # Utility methods
│   │   ├── res/
│   │   │   ├── layout/                # Layout files
│   │   │   ├── values/                # Strings, colors, themes
│   │   │   ├── values-zh/             # Chinese translations
│   │   │   ├── drawable/              # Icon resources
│   │   │   └── anim/                  # Animation resources
│   │   └── AndroidManifest.xml
│   └── build.gradle.kts
├── gradle/
└── build.gradle.kts
```

## 🔧 Development Environment

- **Android Studio**: Arctic Fox (2020.3.1) or higher
- **JDK**: 17 or higher
- **Gradle**: 8.2

## 📦 Main Dependencies

- AndroidX Core & AppCompat
- Material Design 3
- ConstraintLayout
- Lifecycle Components (ViewModel, LiveData)
- Room Database
- OkHttp & Gson
- BouncyCastle (Cryptography)
- ZXing (QR Code)
- Chaquopy (Python Runtime)

## 🚀 Getting Started

1. Clone the project
2. Open with Android Studio
3. Wait for Gradle sync
4. Configure DeepSeek API Key in Settings
5. Connect device or start emulator
6. Run the app

## 📝 Configuration

### API Configuration
The app uses DeepSeek API, configure in Settings:
- **API Key**: Your DeepSeek API key
- **Model**: deepseek-chat / deepseek-reasoner

### Permissions
- `INTERNET`: Network access (AI chat)
- `READ/WRITE_EXTERNAL_STORAGE`: File management
- `MANAGE_EXTERNAL_STORAGE`: Full file access
- `CAMERA`: QR code scanning
- `QUERY_ALL_PACKAGES`: APK extraction
- `REQUEST_INSTALL_PACKAGES`: APK installation

## 🎨 UI Features

- Material Design 3 modern design
- Multi-language support (Chinese/English)
- Smooth animations
- Fullscreen immersive experience

## 📄 License

This project is licensed under the [Apache License 2.0](LICENSE).

```
Copyright 2024 Li Yang

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```

## 👤 Author

**Li Yang**

## 🤝 Contributing

Contributions, issues and feature requests are welcome!

Feel free to check [issues page](../../issues).

## ⭐ Show Your Support

Give a ⭐ if this project helped you!

---

# AllCanDo - AI 智能助手

一款功能强大的 Android AI 助手应用，集成了 DeepSeek AI 对话、代码编程、文件管理等多种实用工具。

## 📱 应用信息

- **应用名称**: AllCanDo
- **包名**: `com.ai.allcando`
- **作者**: Li Yang
- **版本**: v1.0.0
- **最低 SDK**: 24 (Android 7.0)
- **目标 SDK**: 34 (Android 14)
- **开发语言**: Java

## ✨ 主要功能

### 🤖 AI 对话
- 集成 DeepSeek AI 大语言模型
- 支持流式响应，实时显示回答
- 支持推理模型（显示思考过程）
- 聊天历史记录保存和搜索
- 支持多种 AI 工具调用（文件读写、网页搜索、计算器等）

### 💻 IDE 编程环境
- 内置代码编辑器，支持语法高亮
- AI 编程助手，可自动修改代码
- 支持 Python、Java、JavaScript 等多种语言
- 代码对比和一键应用修改
- 代码撤销功能
- AI 生成中断功能

### 📁 文件管理器
- 双面板文件浏览
- 支持复制、移动、删除、重命名等操作
- 多选模式和滑动选择手势
- 内置图片查看器和视频播放器
- APK 文件解压浏览
- 路径输入和复制功能
- 流畅的操作动画

### 🔐 APK 签名工具
- 支持 BKS 和 JKS 密钥库格式
- 创建和导入密钥库
- V1 签名方案支持
- 查看和验证 APK 签名信息
- 移除 APK 签名

### 📷 二维码工具
- 生成二维码（支持中文）
- 扫描二维码（相机/图片）
- 保存和分享二维码

### 🛠️ 其他工具
- **Python 控制台**: 运行 Python 代码
- **单位转换器**: 长度、重量、温度等转换
- **颜色选择器**: RGB/HEX 颜色选取
- **APK 提取器**: 提取已安装应用的 APK
- **哈希计算器**: MD5、SHA1、SHA256 计算
- **Base64 工具**: 编码/解码转换
- **设备信息**: 查看设备详细信息

### 🎬 媒体播放
- **视频播放器**: 全屏播放、倍速支持（0.5x-3.0x）
- **图片查看器**: 缩放、旋转、全屏浏览

## 📂 项目结构

```
├── app/
│   ├── src/main/
│   │   ├── java/com/ai/allcando/
│   │   │   ├── ui/                    # Activity 界面
│   │   │   ├── data/                  # 数据模型和仓库
│   │   │   ├── network/               # 网络服务
│   │   │   ├── tools/                 # 工具类
│   │   │   └── utils/                 # 工具方法
│   │   ├── res/
│   │   │   ├── layout/                # 布局文件
│   │   │   ├── values/                # 字符串、颜色、主题
│   │   │   ├── values-zh/             # 中文翻译
│   │   │   ├── drawable/              # 图标资源
│   │   │   └── anim/                  # 动画资源
│   │   └── AndroidManifest.xml
│   └── build.gradle.kts
├── gradle/
└── build.gradle.kts
```

## 🔧 开发环境

- **Android Studio**: Arctic Fox (2020.3.1) 或更高版本
- **JDK**: 17 或更高版本
- **Gradle**: 8.2

## 📦 主要依赖

- AndroidX Core & AppCompat
- Material Design 3
- ConstraintLayout
- Lifecycle Components (ViewModel, LiveData)
- Room Database
- OkHttp & Gson
- BouncyCastle (加密库)
- ZXing (二维码)
- Chaquopy (Python 运行时)

## 🚀 开始使用

1. 克隆项目到本地
2. 使用 Android Studio 打开项目
3. 等待 Gradle 同步完成
4. 在设置中配置 DeepSeek API Key
5. 连接设备或启动模拟器
6. 运行应用

## 📝 配置说明

### API 配置
应用使用 DeepSeek API，需要在设置中配置：
- **API Key**: 您的 DeepSeek API 密钥
- **模型选择**: deepseek-chat / deepseek-reasoner

### 权限说明
- `INTERNET`: 网络访问（AI 对话）
- `READ/WRITE_EXTERNAL_STORAGE`: 文件管理
- `MANAGE_EXTERNAL_STORAGE`: 完整文件访问
- `CAMERA`: 二维码扫描
- `QUERY_ALL_PACKAGES`: APK 提取
- `REQUEST_INSTALL_PACKAGES`: APK 安装

## 🎨 界面特性

- Material Design 3 现代设计
- 支持明暗主题自动切换
- 多语言支持（中文/英文）
- 流畅的动画效果
- 全屏沉浸式体验

## 📄 许可证

本项目采用 [Apache License 2.0](LICENSE) 许可证。

```
Copyright 2024 Li Yang

根据 Apache License 2.0 版本（"许可证"）授权；
除非遵守许可证，否则您不得使用此文件。
您可以在以下网址获取许可证副本：

    http://www.apache.org/licenses/LICENSE-2.0

除非适用法律要求或书面同意，否则根据许可证分发的软件
按"原样"分发，不附带任何明示或暗示的保证或条件。
请参阅许可证以了解管理权限和限制的特定语言。
```

## 👤 作者

**Li Yang**

## 🤝 贡献

欢迎贡献代码、提交 Issue 和功能请求！

请查看 [Issues 页面](../../issues)。

## ⭐ 支持项目

如果这个项目对您有帮助，请给一个 ⭐ 星标！

---

📧 如有问题或建议，欢迎提交 Issue！
