# 博杉 · 技能成果看板

> 纪念我们的同事张博3 — Bó Shān

## 这是什么

这是 Codex 技能产出的成果展示页，托管在 **GitHub Pages**，完全免费、永久在线。每次运行技能后只需推送更新，链接不变，所有人看到的都是最新版。

## 如何使用

1. 运行你的技能，产出数据
2. 更新 `index.html` 中的数据部分
3. 执行以下命令推送：

```bash
git add index.html
git commit -m "更新博杉看板数据 $(date '+%Y-%m-%d')"
git push origin main
```

4. 领导刷新 `https://你的用户名.github.io/bo-shan` 即可看到最新结果

## 文件结构

```
dashboard/
├── index.html    # 看板页面（唯一需要经常更新的文件）
└── README.md     # 本文件
```

## 部署

1. 把这个文件夹推送到 GitHub 仓库
2. 仓库 Settings → Pages → Source 选 `main` 分支 → 保存
3. 等待 30 秒，页面自动上线
