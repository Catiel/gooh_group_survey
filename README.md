# Gooh旅记旅行产品调研问卷工作台

这是一个无需后端的静态问卷工作台，包含：

- 单页双模块工作台：设计思路、题目说明
- 左侧展示当前问卷题目与选项样式，右侧逐题解释
- 每道题对应展示调研目的、题型原因和产品决策价值
- 每个选项与其代表含义逐行对齐
- 完整问卷和单题复制

## 本地预览

直接打开 `index.html` 即可使用。

## 发布到 GitHub Pages

1. 新建一个 GitHub 仓库。
2. 将本目录中的 `index.html`、`README.md` 和 `.nojekyll` 上传到仓库根目录。
3. 打开仓库的 `Settings` > `Pages`。
4. 在 `Build and deployment` 中选择 `Deploy from a branch`。
5. 选择 `main` 分支和 `/(root)` 目录，然后保存。

部署完成后，可通过以下形式访问：

```text
https://你的用户名.github.io/仓库名/
```

页面的问卷数据、样式和交互均包含在 `index.html` 中，不依赖外部资源。
