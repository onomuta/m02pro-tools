# M02 Pro ツール

感熱プリンター Phomemo M02 Pro に、ブラウザから Web Bluetooth で直接印刷するツール集です。

- `kuku/` … くくプリント：選んだ段の九九一覧と、今日の運勢を印刷
- `studio/` … プリントスタジオ：テキスト・画像・パターンをディザ処理して印刷

## 使い方

GitHub Pages で公開した URL を、Mac・PC・Android の Chrome か Edge で開き、「接続」からプリンターを選びます。
iPhone は Safari・Chrome とも Web Bluetooth に対応していないため、Bluefy などの対応ブラウザが必要です。

## プリンター設定（M02 Pro 実機に合わせた値）

- 送信幅：1行 78 バイト（624 ドット）
- 印字幅：576 ドット（約 48.8 mm、300 dpi）
- 最後の余白：18 mm（紙送り命令ではなく白い行として送信）
