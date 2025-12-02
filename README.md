# 魔法六芒星阵 - 手势互动 | Arcane Hexagram - Gesture Interaction

[![GitHub license](https://img.shields.io/github/license/LiYuxuan/magic)](https://github.com/LiYuxuan/magic/blob/main/LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/LiYuxuan/magic?style=social)](https://github.com/LiYuxuan/magic)
[![GitHub forks](https://img.shields.io/github/forks/LiYuxuan/magic?style=social)](https://github.com/LiYuxuan/magic)

一个基于Three.js和MediaPipe的交互式魔法阵演示，支持手势识别和粒子动画。

An interactive magic circle demonstration based on Three.js and MediaPipe, supporting gesture recognition and particle animation.

## 在线演示 | Live Demo

[https://liyuxuan.github.io/magic/](https://liyuxuan.github.io/magic/)

## 功能特点 | Features

### 中文 | Chinese
- 🖐️ **手势识别**：使用MediaPipe识别手部动作，支持单手和双手交互
- ✨ **粒子动画**：基于Three.js的高性能粒子系统，支持45,000个粒子同时渲染
- 🎨 **多种形态**：球体、坍缩、六芒星阵、复杂魔法阵等多种视觉效果
- 🔄 **实时交互**：通过手势控制旋转、缩放和形态切换
- 📱 **响应式设计**：支持桌面和移动设备

### English
- 🖐️ **Gesture Recognition**: Hand gesture detection using MediaPipe, supporting both single and dual hand interaction
- ✨ **Particle Animation**: High-performance particle system based on Three.js, supporting 45,000 particles rendered simultaneously
- 🎨 **Multiple Forms**: Various visual effects including sphere, collapse, hexagram, and complex magic circle
- 🔄 **Real-time Interaction**: Control rotation, scaling, and form switching through gestures
- 📱 **Responsive Design**: Support for desktop and mobile devices

## 使用方法 | How to Use

### 中文 | Chinese
1. 点击"启动魔法阵"按钮，允许浏览器访问摄像头
2. 将手放入摄像头画面中
3. 尝试以下手势：
   - 张开手掌 → 握拳：触发聚能坍缩效果
   - 保持握拳 → 张开手掌：释放六芒星阵
   - 在六芒星状态下，单指左右移动控制旋转，两指开合控制缩放
   - 双手拉开：触发高阶魔法阵
4. 按键盘"R"键可重置到初始状态

### English
1. Click the "启动魔法阵" button and allow browser camera access
2. Place your hand in front of the camera
3. Try the following gestures:
   - Open palm → Fist: Trigger energy collapse effect
   - Hold fist → Open palm: Release hexagram formation
   - In hexagram state, move index finger left/right to control rotation, pinch to control scaling
   - Pull hands apart: Trigger advanced magic circle
4. Press "R" key to reset to initial state

## 技术栈 | Technology Stack

- **Three.js** - 3D图形渲染库
- **MediaPipe** - 手势识别库
- **HTML5** - 页面结构
- **CSS3** - 样式设计
- **JavaScript** - 交互逻辑

## 安装与运行 | Installation & Running

### 本地运行 | Local Development
```bash
# 克隆仓库
git clone https://github.com/LiYuxuan/magic.git
cd magic

# 使用任意HTTP服务器运行（需要HTTPS环境以访问摄像头）
# 使用Python
python -m http.server 8000

# 或使用Node.js
npx http-server -p 8000 -S

# 访问 https://localhost:8000
```

### GitHub Pages部署 | GitHub Pages Deployment
本项目已配置为可直接在GitHub Pages上运行，无需额外配置。

This project is configured to run directly on GitHub Pages without additional configuration.

## 浏览器兼容性 | Browser Compatibility

- Chrome 88+
- Firefox 85+
- Safari 14+
- Edge 88+

注意：需要HTTPS环境才能访问摄像头。

Note: HTTPS environment is required to access the camera.

## 项目结构 | Project Structure

```
magic/
├── index.html          # 主页面文件 | Main page file
└── README.md           # 项目说明 | Project documentation
```

## 贡献 | Contributing

欢迎提交Issue和Pull Request！

Welcome to submit Issues and Pull Requests!

## 许可证 | License

本项目采用MIT许可证 - 查看 [LICENSE](LICENSE) 文件了解详情。

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 作者 | Author

Li Yuxuan - [GitHub](https://github.com/LiYuxuan)

## 致谢 | Acknowledgments

- [Three.js](https://threejs.org/) - 优秀的3D图形库
- [MediaPipe](https://mediapipe.dev/) - 强大的手势识别解决方案