![](https://raw.githubusercontent.com/JJYing/compressed-punctuation-sans/main/preview.png)

# 基础特性
- 用 kerning 实现了部分标点之间的空间调整，纯属 hack，不喜勿入
- 包含两个字重：Regular 和 Bold
- 粗细基于 PingFang SC，可基本匹配
- 标点符号外形是完全重绘的，应该没有版权问题
- 和微软雅黑也勉强兼容
- 没有 hint
- 纯自用，所以标点符号非常有限，仅包含 `、` `。` `…` `：` `！` `？` `；` `—` `〈` `〉` `「` `」` `《` `》` `『` `』` `（` `）` `~` `“` `”` `‘` `’`
- 夹带了一点连字私货，比如「~~~」和「！！！」


# FAQ
- **什么是标点符号挤压？** 请看[这个视频](http://r.anw.red/nEaKzC)
- **如何使用这个字体？** 定义一个 web font，然后在 `font-family` 里放到正文字体前即可，因为他没有中西文字符，所以标点以外的字符会 fallback 到你原来的字体设置。什么？你问其他平台怎么用？我也不知道
- **采用什么授权，可以自己改或者商用吗？** 采用 [OFL 授权](https://scripts.sil.org/cms/scripts/page.php?site_id=nrsi&id=OFL)，可自行修改 Glyphs 源文件或者商用
- **你这个做得不够好，有没有其他版本？** 在[这里](https://github.com/houkanshan/mojikumi)，做得比我完善、字符设计上更有风格一些，但没有粗体，以及[这个](https://github.com/Buernia/Zhudou-Sans)，基于 Noto Sans，可变字体格式
