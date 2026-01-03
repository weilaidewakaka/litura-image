# Litura Image Hosting

> Litura 网站和博客的图片存储仓库

此仓库用于存储 [Litura 网站](https://www.liturangler.com) 的所有图片资源，通过 jsDelivr CDN 提供全球加速访问。

## 📁 目录结构

```
.
├── blog/              # 博客文章封面和配图
│   ├── 2024/         # 2024年博客图片
│   └── 2025/         # 2025年博客图片
├── assets/           # 网站静态资源图片
│   ├── logo.png      # 品牌Logo
│   └── banners/      # 宣传横幅
└── README.md         # 本文件
```

## 🔗 CDN 链接格式

```
https://cdn.jsdelivr.net/gh/weilaidewakaka/litura-image@main/图片路径
```

### 使用示例

```markdown
<!-- 博客封面 -->
![冬季钓鱼](https://cdn.jsdelivr.net/gh/weilaidewakaka/litura-image@main/blog/2025/winter-fishing.jpg)

<!-- Logo -->
![Logo](https://cdn.jsdelivr.net/gh/weilaidewakaka/litura-image@main/assets/logo.png)
```

## 🚀 上传新图片

### 自动上传脚本
```bash
cd ~/project/Litura-web
./scripts/upload-image.sh 图片路径 blog/2025
```

### GitHub 网页上传
1. 进入相应目录
2. 点击 "Add file" → "Upload files"
3. 拖拽上传

## 📊 仓库信息

- **CDN**: jsDelivr
- **仓库类型**: Public
- **相关项目**: [Litura Web](https://github.com/weilaidewakaka/Litura-web)
- **创建时间**: 2025-01-03

---

**注意**: 请保持文件名简洁（小写字母+连字符），避免使用空格和特殊字符。
