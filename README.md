# WebGIS4G-SPASE
WebGIS repository for G-SPASE project.

Web-GISとは、ウェブブラウザ上で一般的なGIS(地理情報システム)としての地理空間情報の表示、インタラクティブな操作、情報の共有が可能なマッピングシステムです。G-SPASE 第一期は、オープンソースWeb-GISとして代表的な GeoServer を運用していましたが、よりイノベーティブに多くの方々と協業し、よりオープンな環境でのWeb-GIS構築が可能な GitHub にプラットフォームを移動し、運用をはじめました。

# 目的：
* 地理空間情報を格納・共有する
* 地理空間情報を可視化する
* 格納されたデータの流通を辿る

# 内容：
すべての情報は GitHub の GESTISS organization にそれぞれレポジトリごとに区分し格納しています。データの閲覧などは、GitHub アカウントがなくても利用可能ですが、データやWeb-GISブラウザを複製する場合は、GitHub アカウントを作成の上、適宜 Fork してご利用ください。

GESTISS/G-SPASE on GitHub
https://github.com/gestiss/

# 利用の仕方：

主に、以下の３種類の利用方法がありますが、GitHubの使い方次第で、その利用方法は無限にあります。新しい利用方法を見つけたら、ぜひWebGIS4G-SPASEリポジトリのIssue に追記してください。

- 二次元簡易ウェブマップ

GeoJSON/TopoJSON 形式でレポジトリに追加。GitHub上でウェブマップに自動的に切り替わります。背景は OpenStreetMap になります。

- 二次元ウェブマップ

https://github.com/gestiss/gsimaps4gestiss

地理院地図(GSImaps)をベースとした gsimaps4gestiss レポジトリをForkし、任意のレイヤとしてデータレイヤを追加することで、ウェブマップシステムをカスタマイズ可能です。背景地図も任意に選べます。


- 三次元ウェブマップ

https://github.com/gestiss/cesiumGitHubPages4gestiss

Google Earthライクな三次元表示を可能にするオープンソース描画エンジンCesiumJS の代表的な利用例である cesiumGitHubPages をベースとした cesiumGitHubPages4gestissレポジトリをForkし、任意のレイヤとしてデータレイヤを追加するなどカスタマイズ可能です。

# 利用可能なデータ形式：
ベクタデータの場合、空間参照系が EPSG:4326 で定義された GeoJSONもしくはTopoJSON形式で格納してください。
ラスタデータの場合、空間参照系が EPSG:900913 のXYZタイルで定義された JPG もしくはPNG形式で格納してください。

# ライセンス
© GESTISS/G-SPASE, CC BY 4.0

本レポジトリに格納されているデータ、コンテンツは原則ライセンスをコンテンツ管理者が管理し定義しますが、記述がされていないコンテンツは原則 CC BY 4.0 ライセンスとして公開されます。
