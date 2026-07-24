# 🖼️ Images

个人图床，通过 GitHub + jsDelivr CDN 提供静态图片外链。

## 目录

```
images/
└── console/
    └── login/
        ├── bg-sea.jpg
        └── bg-starry.jpg
```

## 图片列表

| 路径 | 预览 |
|------|------|
| `console/login/bg-sea.jpg` | ![bg-sea](https://cdn.jsdelivr.net/gh/gvray/images@main/console/login/bg-sea.jpg) |
| `console/login/bg-starry.jpg` | ![bg-starry](https://cdn.jsdelivr.net/gh/gvray/images@main/console/login/bg-starry.jpg) |

## 使用方式

推荐使用 **jsDelivr CDN** 地址，国内访问更快：

```
https://cdn.jsdelivr.net/gh/gvray/images@main/{path}
```

例如：
- 大海背景：`https://cdn.jsdelivr.net/gh/gvray/images@main/console/login/bg-sea.jpg`
- 星空背景：`https://cdn.jsdelivr.net/gh/gvray/images@main/console/login/bg-starry.jpg`

## 新增图片

```bash
# 放入对应目录，命名语义化
git add .
git commit -m "Add xxx images"
git push origin main
```

> 推送后 jsDelivr 会缓存文件，如需立即刷新可改用 commit hash 作为版本号。
