# Hover on Pic - 3D 波纹效果

一个使用 Three.js 创建的交互式图片悬停波纹效果项目。当鼠标悬停在图片上时，会产生美丽的 3D 波纹动画效果。

## ✨ 特性

- 🎨 **3D 波纹效果** - 使用 WebGL 着色器实现的动态波纹动画
- 🖱️ **交互式体验** - 鼠标悬停触发波纹效果
- 📱 **响应式设计** - 自动适应不同屏幕尺寸
- ⚡ **高性能** - 基于 Three.js 的硬件加速渲染
- 🎯 **简单易用** - 纯前端实现，无需后端服务

## 🚀 在线演示

**项目链接：** [https://hoveronpic.vercel.app](https://hoveronpic.vercel.app)

## 🛠️ 技术栈

- **Three.js** - 3D 图形库
- **WebGL Shaders** - 自定义着色器效果
- **HTML5 Canvas** - 渲染画布
- **JavaScript ES6+** - 现代 JavaScript 语法

## 📁 项目结构

```
hover_on_pic/
├── index.html          # 主页面文件
├── package.json        # 项目配置
├── vercel.json         # Vercel 部署配置
├── public/             # 静态资源目录
│   └── 1.png          # 示例图片
├── 1.png              # 根目录图片
└── README.md          # 项目说明文档
```

## 🎮 使用方法

1. **本地运行**
   ```bash
   # 克隆项目
   git clone https://github.com/fffshiyu/hoveronpic_.git
   
   # 进入项目目录
   cd hoveronpic_
   
   # 安装依赖
   npm install
   
   # 启动开发服务器
   npm run dev
   ```

2. **直接访问**
   - 打开 `index.html` 文件即可在浏览器中查看效果

## 🎨 效果说明

- **波纹动画**：鼠标悬停时会在图片上产生从中心向外扩散的波纹
- **动态着色器**：使用自定义 fragment shader 实现波纹扭曲效果
- **平滑过渡**：波纹效果具有自然的衰减和过渡动画
- **实时交互**：每次鼠标移动都会触发新的波纹效果

## 🔧 自定义配置

您可以通过修改 `index.html` 中的参数来自定义效果：

```javascript
// 波纹参数调整
ripple = sin(dist*50.0 - t*6.0) * 0.02 * mask * (1.0 - t/0.8);
// 调整波纹频率、强度、持续时间等
```

## 📦 部署

### Vercel 部署
项目已配置 Vercel 部署，可以直接部署到 Vercel：

1. 将代码推送到 GitHub
2. 在 Vercel 中导入项目
3. 自动部署完成

### 其他平台
- **Netlify**：拖拽项目文件夹到 Netlify
- **GitHub Pages**：启用 GitHub Pages 功能
- **自建服务器**：上传文件到任何静态文件服务器

## 🤝 贡献

欢迎提交 Issue 和 Pull Request 来改进这个项目！

## 📄 许可证

MIT License - 详见 [LICENSE](LICENSE) 文件

## 👨‍💻 作者

- GitHub: [@fffshiyu](https://github.com/fffshiyu)

---

⭐ 如果这个项目对您有帮助，请给个 Star 支持一下！
