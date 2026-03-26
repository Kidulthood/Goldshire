# 图床部署
## 实现方案
Github+Cloudflare+PicGo
## 目录结构
/goldshire/ (仓库根目录)
├── README.md           # 记录图床的使用方法和加速域名
├── .gitignore          # 忽略临时文件
├── joplin/             # 专门存放 Joplin 同步过来的笔记图片
│   └── 2026/           # 按年份切分，防止单文件夹文件过多
├── marp/               # 专门存放 Marp 演示文稿的素材
│   ├── assets/         # 通用 Logo、背景图
│   └── 2026-Q1-Report/ # 特定项目的配图
└── temp/               # 临时分享、随手截图（定期清理）
