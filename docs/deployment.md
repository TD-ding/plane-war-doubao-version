# 部署说明

## 运行方式

纯静态 HTML5 游戏，不需要安装任何依赖或构建工具。

### 方式一：直接打开

双击 `index.html` 文件，用浏览器打开即可。

### 方式二：本地服务器

```bash
# Python 3
python3 -m http.server 8091

# Node.js
npx serve .
```

然后访问 `http://localhost:8091/index.html`。

## 浏览器要求

- Chrome 60+
- Firefox 60+
- Safari 12+
- Edge 79+

需要支持 HTML5 Canvas API。
