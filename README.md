# japan_prefectures

日本の都道府県名と地方名の英語と日本語のデータです。

本体は[japan_prefectures.csv](https://github.com/hamukazu/japan_prefectures/blob/main/japan_prefectures.csv)です。

注意点：

* `prefecture_jp`（例えば「長野」）と`suffix_jp`（例えば「県」）を繋げると住所等で使われる都道府県名になりますが、北海道だけは例外で、`prefecture_jp`は「北海道」、`prefix_jp`は「道」になっています。これは呼称の慣習に従っています。
* 日本語地方名（`region_jp`）は、国土地理院の[「日本の典型地形について」](https://www.gsi.go.jp/kikaku/tenkei_top.html)に習いました。
* 英語地方名（`region_en`）は日本語地方名をそのまま表記したものではなく、例えば「関東地方」は「Kanto」になっています。
