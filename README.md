# msoffice_UD_color

<div align="right">
鶴見教育工学研究所<br />
タナカ ケンタ<br />
<a href="https://mana.bi/">https://mana.bi/</a>
</div>

Microsoft Officeでカラーユニバーサルデザインに基づく配色をするためのパレット (XMLファイル) を提供します。


## パレットについて

以下の2種類のカラーパレットを提供します。


### カラーユニバーサルデザイン推奨配色セット第4版

* https://jfly.uni-koeln.de/colorset/

Microsoft Officeではアクセントカラーは6色までしか登録できないため、色セットから、以下を選択しました。また、ハイパーリンクは「青」、表示済みのリンクは「紫」をそれぞれ指定しています。


|見本|色名|RGB|カラーコード|
|:-:|:-:|:-:|:-:|
|<span style="background-color: #000000;">____</span>|黒|(0,0,0)|#000000|
|<span style="background-color: #FFFFFF;">____</span>|白|(255,255,255)|#FFFFFF|
|<span style="background-color: #84919E;">____</span>|グレー|(132,145,158)|#84919E|
|<span style="background-color: #C8C8CB;">____</span>|明るいグレー|(200,200,203)|#C8C8CB|
|<span style="background-color: #FF4600;">____</span>|赤|(255,75,0)|#FF4600|
|<span style="background-color: #FFF100;">____</span>|黄|(255,241,0)|#FFF100|
|<span style="background-color: #03AF7A;">____</span>|緑|(3,175,122)|#03AF7A|
|<span style="background-color: #005AFF;">____</span>|青|(0,90,255)|#005AFF|
|<span style="background-color: #990099;">____</span>|紫|(153,0,153)|#990099|
|<span style="background-color: #804000;">____</span>|茶色|(128,64,0)|#804000|


### JIS安全色

* http://safetycolor.jp/shiteichi/

6色定義されている安全色をアクセントカラーとして設定しました。グレー系についてはカラーユニバーサルデザイン推奨配色セットに準じました。ハイパーリンクは「青」、表示済みのリンクは「赤紫」をそれぞれ指定しています。


|見本|色名|RGB|カラーコード|
|:-:|:-:|:-:|:-:|
|<span style="background-color: #000000;">____</span>|黒|(0,0,0)|#000000|
|<span style="background-color: #FFFFFF;">____</span>|白|(255,255,255)|#FFFFFF|
|<span style="background-color: #84919E;">____</span>|グレー|(132,145,158)|#84919E|
|<span style="background-color: #C8C8CB;">____</span>|明るいグレー|(200,200,203)|#C8C8CB|
|<span style="background-color: #FF4600;">____</span>|赤|(255,75,0)|#FF4B00|
|<span style="background-color: #F6AA00;">____</span>|橙|(246,170,0)|#F6AA00|
|<span style="background-color: #F2E700;">____</span>|黄|(242,231,0)|#F2E700|
|<span style="background-color: #00B06B;">____</span>|緑|(0,176,107)|#00B06B|
|<span style="background-color: #1971FF;">____</span>|青|(25,113,255)|#1971FF|
|<span style="background-color: #990099;">____</span>|赤紫|(153,0,153)|#990099|


## インストール

ダウンロードしたXMLファイルを、Microsoft Officeのテンプレートフォルダーに移動 / コピーしてください。Windowsでは、一般的に以下のフォルダーです。ドライブレターや `xxxxx` はご自身の環境に置き換えてください。

```
C:\Users\xxxxx\AppData\Roaming\Microsoft\Templates\Document Themes\Theme Colors
```

macOSでは、以下のフォルダーになるようです。細かな文字列は異なるかもしれません。

```
/Users/xxxxx/Library/Group Containers/UBF8T346G9.Office/User Content.localized/Themes.localized/Theme Colors
```

それぞれ、最新のMicrosoft 365で確認しました。


## ライセンス

パレット (XMLファイル) のライセンスはMITライセンスとします。
