# 故宫博物院 x LEGO | 筑梦紫禁 戏出东方

Harvard BPC Case Competition Proposal | Team 3035 x 2045

## 项目结构

```
tpm/
├── index.html          # 主页面
├── images/             # 图片资源
│   ├── logo_gugong.png
│   ├── logo_lego.png
│   ├── hero_bg.jpg     # 首屏背景图（需自行添加）
│   ├── card_theatre.jpg
│   ├── card_dougong.jpg
│   ├── card_relic.jpg
│   └── ar_preview.jpg
├── .nojekyll           # 禁用 Jekyll 处理
└── README.md
```

## GitHub Pages 部署步骤

1. **创建 GitHub 仓库**
   - 登录 [GitHub](https://github.com)
   - 点击 New repository，创建新仓库（如 `tpm`）

2. **上传代码**
   ```bash
   cd c:\Users\Administrator\Desktop\tpm
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/你的用户名/tpm.git
   git push -u origin main
   ```

3. **启用 GitHub Pages**
   - 进入仓库 → **Settings** → **Pages**
   - **Source** 选择 `Deploy from a branch`
   - **Branch** 选择 `main`，文件夹选择 `/ (root)`
   - 点击 **Save**

4. **访问站点**
   - 部署完成后约 1–2 分钟生效
   - 访问：`https://你的用户名.github.io/tpm/`

## 图片资源说明

请将以下图片放入 `images/` 目录：

| 文件名 | 用途 |
|--------|------|
| hero_bg.jpg | 首屏背景 |
| card_theatre.jpg | 戏台卡片图 |
| card_dougong.jpg | 斗拱卡片图 |
| card_relic.jpg | 文物卡片图 |
| ar_preview.jpg | AR 演示图 |
