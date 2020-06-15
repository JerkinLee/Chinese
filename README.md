# Chinese

中文拼音及数字读法转换。（引用库：Microsoft Visual Studio International Pack 1.0 Service）

```c#
// "qu4 ba1，pi2 ka3 qiu1！"
Pinyin.Get("去吧，皮卡丘！", PinyinFormat.Default);
// "qu ba，pi ka qiu！"
Pinyin.Get("去吧，皮卡丘！", PinyinFormat.WithoutTone);
// "qù bā，pí kǎ qiū！"
Pinyin.Get("去吧，皮卡丘！", PinyinFormat.PhoneticSymbol);
```

