# Toy Chest Lab

玩具箱三消关卡配置与试玩编辑器。

## 本地运行

```bash
python3 -m http.server 8128
```

打开 <http://127.0.0.1:8128/index.html>。

## GitHub Pages

仓库推送到 `main` 后，`.github/workflows/pages.yml` 会通过 GitHub Actions 发布根目录静态站点。

预期地址：<https://gaogaolo.github.io/toychest/>。

详细配置与生成规则见 [`MEMORY.md`](MEMORY.md)。
