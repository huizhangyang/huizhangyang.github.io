# 按当前中文新版同步英文展示页

## 背景

用户指出英文版仍按旧版本翻译，需要按照当前中文 `index.html` 新版同步。当前任务只修改英文页可见文本，不处理图片，不重生成资源。

## 修改内容

- 将英文页顶部品牌和主标题从旧的 `Radar Imaging / Detection / Electronic Countermeasures` 改为 `Radar Imaging / Sensing / Countermeasures`。
- 同步关键词区，去掉旧版的 `Radar Electronic Countermeasures`、多余交付/复核类展示口径。
- 将第 7 项标题同步为主动干扰识别特征提取与自适应检测的新版译法。
- 将第 13 项标题同步为 SAR 图像域复合扫频干扰稀疏参数化估计的新版译法。
- 删除英文正文中的 `single-look complex`、`Electronic Countermeasure`、`electronic-countermeasure` 等旧口径。
- 保留 `Huizhang Yang's Research Page` 浏览器标题、favicon、主题切换、语言切换和 IP 自动切换脚本。

## 验证

- `index.html` 与 `index_en.html` 均为 16 项成果、31 张图片、31 个图注。
- 两个页面所有图片引用均存在。
- 英文页不包含 `Achievement(s)`、`Electronic Countermeasure`、`non-local`、`SLC`、`RFI`、`single-look complex`、`customer/client` 等禁用或旧版词。
