# MixedRealityToolkit-Unity-Ja (MRTK-UNity-Ja)
MRTK-Unity の UI コンポーネントの日本語対応バージョンです。

フリーの日本語フォント M+ Fonts を利用しています。

![image](https://user-images.githubusercontent.com/4415085/93562458-0bc9cb80-f9c1-11ea-9669-bd316d8cb2ab.png)

## プロジェクトへのインポート
事前に Unity プロジェクトに MRTK をインポートしてください。


### Unity Package Manager (UPM) でのインポート
`Packages\manifest.json` の `"dependencies"` 内に以下の行を追加してください。

```
"jp.co.hololab.mrtk.ja": "https://github.com/HoloLabInc/MixedRealityToolkit-Unity-Ja.git?path=Assets/MRTK.ja",
```

### Unity Package でのインポート
リリースページから Unity Package をダウンロードしてインポートしてください。

https://github.com/HoloLabInc/MixedRealityToolkit-Unity-Ja/releases

<br>
<br>

---

<br>
<br>

## 本リポジトリの Unity プロジェクトセットアップ
本リポジトリに含まれる Unity プロジェクトを開くには、以下のセットアップを行ってください。

### Git Submodule のクローン
#### コマンドから実行する場合
```bash
git clone --recursive git@github.com:HoloLabInc/MixedRealityToolkit-Unity-Ja.git
```
または

```bash
git clone git@github.com:HoloLabInc/MixedRealityToolkit-Unity-Ja.git
cd MixedRealityToolkit-Unity-Ja
git submodule init
git submodule update
```

### シンボリックリンクの作成
`_tools\createSymlink.bat` を実行してください。

## Author
Furuta, Yusuke ([@tarukosu](https://twitter.com/tarukosu))

## License
MIT
