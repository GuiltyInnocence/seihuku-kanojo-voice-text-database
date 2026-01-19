# seihuku-kanojo-voice-text-database
Voice-text database for game Seihuku Kanojo. Make use of this if your favorite seiyuu voiced here.  
SQLite database, `voice_id` field corresponds to ogg filenames in `Voice.pac`. 

- 0908xxxx = Yui Konomi (Kaori Maeda)
- 0911xxxx = Mio Yahiro (Yurie Kozakai)
- 0915xxxx = Himari Tamayori (Azusa Tachibana)

- 0901xxxx = 桃尻芹香 (陽高真白)
- 0902xxxx = 伊規須真守 (河西健吾)
- 0905xxxx = 仁田原夢羽 (山田麻莉奈)
- 0919xxxx = 古賀希望 (月城日花)

- 0903xxxx = 舞鶴よかと
- 0904xxxx = 羽形モモ
- 0906xxxx = 葛城七瀬
- 0907xxxx = 莉子
- 0909xxxx = 花梨
- 0910xxxx = ローラ
- 0912xxxx = 実桜マネージャー
- 0913xxxx = 秋月花音 (ゆい挂件)
- 0914xxxx = 黒田葵 (ゆい挂件)
- 0916xxxx = 鐘江芽郁 (ひまり挂件)
- 0917xxxx = 砥綿結愛 (ひまり挂件)
- 0918xxxx = CGEプロダクション社長藤倉

### Thanks to 
- [akiWagashi/GIGA_NeXAS](https://github.com/akiWagashi/GIGA_NeXAS)
- [morkt/GARbro](https://github.com/morkt/GARbro)

---

> The `Voice.pac` seems to be imcomplete for Hikari Field Simplified-Chinese release. Use original version when unpacking `Voice.pac`. `size: 788402286, sha256: 34a50c3a605fd24f042e33aa35e2c67be6b64c027468991d42ea982a7e451ba2`

有个问题，处理的时候把`\x00`全替换成CRLF了，可能有一堆莫名其妙的换行
