# Jinfu Zhang 的个人主页

基于 [Jon Barron 的模板](https://github.com/jonbarron/jonbarron.github.io) 精简，保留白底、蓝色链接与论文列表的学术主页风格。无需安装依赖或构建。

## 文件

- `index.html`：个人简介与论文信息。
- `stylesheet.css`：桌面和手机排版。
- `images/jinfu-zhang.png`：用户提供的个人照片，页面以圆形头像显示，点击可查看原图。
- `images/cpps-model.png`：用户提供的论文配图，点击可查看原图。
- `data/zhang2025cpps.pdf`：用户提供的论文。
- `data/zhang2025cpps.bib`：论文引用。
- `.nojekyll`：直接发布静态文件。

## 简介草稿（英文已写入页面）

我是浙江大学控制科学与工程学院2026级工科博士生，研究方向为面向工业的人工智能（AI4Industry），重点关注风电领域的应用。博士期间，我计划依托课题组与风电及其他能源企业的合作，开展工业多模态数据分析与故障检测研究，同时积极探索 AI4Industry 中新的研究方向。

本科期间，我在杭州电子科技大学开展了一年半的科研工作，主要研究复杂网络及其在信息物理电力系统中的应用。

姓名采用论文中的 Jinfu Zhang；学校、入学年份、博士身份、科研经历和未来方向根据用户提供的信息撰写。未添加未经确认的导师、具体企业、邮箱或简历。照片原文件保持不变，通过 CSS 以圆形取景显示；电脑端直径 190px，手机端直径 140px。

## 本地查看

可以直接用浏览器打开 `index.html`。也可以在本目录执行 `python3 -m http.server 8000`，然后打开 http://localhost:8000。

## 发布到 GitHub Pages

1. 将此目录内的更改提交并推送至 `iamzjf/iamzjf.github.io` 的 `main` 分支。上传时让 `index.html` 位于仓库根目录，不要多包一层文件夹。
2. 仓库 Settings → Pages → Source 选择 Deploy from a branch。
3. Branch 选择 `main`，目录选择 `/(root)`，点击 Save。
4. Custom domain 留空。原作者的 CNAME 已移除。
5. 等待 Actions 中 Pages 部署成功，访问 https://iamzjf.github.io/。

本次仅修改本地文件，未提交、推送或更改 GitHub Pages 设置。

## 清理说明

已移除原作者的论文、简历、头像、图片、视频，以及 mipnerf、mipnerf360、zipnerf 项目页面。原始内容仍保留在本地 Git 历史中。保留模板来源链接。
