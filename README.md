# Mental World Modeling 组内分享

一个无后端、无 CDN 依赖的 16:9 交互式演示网页。

## 运行

直接打开 `dist/index.html`，或在项目根目录执行：

```bash
python3 -m http.server 8080 -d dist
```

然后访问 `http://localhost:8080`。

## 快捷键

- `←` / `↑`：上一页
- `→` / `↓` / `Space`：下一页
- `O`：目录总览
- `F`：全屏
- `Esc`：关闭原文证据或目录

## 修改内容

- 页面主内容：`dist/app.js` 中的 `slides`
- 论文原文、页码与中文解读：`dist/paperEvidence.js`
- 视觉样式：`dist/styles.css`

所有产品延展与架构提议均应标记为「我们的推论」，不应写成论文已验证的结论。
