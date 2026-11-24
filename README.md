# NekoGo audio

MP3 pronunciation files for the NekoGo JLPT vocabulary (8,344 files, N5–N1).

Layout: `n5/<vocab-id>.mp3` … `n1/<vocab-id>.mp3`. The `audio` field in the app data
(`audio/n5/<id>.mp3`) maps to `<base>/n5/<id>.mp3` in this repo (drop the `audio/` prefix).

Raw base URL: `https://raw.githubusercontent.com/cuongdq88/nekogo/main/`

## Generated audio (VOICEVOX)

Made with VOICEVOX CORE by `tools/tts_voicevox.py` in the main NekoGo repo.

- `examples/n<L>/<vocab-id>.mp3`: vocabulary example sentences
- `grammar/<grammar-id>/<idx>.mp3`: grammar example sentences
- `exam/n<L>/listening/<id>.mp3` and `<id>.slow.mp3`: mock-exam listening (N5 scripts from
  [JLPTSuccess](https://github.com/gauravhq/JLPTSuccess), MIT; N4–N1 scripts written by NekoGo)

Voices (credit required): VOICEVOX:雨晴はう, VOICEVOX:四国めたん, VOICEVOX:東北ずん子,
VOICEVOX:玄野武宏(CV:ガロ), VOICEVOX:白上虎太郎.
