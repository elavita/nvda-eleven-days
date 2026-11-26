# N-V-D-A — 《Y.M.C.A.》改词版

**在线播放（带同步歌词）→ https://elavita.github.io/nvda-eleven-days/**

2026 年 11 月 12 日，黄仁勋辞去英伟达总裁、CEO 及董事职务。11 天后的 11 月 23 日，董事会全票通过，把他请了回来。中间隔着一条白宫的电话线、一次六天的立场反转，和三十一个点的股价。

这首歌就是那十一天。

---

## 这是什么

一首戏仿《Y.M.C.A.》的英文歌，配中文字幕。

- **51 行，与原曲逐句等音节**，一句不差。`[Verse 1] 8 + [Chorus] 8 + [Verse 2] 8 + [Chorus] 8 + [Verse 3] 8 + [Chorus] 8 + [Outro] 3`
- **笑点全部在英文行里**，中文字幕只翻不解释，不靠注释
- **数字都可查**：跌三成、涨三十一个点、调查未结、六天反转

## 三段副歌，三个台阶

前两段副歌只差一个开关，第三段把条件露出来：

| | 末句 | 含义 |
|---|---|---|
| 副歌 1 | You **can't** do whatever you feel | 不能 |
| 副歌 2 | You **can** do whatever you feel | 能 |
| 副歌 3 | **As long as** the ticker goes up | 只要 |

## 五段结构

| 段落 | 视角 | 内容 |
|---|---|---|
| 主歌 1 | 董事会 | 宣读《行为准则》，剥皮衣，末句预告千夫所指 |
| 副歌 1 | 全体 | 股价跌三成，"请慢用" |
| 主歌 2 | 特朗普 | 一个电话归队，威逼董事，利诱本人 |
| 副歌 2 | 全体 | 股价涨三十一个点，"你洗清了罪责" |
| 主歌 3 | 黄仁勋 | "他们都说自己也曾坐在你位置上""他们从来没有" |
| 副歌 3 | 全体 | 醉生梦死 |
| 尾声 | 全体 | 把皮衣从地上捡起来 |

## 文件

```
index.html              单文件播放器，无依赖，双击即用（需同目录 audio.mp3）
audio.mp3               AI 翻唱音频，3:30
lyrics/*.lrc            中文字幕 / 中英双语字幕，时间轴已对齐
lyrics/for-ai*.txt      喂给 AI 翻唱工具的纯歌词文本（三种拼写方案）
docs/script-cn.md       完整可唱本：逐句字幕、音节表、双关说明、剪辑提示
docs/script-en.md       纯英文演出本
assets/preview.png      播放器截图
```

## 直接用

开 `index.html`：

- **空格** 播放 / 暂停
- **点任意一行** 跳到那一句
- **← / →** 快退 / 快进 3 秒
- 底部 **字幕偏移** 滑块整体前后挪，用来判断是整体偏差还是单行错

页面会自动把"与上一行间隔小于 2.2 秒"的行标成琥珀色——那是时间轴出错的典型痕迹。

## 事实来源

| 歌词 | 事实 | 来源 |
|---|---|---|
| down thirty percent | 六周连跌期间市值蒸发约 30%（约 1.7 万亿美元） | CNBC, 2026-11-13 |
| up thirty-one percent | 复职当日收盘 +31.5% | Reuters, 2026-11-23 |
| eleven days | 11.12 辞职 → 11.23 复职 | 新华社 / AP |
| the probe is still open | 董事会明示独立委员会调查"将继续进行到底" | NVIDIA 公告, 2026-11-23 |
| they'll do just what I say | 公告原文："听取了美国政府高层的意见" | NVIDIA 公告, 2026-11-23 |
| 六天反转 | 11.17 "不打算恢复其职务" → 11.23 全票复职 | Reuters / BBC |

## 声明

- 曲：Village People《Y.M.C.A.》，本仓库歌词为戏仿作品，仅作评论与讽刺用途。
- 人声由 AI 翻唱工具生成，非真人演唱。
- 歌词中"黄 man"是双关（黄 / Young man），字幕统一作"黄老板"。

---

**English**: A parody of "Y.M.C.A." about the eleven days Jensen Huang spent out of NVIDIA (Nov 12 → Nov 23, 2026). 51 lines, line-for-line metrically identical to the original. English vocal with Chinese subtitles; every joke lives in the English line, nothing depends on a footnote.
