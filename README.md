# MVT Test Repository

バイナリベクトルタイルの配信実験のページです。

バイナリベクトルタイルを使った[日本鉄道時系列地図][https://cieloazul310.github.io/railroad-timeline-map/]
[Leafletでの表示サンプル][デモ]

## 配信実験中のデータ

### [国土数値情報] 学校データ
- URL: https://cieloazul310.github.io/mvt-tiles/tile/schools/{z}/{x}/{y}.mvt
- ズームレベル8〜15
- レイヤ名: `"schools"`

[デモ]: http://cieloazul310.github.io/mvt-tiles/
[国土数値情報]: http://nlftp.mlit.go.jp/ksj/


### [国土数値情報] 鉄道時系列データ
- URL: https://cieloazul310.github.io/mvt-tiles/tile/rails/{z}/{x}/{y}.mvt
- ズームレベル4〜15
- レイヤ名: `"section"`:路線, `"station"`:駅

[国土数値情報]: http://nlftp.mlit.go.jp/ksj/

### [地域メッシュ統計] 250mメッシュ人口データ
- URL: https://cieloazul310.github.io/mvt-tiles/tile/population_250m/{z}/{x}/{y}.mvt
- ズームレベル14
- レイヤ名: `"250mesh"`
- 点データ
- プロパティ:
  - KEY_CODE: メッシュコード
  - val: 人口総数

[地域メッシュ統計]: http://www.stat.go.jp/data/mesh/

### [地域メッシュ統計] 500mメッシュ人口データ
- URL: https://cieloazul310.github.io/mvt-tiles/tile/population_500m/{z}/{x}/{y}.mvt
- ズームレベル14
- レイヤ名: `"merged"`
- 点データ
- プロパティ:
  - KEY_CODE: メッシュコード
  - val_2005: 2005年の人口総数
  - val_2010: 2010年の人口総数
  - val_2015: 2015年の人口総数

[地域メッシュ統計]: http://www.stat.go.jp/data/mesh/