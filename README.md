# jubeat 歌曲背景资料

本仓库整理 jubeat 统一曲库的歌曲目录，以及按街机版本从旧到新编写的歌曲背景资料。每篇背景稿以曲目为单位，记录原作发行、创作者、游戏收录与解禁、版本位置和资料来源。

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

## 范围与口径

- 曲库清单来自本地统一曲库的 `song.json` 元数据，排除 `source.version == 自制谱` 的 13 条记录。
- 清单按统一曲库身份去重：同一首歌的“谱面变化”记录不另立一行，优先保留首次收录时的曲名、艺术家与版本。归并后为 2,438 首。
- `jubeat-china` 13 首和“音乐魔方”视频抄谱 16 首不属于自制谱，因此保留在清单中。
- 背景稿按版本的历史收录边界整理，部分文章会纳入后续移除或谱面变化记录，故每篇的曲目统计不必与曲库清单的当前去重数量相同。具体口径见各篇开头的“版本说明”。
- 曲名、艺术家、日期和游戏内状态均以对应资料页为准；不同来源发生冲突时，文章会注明差异，而不把推测写成确定结论。
- 资料主要来自 RemyWiki，并交叉查证 jubeat@Wiki、BEMANICN、ZIv / Zenius-I-vanisher、KONAMI 官方页面、音乐资料库与唱片商品页等公开来源。每个曲目条目均标注所用来源。

## 许可

本仓库原创的整理文字、表格编排和 README 采用 [MIT License](LICENSE)。

曲名、艺术家名、游戏名称、商标、封面与第三方网站内容仍归各自权利人所有，不在本仓库的 MIT 授权范围内。引用来源仅用于说明资料出处；若需再利用第三方内容，请遵循原网站及权利人的许可条款。

## 贡献

欢迎提交勘误和补充来源。修改背景资料时，请附上可访问的出处，并区分原始发行信息、游戏收录信息与推测。
