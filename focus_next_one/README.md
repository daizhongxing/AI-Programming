# 专注 1 件事 📋

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow.svg)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![HTML5](https://img.shields.io/badge/HTML5-supported-orange.svg)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-supported-blue.svg)](https://developer.mozilla.org/en-US/docs/Web/CSS)

> 一次只做一件事，提高你的专注力与生产力

一个简洁美观的任务管理应用，专注于帮助您一次只专注一件最重要的事情，避免分心，提升工作效率。

## ✨ 功能特性

### 🎯 专注模式
- **单任务聚焦**：界面突出显示当前最重要的任务
- **智能任务选择**：自动根据优先级为您选择下一个要专注的任务
- **任务跳过**：可以跳过当前任务，系统会自动选择下一个

### 📝 任务管理
- **任务创建**：添加任务名称、估算时间和优先级
- **优先级系统**：5级优先级分类（1-最高 到 5-最低）
- **时间估算**：为每个任务设置预计完成时间
- **任务编辑**：随时修改任务信息
- **任务删除**：完成或不需要的任务可以删除

### 💾 数据持久化
- **本地存储**：使用 LocalStorage 保存所有数据
- **状态恢复**：刷新页面后自动恢复之前的工作状态
- **数据安全**：所有数据存储在本地，保护隐私

### 📱 响应式设计
- **移动端优化**：完美支持手机、平板等移动设备
- **自适应布局**：界面自动适配不同屏幕尺寸
- **触摸友好**：针对触屏设备优化的交互体验

### 🎨 用户体验
- **优雅动画**：流畅的过渡动画和悬停效果
- **可折叠列表**：任务列表可以折叠，保持界面清爽
- **直观操作**：简单明了的操作流程
- **视觉优先级**：不同颜色标识任务优先级

## 🚀 快速开始

### 在线使用
1. 下载 `todo.html` 文件
2. 用任意现代浏览器打开
3. 开始添加您的第一个任务！

### 本地部署
```bash
# 克隆项目
git clone https://github.com/你的用户名/focus_next_one.git

# 进入项目目录
cd focus_next_one

# 用浏览器打开 todo.html
open todo.html  # macOS
start todo.html # Windows
xdg-open todo.html # Linux
```

## 📖 使用指南

### 1. 添加任务
1. 点击「添加任务」按钮
2. 填写任务名称（必填）
3. 设置预计耗时（分钟）
4. 选择优先级（1-5级）
5. 点击「保存」

### 2. 专注工作
- 应用会自动选择优先级最高的任务作为当前专注任务
- 专注完成后点击「完成任务」
- 如需跳过当前任务，点击「跳过任务」

### 3. 管理任务
- 点击「显示任务列表」查看所有任务
- 使用「编辑」按钮修改任务信息
- 使用「删除」按钮移除不需要的任务

### 4. 优先级说明
- **1级（红色）**：紧急且重要，最高优先级
- **2级（橙色）**：重要但不紧急
- **3级（黄色）**：一般重要性（默认）
- **4级（绿色）**：不重要但有用
- **5级（蓝色）**：最低优先级

## 🛠️ 技术栈

- **HTML5**：结构和语义化标记
- **CSS3**：样式设计和响应式布局
  - CSS Variables（自定义属性）
  - Flexbox 布局
  - CSS Grid
  - 媒体查询
  - 过渡动画
- **Vanilla JavaScript**：核心逻辑实现
  - ES6+ 语法
  - LocalStorage API
  - DOM 操作
  - 事件处理

## 📂 项目结构

```
focus_next_one/
├── todo.html          # 主应用文件（包含 HTML、CSS、JavaScript）
└── README.md          # 项目说明文档
```

## 🎯 设计理念

这个应用基于以下生产力原则设计：

1. **单任务原则**：一次只专注一件事，避免多任务切换带来的效率损失
2. **优先级驱动**：始终优先处理最重要的任务
3. **简化决策**：减少选择困难，让系统帮您决定下一步做什么
4. **时间感知**：通过时间估算培养对任务复杂度的认知
5. **渐进式完成**：通过完成小任务获得成就感，保持动力

## 🌟 特色亮点

- 🎯 **零干扰专注**：界面简洁，突出当前最重要的任务
- 🏃‍♂️ **即开即用**：无需安装，单文件部署
- 🔒 **隐私安全**：数据完全存储在本地
- 📱 **跨平台**：支持所有现代浏览器和移动设备
- 🎨 **现代设计**：优雅的 UI 设计和流畅的动画效果

## 🤝 贡献指南

欢迎您为项目做出贡献！

### 如何贡献
1. Fork 本项目
2. 创建您的特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交您的更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 打开一个 Pull Request

### 贡献类型
- 🐛 Bug 修复
- ✨ 新功能开发
- 📚 文档改进
- 🎨 UI/UX 优化
- 🔧 代码重构
- 🧪 测试添加

## 📄 许可证

本项目采用 MIT 许可证 - 查看 [LICENSE](LICENSE) 文件了解详情。

## 💡 灵感来源

这个项目受到以下生产力方法论的启发：
- **Getting Things Done (GTD)**：任务收集和优先级管理
- **番茄工作法**：专注时间块的概念
- **单任务处理**：避免多任务切换的效率损失理论

## 📞 联系方式

如果您有任何问题或建议，欢迎通过以下方式联系：

- 📧 邮箱：[710600858@qq.com](mailto:710600858@qq.com)
- 🐛 Issues：[GitHub Issues](https://github.com/daizhongxing/AI-Programming/issues)
- 💬 讨论：[GitHub Discussions](https://github.com/daizhongxing/AI-Programming/discussions)

---

⭐ 如果这个项目对您有帮助，请给它一个 Star！

*用专注力改变工作方式，一次只做一件事。* 