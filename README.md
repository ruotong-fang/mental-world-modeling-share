# Mental World Modeling 组内分享

一个无后端、无 CDN 依赖的交互式论文解读网页。内容从完整故事开始，逐步解释心理状态、Mental World Modeling、MENTIS、实验结果和业务启发。

## 运行

直接打开 `dist/index.html`，或在项目根目录执行：

```bash
python3 -m http.server 8080 -d dist
```

然后访问 `http://localhost:8080`。

## 快捷键

- 页面内滚动：阅读当前页完整内容
- `←` / `→`：切换页面
- `O`：目录总览
- `F`：全屏
- `Esc`：关闭原文证据或目录

## 修改内容

- 页面主内容与逐页出处：`dist/storyContent.js`
- 页面渲染与导航：`dist/story.js`
- 基础视觉样式：`dist/styles.css`
- 长文阅读与响应式样式：`dist/reading.css`
- 网页内引用的论文：`dist/mental-world-modeling.pdf`

网页会区分论文结果、教学例子和业务建议，避免把业务推演写成论文已经验证的结论。
