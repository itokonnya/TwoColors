# Color Scheme Generator

![demo](https://user-images.githubusercontent.com/124262891/218033714-78d532d8-80c4-4749-b91f-d7bec766f955.gif)

* __This suggests two contrasting colors.__
* __Those are ideal for presentation materials.__

## 配色の生成手順

[配色の生成プログラム](JavaScript/color-scheme-generation.js)

1. [PCCSの各色を並べた配列](JavaScript/color-code-store.js)[^1]からメインの色を無作為に選ぶ。
2. メインの色と対照性が保てない色を[PCCSの各色を並べた配列](JavaScript/color-code-store.js)[^1]から除いた配列を新たに作る。
3. 新たに作った配列からアクセントの色を無作為に選ぶ。

現状、私の独断で対照性が保てない色を選んでいる。合理的な基準を見つけ次第、改良に取り組む。

### PCCS (日本色研配色体系)

日本色研事業株式会社は、 __PCCSとは色をトーンと色相の二次元で表せる色空間である__ と説明している[^2]。

## Supported Browsers

* macOS
    * Google Chrome (latest version) - Recommended
    * Microsoft Edge (latest version)
    * Mozilla Firefox (latest version)
    * Apple Safari (latest version)
* Windows
    * Google Chrome (latest version) - Recommended
    * Microsoft Edge (latest version)
    * Mozilla Firefox (latest version)
* iPadOS
    * Google Chrome (latest version) - Recommended
    * Apple Safari (latest version)
* Android
    * Google Chrome (latest version) - Recommended

Any browser you use needs to have __JavaScript__ turned on.

### 参考文献

[^1]: 日本色彩研究所. デジタル色彩マニュアル. クレオ, 2004, p. 228-229.
[^2]: 日本色研事業株式会社. "PCCS". https://www.sikiken.co.jp/pccs/index.html, (参照2023-02-14).
