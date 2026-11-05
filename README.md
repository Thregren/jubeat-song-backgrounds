# jubeat 歌曲背景资料

本仓库整理 jubeat 统一曲库的歌曲目录，以及按版本从旧到新编写的歌曲背景资料。每篇背景稿以曲目为单位，记录原作发行、创作者、游戏收录与解禁、版本位置和资料来源。

当前内容对应 **2026-11-05 更新版**，覆盖 15 个版本文件、2,438 个统一曲库身份，其中音乐魔方 29 项。资料仍在继续补查，本仓库不把现有覆盖度表述为研究已经完成。

音乐魔方另有 [71 首独立资料](music-cube-71/README_阅读说明.md)：其中 29 项已有正式曲库身份，42 项为临时资料，不与 2,438 项直接相加。

## 目录

### 曲库清单

- [统一曲库歌曲总表](index/unified-song-catalog.md)：按版本、曲名、艺术家和统一曲库 ID 排列，共 2,438 首。

### 分版本背景

| 顺序 | 版本 | 资料 |
|---:|---|---|
| 1 | jubeat | [初代歌曲背景](background/01-jubeat.md) |
| 2 | jubeat ripples | [ripples 歌曲背景](background/02-ripples.md) |
| 3 | jubeat knit | [knit 歌曲背景](background/03-knit.md) |
| 4 | jubeat copious | [copious 歌曲背景](background/04-copious.md) |
| 5 | jubeat saucer | [saucer 歌曲背景](background/05-saucer.md) |
| 6 | jubeat saucer fulfill | [saucer fulfill 歌曲背景](background/06-saucer-fulfill.md) |
| 7 | jubeat prop | [prop 歌曲背景](background/07-prop.md) |
| 8 | jubeat Qubell | [Qubell 歌曲背景](background/08-qubell.md) |
| 9 | jubeat clan | [clan 歌曲背景](background/09-clan.md) |
| 10 | jubeat festo | [festo 歌曲背景](background/10-festo.md) |
| 11 | jubeat Ave. | [Ave. 歌曲背景](background/11-ave.md) |
| 12 | jubeat beyond the Ave. | [beyond the Ave. 歌曲背景](background/12-beyond-the-ave.md) |
| 13 | beyond the Ave. 2026-07-22 更新 | [2026-07-22 更新歌曲背景](background/13-beyond-the-ave-2026-07-22.md) |
| 14 | jubeat plus | [plus 歌曲背景](background/14-jubeat-plus.md) |
| 15 | 音乐魔方 | [音乐魔方歌曲背景](background/15-music-cube.md) |

### 核查与说明

- [阅读说明](metadata/reading-guide.md)：当前统计、证据口径与阅读方法。
- [版本变更说明](metadata/version-changes.md)：本次新增范围、继承成果与未变指标。
- [格式与覆盖检查](metadata/format-and-coverage.json)：身份数、版本文件数、锚点与结构检查。
- [重点缺口清单](metadata/key-gaps.md)：三源不足、待复现来源及具体曲目。
- [音乐魔方身份映射](metadata/music-cube-identity-map.json)：29 项身份及 `jubeat-china` 合并关系。
- [音乐魔方合并说明](metadata/music-cube-merge-notes.md)：历史别名、分组和重名处理。
- [逐曲创作证据分类](metadata/evidence-classification.json)：原作证词、二手证词及证据边界。
- [逐曲核查状态与缺口](metadata/verification-status-and-gaps.json)：每项身份的来源与待核状态。
- [文件校验](metadata/file-checksums.json)：交付文件 SHA-256 清单。

## 范围与口径

- 曲库清单来自本地统一曲库的 `song.json` 元数据，排除 `source.version == 自制谱` 的 13 条记录。
- 清单按统一曲库身份去重：同一首歌的“谱面变化”记录不另立一行，优先保留首次收录时的曲名、艺术家与版本。归并后为 2,438 首。
- 依 2026-11-03 的更新口径，`jubeat-china` 与音乐魔方统一归属 **音乐魔方**；china 是历史别名，不另立版本。原 china 13 首和视频抄谱 16 首合计 29 个曲库身份，全部保留。
- 背景稿按统一曲库的本地分组整理，并新增 2026-07-22 更新线、`jubeat plus` 与音乐魔方三篇。本地分组不必然等于真实历史首发；跨版本差异、总表外历史附录和未核事项在各篇开头的说明或对应条目中列明。
- 曲名、艺术家、日期和游戏内状态均以对应资料页为准；不同来源发生冲突时，文章会注明差异，而不把推测写成确定结论。
- 资料来源不只依赖 RemyWiki：逐曲交叉查证 jubeat@Wiki、BEMANICN、ZIv / Zenius-I-vanisher、KONAMI 官方页面、作者或艺人资料、访谈、音乐资料库、歌词数据库与唱片商品页等公开页面。每个曲目条目均标注来源编号；重复转载、搜索摘要和未具体涉及本曲的页面不计作新的独立来源。
- 当前 2,416 项达到至少三个有效独立来源，仍有 22 项不足；已完成第二次独立复核 2,435 项，另有 3 项的部分来源待复现；全部字段均已证实为 0 项。来源数量与文字润色不等于创作过程已经完整核实，未核实的录音、母带、剪辑、日期异文和作者分工继续逐条标明。

## 许可

本仓库原创的整理文字、表格编排和 README 采用 [MIT License](LICENSE)。

曲名、艺术家名、游戏名称、商标、封面与第三方网站内容仍归各自权利人所有，不在本仓库的 MIT 授权范围内。引用来源仅用于说明资料出处；若需再利用第三方内容，请遵循原网站及权利人的许可条款。

## 贡献

欢迎提交勘误和补充来源。修改背景资料时，请附上可访问的出处，并区分原始发行信息、游戏收录信息与推测。
