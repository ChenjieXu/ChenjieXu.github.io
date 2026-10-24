# 个人网站维护

网站由 GitHub Pages 从 `master` 分支的仓库根目录构建。

| 内容 | 修改文件 |
| --- | --- |
| 中文首页、工作经历、开源项目 | `index.md` |
| 中文教育经历、新闻、发表刊物 | `pages/education.md`、`pages/news.md`、`pages/publications.md` |
| 对应英文正文 | `en/` 下的同名文件 |
| 两种语言共用的荣誉事实与翻译 | `_data/honors.yml` |
| 两种语言的界面文字 | `_data/locales.yml` |
| 导航、站点信息 | `_config.yml` |

中文地址保持不变，英文页面位于 `/en/`。导航中的 `EN` / `中文` 切换到同一栏目的另一语言版本。更新正文时维护对应翻译；荣誉的日期、奖项和角色只在共享数据中维护一次，不再创建 `docs/` 等内容副本。

更新后提交并推送，等待 GitHub Pages 部署成功，再检查对应线上页面及语言切换。

旧 Markdown 副本及未上线的项目简记保存在 Git 历史中，可在提交 `91dca7b` 查看。
