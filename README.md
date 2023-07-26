# MSX Cartridge Inspector
---
## これは何ですか？
このツールはMSX用ROMカートリッジをMSX実機の環境でバイナリイメージとして保存するものです。

特徴としてはセーブデータ用のSRAMが存在する場合、そのイメージも保存されます。

## 使用環境
FDDとROMカートリッジを使用できるMSX実機

MSX-DOS

## 使用方法
Docフォルダーにあるmci-doc.txtを参考にしてください。

###　既知のバグ
・保存時に同名ファイルが存在する場合、ハングアップしてしまう場合がある

・一部のROMカートリッジで、実際の容量よりサイズを大きく判定してしまうことがある。
（ページ2、8000H～BFFFHに8KBのROMがある場合に起きる？）

### ライセンス
これらのコード類はYoshimasa Kusakaにより作成されたソフトウェアであり、使用等に関しては記載されたライセンスに同意したものとします。

ライセンスは三条項BSDライセンスとします。詳細は[LICENSE](https://bitbucket.org/gamepres/msx-cartridge-inspector/src/main/LICENSE)を参考ください。

### 改版履歴
2023/1/26

初版

---
(C) 2022, Yoshimasa Kusaka

[ゲーム保存協会](https://www.gamepres.org/)
