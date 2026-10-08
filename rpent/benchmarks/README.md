# RPent leaderboard

The current leaderboard is maintained in RPent:

- [English results](https://rpent.readthedocs.io/en/latest/rst_source/leaderboard/index.html)
- [中文成绩](https://rpent.readthedocs.io/zh-cn/latest/rst_source/leaderboard/index.html)
- [Dataset and renderer](https://github.com/RLinf/RPent/tree/main/docs/_static/leaderboard)
- [Contribution instructions](https://github.com/RLinf/RPent/blob/main/docs/README.md#update-the-leaderboard)

`index.html` forwards readers to Read the Docs, preserving the language query,
selected view, page section and fragment. It also provides ordinary links for
readers without JavaScript. Forwarding requires serving the file as HTML;
GitHub blob views and raw file responses are not HTTP redirects.

Other files in this directory are frozen compatibility assets. Update scores
and charts in RPent only. Keep these files until consumers of branch-based
script, JSON and PNG URLs have migrated; replacing an HTML entry point does
not redirect embedded images or scripts. Preserve the icon license notices
while distributing the corresponding icons.

排行榜数据和渲染器已迁入 RPent。请在 RPent 中维护成绩和图表。本目录其余文件
暂时作为旧链接的兼容资源保留，不再同步成绩；确认旧页面和图片引用完成迁移后，
再清理重复文件。旧 HTML 入口的跳转不适用于图片、JSON 或脚本 URL。
