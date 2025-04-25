# lilToonBiColorOutline

## これは何？

- [lilToon](https://lilxyzw.github.io/lilToon/ja_JP/) のカスタムシェーダーです。
  - cf. [lilToon カスタムシェーダーの作り方](https://lilxyzw.github.io/lilToon/ja_JP/dev/custom_shader.html)
- ワールド法線の向きに応じて、輪郭線の色(青 or 赤)を決めます。
  - より具体的には、ワールド法線の x 成分の値が 0 未満かどうかで輪郭線の色を決めています。
 
## どんな風に見えるの？

- 使用例 ([バウワウナード ちびとら](https://booth.pm/ja/items/4595348))

<image src="https://github.com/user-attachments/assets/29371231-fc37-40db-955e-41f609b51345" width="50%" />

## 導入方法

- [lilToon 導入手順と簡易的な使い方](https://lilxyzw.github.io/lilToon/ja_JP/first.html#%E5%B0%8E%E5%85%A5%E6%89%8B%E9%A0%86%E3%81%A8%E7%B0%A1%E6%98%93%E7%9A%84%E3%81%AA%E4%BD%BF%E3%81%84%E6%96%B9) にしたがって、lilToon をインストールしてください。
- [lilToonBiColorOutline/releases](https://github.com/siiru3/lilToonBiColorOutline/releases) から最新版の unitypackage (e.g. `lilToonBiColorOutline_vX.Y.Z.unitypackage`) をダウンロードし、Unity の Project ウィンドウ内にドラッグ&ドロップしてください。
- マテリアルを選択し、Inspector上部の "Shader" を "lilToonBiColorOL/lilToon" に変更してください。

<image src="https://github.com/user-attachments/assets/30df15ad-1df0-4b87-967f-f045d06a2070" width="50%" />

- "輪郭線設定" から "輪郭線" のチェックボックスにチェックを入れてください。（輪郭線の太さも変更可能です。）

## 注意点

- "輪郭線設定"の"色"の項目で指定した色は反映されません。

## ライセンス

- MIT License
  - 詳細は[こちら](https://github.com/siiru3/lilToonBiColorOutline/blob/main/LICENSE)をご確認ください。
