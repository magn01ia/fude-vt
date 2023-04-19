# fude-vt

主にunvtを使った登記所備付地図のベクトルタイル作成練習。  
[unvt/nanban](https://github.com/unvt/nanban)を利用して作業。  
 
### 元データ  
[G空間情報センター登記所備付地図変換済みgeojson](https://front.geospatial.jp/moj-chizu-shp-download/)

### 変換  
Tippecanoe  
- pbf  
--no-tile-compression --no-feature-limit --no-tile-size-limit  

### スタイル
charites

### 目次  
#### 茨城県
- 水戸市  
zoom：1-16  
url:https://magn01ia.github.io/fude-vt/zxy/mito/{z}/{x}/{y}.pbf  
style(作成中)

