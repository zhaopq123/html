# static-html · 单文件 HTML 页面合集

零构建、零依赖的静态页面集合。每个 `.html` 都是**自足单文件**：样式、脚本、数据全在一个文件里，
双击就能打开，也能直接丢到任何静态托管（GitHub Pages / Nginx / 对象存储）上跑。

适合放「一页纸」类的东西：配置卡、检查清单、汇报页、演示原型 —— 改完就能发，不用打包。

## 页面清单

| 文件 | 是什么 | 用途 |
|---|---|---|
| [`励销云外呼配置卡_2026-09-21.html`](励销云外呼配置卡_2026-09-21.html) | 无人冰淇淋机器人 · 外呼配置卡 | 外呼前对齐口径的一页纸：产品参数、话术要点、常见异议；屏幕看、打印、投屏都行 |

## 怎么看

在线（GitHub Pages）：<https://zhaopq123.github.io/html/>

本地：

```bash
git clone https://github.com/zhaopq123/html.git
cd html
# 直接双击 .html，或起个静态服务
python -m http.server 8080
# 打开 http://localhost:8080
```

国内镜像（Gitee）：<https://gitee.com/zhaopq/static-html>

## 约定

- 一个页面一个文件，不引外部 CDN —— 断网也能打开
- 文件名带日期（`_YYYY-MM-DD`），同一份东西改版就新增一个，不覆盖历史
- 中文内容用 UTF-8 直写，不用 HTML 实体（Chrome 转 PDF 时不会拆字）

## 许可

MIT，见 [LICENSE](LICENSE)。
