# moodcalc
![test](https://github.com/Keita297/robosys2025/actions/workflows/test.yml/badge.svg)
- このソフトウェアパッケージは，3 条項 BSD ライセンスの下で，再頒布および使用が許可されます。

- このパッケージには，他者の著作物に依存しない，独自に作成したコードのみが含まれています。

- このパッケージで利用している内容は，下記のスライド資料（CC-BY-SA 4.0 by Ryuichi Ueda）を参考にして作成しました。
    - [ryuichiueda/my_slides robosys_2025](https://github.com/ryuichiueda/my_slides/tree/master/robosys_2025)

- © 2025 Keita Arakawa

`moodcalc` は、入力された日本語文章から簡易的に感情スコアを計算し、文章の傾向を判定する Bash スクリプトです。

---

## 使い方
# ./moodcalc "今日はとても楽しくて嬉しい！"
# echo "全然うまくいかなくて悲しい" | ./moodcalc

### 1. 実行権限を付与
```bash
chmod +x moodcalc

