# Markdown 格式转换器

一个纯前端的 Markdown 双向格式转换工具，无需后端，开箱即用。

## ✨ 功能

- **Markdown → 预览**：实时渲染 Markdown，支持代码高亮、GFM 表格、任务列表
- **富文本 → Markdown**：粘贴网页/Word 带格式内容，自动转为 Markdown
- **PDF → Markdown**：上传 PDF 文件，智能解析为 Markdown 格式
- **导出 PDF**：将当前内容导出为排版精美的 PDF 文件
- **一键复制**：快速复制转换结果

## 🚀 在线使用

访问：[https://ycyliu.github.io/markdown-converter/](https://ycyliu.github.io/markdown-converter/)

## 🛠 技术栈

- [marked.js](https://github.com/markedjs/marked) - Markdown 解析
- [Turndown](https://github.com/mixmark-io/turndown) - HTML 转 Markdown
- [highlight.js](https://highlightjs.org/) - 代码高亮
- [PDF.js](https://mozilla.github.io/pdf.js/) - PDF 解析
- [html2pdf.js](https://github.com/eKoopmans/html2pdf.js) - PDF 导出

## 📦 本地运行

```bash
# 克隆仓库
git clone https://github.com/ycyliu/markdown-converter.git

# 任意静态服务器启动
cd markdown-converter
python3 -m http.server 8080
# 访问 http://localhost:8080
```

## ⌨️ 快捷键

| 快捷键 | 功能 |
|--------|------|
| `Cmd/Ctrl + S` | 导出 PDF |
| `Cmd/Ctrl + Shift + C` | 复制结果 |

## 📄 License

MIT
