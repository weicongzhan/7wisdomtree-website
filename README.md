# 智慧树语言中心官网

智慧树语言中心（7WisdomTree）官方网站，纯静态 HTML/CSS/JS 项目。

## 项目结构

```
index.html      -- 首页
courses.html    -- 课程介绍
about.html      -- 关于我们
contact.html    -- 联系我们
css/style.css   -- 全局样式
js/main.js      -- 交互逻辑
images/         -- 图片资源
```

## 本地预览

直接用浏览器打开 `index.html` 即可预览，无需任何构建工具。

## 部署

项目设计为部署到 **Cloudflare Pages**：

1. 推送到 GitHub 仓库
2. 在 Cloudflare Pages 中关联仓库
3. 构建设置：无需构建命令，输出目录设为 `/`（根目录）
4. 绑定域名

## 关联平台

- 学习平台：https://www.7wisdomtree.com
- App 下载：https://www.7wisdomtree.com/download
