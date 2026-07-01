# 调整页面底栏署名居中显示

- 时间：2026-07-01
- 目标：将页面底部“雷达成像/探测/对抗 技术成果展板，南京理工大学，电子工程与光电技术学院”等署名信息水平居中。
- 修改范围：`index.html` 与 `index_en.html` 的 `footer .content-frame` 样式。
- 实现方式：保留原有最大宽度约束，增加 `text-align: center;`，不影响正文区其它 `content-frame`。
- 资源约束：未修改 `SAR技术成果展示版_assets`，未更改成果图文件。
