# 朋导工作（freshmen_guide）

新生校园网站导航页项目。单文件 HTML 应用，纯原生 JS，无依赖。

## 项目信息

- 本地目录：`C:/Users/Lenovo/Desktop/朋导工作`（本目录就是 git 仓库根目录）
- 远程仓库：`https://github.com/ljxYYDS369/freshmen_guide.git`（分支 `main`）
- 部署地址：https://ljxyyds369.github.io/freshmen_guide/
- 数据来源：`index.html` 内嵌 `const data = [...]` 数组

## 开发流程

修改完 `index.html` 后：

```bash
git add index.html
git commit -m "feat: 添加新站点"
git push origin main
```

推送后 GitHub Pages 部署约需 1-2 分钟生效。修改的是网页内容时，记得提醒用户硬刷新或加防缓存 meta（页面已带 `no-cache, no-store`）。

## 注意

- `.gitignore` 排除了本地的「各种链接」文件，不要提交它。
- 本仓库只跟踪 `index.html` 和 `.gitignore`，其他文件（PDF、文档、快捷方式等）不要误提交。
- 提交信息用中文写主体，遵循 Conventional Commits（feat/fix/chore 等）。
