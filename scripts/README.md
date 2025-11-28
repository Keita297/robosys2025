# moodcalc
![test](https://github.com/Keita297/robosys2025/actions/workflows/test.yml/badge.svg)
`moodcalc` は、入力された日本語文章から簡易的に感情スコアを計算し、文章の傾向を判定する Bash スクリプトです。

---

## 使い方
# ./moodcalc "今日はとても楽しくて嬉しい！"
# echo "全然うまくいかなくて悲しい" | ./moodcalc

### 1. 実行権限を付与
```bash
chmod +x moodcalc

