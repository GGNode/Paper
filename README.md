# Paper

个人论文 PDF 收藏库，用于在线存储与访问学术论文。

## 目录结构

```
Paper/
├── README.md
└── papers/         # 论文 PDF 文件存放目录
```

## 如何访问论文

所有 PDF 文件均可通过 GitHub 直接访问或下载：

- **在线预览**：点击仓库中的 PDF 文件，即可在 GitHub 上预览。
- **直接下载链接**：
  ```
  https://raw.githubusercontent.com/GGNode/Paper/main/papers/<文件名>.pdf
  ```
- **示例**：
  ```
  https://raw.githubusercontent.com/GGNode/Paper/main/papers/example.pdf
  ```

## 如何上传论文

1. 将 PDF 文件放入 `papers/` 目录。
2. 提交并推送到仓库：
   ```bash
   git add papers/<文件名>.pdf
   git commit -m "Add paper: <论文标题>"
   git push
   ```
