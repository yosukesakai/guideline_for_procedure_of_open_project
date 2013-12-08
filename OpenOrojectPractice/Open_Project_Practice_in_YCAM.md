---


#YCAMにおけるオープン化の試み

山口情報芸術センター[YCAM]では、これまでいくつかのプロジェクトにおいて、成果をオープン化してきました。このドキュメントはこうしたプロジェクトをまとめたものです。


---

##Forest Symphony (2013)

###Summary

森林や樹木の存在に深い興味を抱いてきた坂本龍一が、東日本大震災以降,その関心を具体的な芸術表現として示したプロジェクト「Forest Symphony（フォレスト・シンフォニー）」。森林をはじめとした人類が生きる環境に目を向けることを意図して構想された「Forest Symphony」を、山口情報芸術センター［YCAM］のYCAM InterLabとのコラボレーションにより技術開発を進め、アートプロジェクトとしてインスタレーションやウェブサイトで公開します。本プロジェクトでは、樹木の生体電位を計測する機器を開発し、取得されたデータを集積・解析、坂本龍一が音楽へと変換、世界各地に存在する森と、樹々から奏でられる音源をもとにシンフォニーを構想します。YCAMでは、インスタレーション作品を展示するほか、Arduinoを使用し、樹木から電位を取得するための「アンプシールド」を希望者が入手できるよう、その制作に関する情報をオープンソースで公開します。また、今回収集している樹木の生体電位データも公開します。


###Object and License


|Object |Object|License |  
|------|--------|----|  
|ハードウェア制作情報 注1|基板の設計図(pdf)| CC BY-SA|
||基板の設計図(pdf) | CC BY-SA  |
||基板の設計図(Gerber Format File) | CC BY-SA|
||部品リスト | CC BY-SA|
|ソフトウェア 注2|ハードウェア制御ソフトウェア(Arduinoのスケッチ)、 | Apache License 2.0|
||生体電位データを扱う基礎的なソフトウェア(oF・Processing・MaxMSPのサンプル用コード)| Apache License 2.0|
|生体電位データ 注3|樹木から得られた生体電位データ | CC0|


注1 設計図の一部がpdf形式であるため、OSHW Defenitionには適合しない。  
注2 作品で使用する音響生成ソフトウェアは公開対象に含まない。  
注3 生体電位データの公開にCC0を適用した。CC0の採用はYCAM初であり、また、アートプロジェクトにおける採用は類を見ない。各地の樹木生体電位データは、YCAM Interlabウェブサイトとxivelyで公開している。  


<!--

######[ハードウェア制作情報]

基板の設計図(pdf) / CC BY-SA

基板の設計図(Gerber Format) / CC BY-SA

部品リスト / CC BY-SA


######[制御ソフトウェア、生体電位データを扱う基礎的なソフトウェア]

Arduinoのソフトウェア・コード(スケッチ)、oF・Processing・MaxMSPのサンプル用ソフトウェア・コード / Apache License 2.0

(作品で使用する音響生成ソフトウェアは公開対象に含まない)

######[生体電位データ]

樹木から得られた生体電位データ / CC0

```
生体電位データの公開にCC0を適用した。CC0の採用はYCAM初であり、また、アートプロジェクトにおける採用は類を見ない。

注:設計図の一部がpdf形式であるため、OSHW Defenitionには適合しない。
```
-->





###Website

FOREST SYMPHONY

http://forestsymphony.ycam.jp/info/#

Forest Symphony ｜ YCAM InterLab

http://interlab.ycam.jp/projects/forestsymphony






---

##YCAMサマースクール (2013)

###Summary

2011年よりYCAM館内に登場した、メディア工房「tecpot(テックポット)」では、単なる機材の使い方を学ぶだけでなく、メディアテクノロジーと日常生活との接点を考えるための想像力を刺激するようなプログラムが用意されました。
10周年記念祭プログラム「YCAMサマースクール」では、この工房機能を拡大させ、パーソナルファブリケーション（工業の個人化）という新しいものづくりの動きによる創作支援も行います。
参加者によるYCAMサマースクールでの成果は、参加者の意思に応じてオープン化されます。

###Object and License

Ocject|License
---- | -----------
Movie, Graphics, Drawing, 3D Modeling Data, Modulobe Data | CC License (depends)
Software Code | Apache License 2.0 (depends)


###Website

YCAMサマースクール  
http://yschool.ycam.jp


######成果の公開についての同意について

ワークショップ参加者が、主催者がワークショップ参加者の成果を公開することを認める契約書である同意書を作成し、運用した。
参加者には未成年が多く、この場合の契約の有効性について検討し、同意書の運用方法を定めた。(別途付録を参照のこと。)

ユーザは、"成果をオープン化する/しない"を選ぶことができる。

同意書は、2種類(成果がソフトウェア・コードについてのもの、それ以外のコンテントについてのもの)を作成した。前者はApacheLicense2.0などのソフトウェア用ライセンス、後者はCCライセンスやニコニ・コモンズなどの適用を前提としているためである。
公開する場所としてのウェブサイトについて、なるべく多様な公開方法を用いる事ができるよう設計した。(thingiverse、youtube、vimeo、ニコニコ動画、github、hascamvas etc.)




---
##Reactor for Awareness in Motion (RAM) (2013)
###Summary

“RAM is Food for Thought”

創造的なダンスのアイデアのための反応装置RAM
ステージを外部から俯瞰している演出家や振付家の視点を一旦無くしてみるとき、コンテンポラリーダンスにおけるダンサーは、舞台上で何を思考して次の動きを選んでいるのでしょうか？ダンサーが身体のレベルで把握している情報については、今までほとんど言語化されてきませんでした。ダンサーが周囲の環境から情報を受け取り、それにどう反応（react）するかという「ルール」をつくることをダンスとして仮定したとき、ダンサーがイメージする環境によってダンスは異なり、環境の中で自分をどう位置づけるかによってもダンスは異なってくるはずです。
RAMではダンサーという存在を、振付家によって予め決められた振付を再現する存在ではなく、環境の中で主体的に情報を発見し、豊かな動きのイマジネーションを見出していく存在として規定しており、そのための〈反応装置〉（＝知覚と思考のツール）をダンサーにもたらすことを目的としています。具体的には、オリジナルのツールキットとハードウェアによって、ダンスのアイデアをより刺激するための環境を仮想的に設定し、ダンサーがそれに反応して動くことによって、さらに環境自体が生成的に変化していく、という相互関係をつくりだします。

**本プロジェクトでは、GRPContractFormを採用した。**

###Object and License

Ocject|License
---- | -----------
Software | Apache License 2.0, GPL
Hardware | CC
Document | CC

###Website

Reactor for Awareness in Motion (RAM)

http://interlab.ycam.jp/projects/ram





---
##GRP Contract Form (2013)

###Summary

GRPContractFormは、クリエイティブでオープンな恊働の枠組み(=フレームワーク)を実現する、共同研究開発契約書のひながたです。いわゆるオープンソースコードと同様に、多くの人々が自由に利用し、改変し、派生物を生み出せるようにするため、GRPContractFormを公開します。  
このひながたが具体的に対象とするのは、アートセンターや劇場など、クリエイションを行う組織がアーティストやエンジニアを招いて、先進的なテーマについて滞在制作の形式で共同研究を行い、その成果をオープン化(=誰もが一定の範囲内で自由に利用できるようオープンライセンスを付して公開すること)し、更なる派生や発展を促す、という共同研究開発プロジェクトです。GRPContractFormは、このようなプロジェクトのフレームワークを実現するソースコードであると言っても良いでしょう。  
このひながたは、クリエイティブ・コモンズ・ライセンスのもとに公開されています(*)。利用者はライセンスの範囲で、自分たちのプロジェクトのためにアレンジ/フォークし、実利用することができます。Github上での更新リクエストも歓迎します。  


###Object and License

Ocject|License
---- | -----------
Contract Form, Document | CC BY-SA


###Website

GRP Contract Form

http://interlab.ycam.jp/projects/grp-contract-form



---
##Guest Research Project vol.2 (2012)

###Summary


先端的なテーマをもつアーティスト／技術者を研究員として招聘し、YCAM InterLabと共同で研究開発をおこなう滞在研究プログラム。YCAMにおける本格的な研究開発事業として、その成果を蓄積し、制作機能の更なる充実と活性化を図るとともに、開発内容を対外的に公開することで、国際的な技術者間の交流、最新の技術と新たな表現に関するプラットフォームの創造を目指しています。  

vol.2 ジェネレーティブ・メディアのためのコンポジション・ツール（2012年／研究員：ジェームス・ジョージ）  
「RGB+Depth」を含んだ多様な形式の情報を時間軸上に構成するopenFrameworks用のアドオン「ofxTimeline」ofxTimeline、ofxTimeline を基盤とする、openFrameworks無しで単体で動作可能なソフトウェア「Duration」を開発しました。
  



**並行してGRP Contract Formの開発を行い、GRP Contract Formを採用した。**

**YCAMのプロジェクトではじめてApache License 2.0を採用した。(ライセンス選定プロセスについては別途付録を参照のこと。)**

###Object and License

Ocject|License
---- | -----------
Software Code | Apache License 2.0
Document | CC



###Website

Guest Research Project vol.2―ジェネレーティブ・メディアのためのコンポジション・ツール

http://interlab.ycam.jp/projects/guestresearch/vol2


######二次利用事例

Blaus y Playmodes  Laser beams, light and sound installation | VAD  Festival | Girona | 2012   http://playmodes.com  
(PRIX ARS ELECTRONICA 2013 HONORARY MENTION)  

BlueBeams by Playmodes   
Laser and sound installation | VI Bienal de Arte | Lanzarote | 2012  
http://playmodes.com  

---
##EyeWriter 2.0 のつくりかた (2012)
###Summary

本マニュアルはYCAM(山口情報芸術センター)で2011年10月に制作公開された展覧会LabActVol1 The EyeWriterに際し、当館の教育普及事業の一環として制作されたThe Eyewriterの日本語制作マニュアルです。

**YCAMのプロジェクトではじめてCC BY-SAを採用した。(ライセンス選定プロセスについては別途付録を参照のこと。)**


###Object and License

Ocject|License
---- | -----------
Document | CC BY-SA



###Website

EyeWriter 2.0 のつくりかた

http://interlab.ycam.jp/projects/labact/eye-tracking-study/how-to-make-eyewriter2



EyeWriter 2.0とは、YCAMのスタッフも開発に参加した、眼球の動きによる視線の変化を検出するオープンソースの「視線入力技術」です。
会期を分けて2つの展覧会を開催しました。



---
##Guest Research Project vol.1 (2011)

###Summary


先端的なテーマをもつアーティスト／技術者を研究員として招聘し、YCAM InterLabと共同で研究開発をおこなう滞在研究プログラム。YCAMにおける本格的な研究開発事業として、その成果を蓄積し、制作機能の更なる充実と活性化を図るとともに、開発内容を対外的に公開することで、国際的な技術者間の交流、最新の技術と新たな表現に関するプラットフォームの創造を目指しています。  

vol.1 プロジェクタカメラ・ツールキット（2011年／研究員：カイル・マクドナルド）  
「Guest Research Project vol.1」では、ソフトウェアの開発や、メディアアートに関する国際的なプロジェクトで活躍するニューヨーク在住の技術者／アーティストのカイル・マクドナルド氏が、2011年8月から11月の約3ヶ月間にわたりYCAMに滞在しました。カイル氏は、対象物を3次元で計測する3Dスキャナー技術を、専門の機械を使用せずに実現するプロジェクト「DIY 3D Scanning」の作者として知られています。YCAMにおける共同研究開発では、この技術を応用し、プロジェクターによる大規模な映像投影に必要とされる技術「キャリブレーション（画像の投影位置や色を補正する技術）」を実現するためのソフトウェア「ProCamToolKit（プロジェクタカメラ・ツールキット）」の開発を行いました。




###Object and License


Ocject|License
---- | -----------
Software Code | MIT License
Document | 


###Website

YCAM Guest Research Project vol.1—プロジェクタカメラ・ツールキット

http://interlab.ycam.jp/projects/guestresearch/vol1


LabACT―視線を通じて世界と繋がる。「視線入力技術」

http://interlab.ycam.jp/projects/labact/eye-tracking-study

(オープンソース技術をテーマに展覧会を展開した)






---
##Choreography filmed: 5days of movement (2011)

###Summary

YCAMと振付家／ダンサーの白井剛が共同でおこなったビデオダンス制作プロジェクト。ひとつのビデオダンスを起点に、作品という概念がより広範な概念へと移行しつつある今日における映像制作、そして視聴体験の可能性を積極的に模索していくプロジェクトとして展開した。
このプロジェクトではまず、白井の代表的なダンス作品のひとつである『質量, slide ,& .』（2004年初演）を「映像としてのダンス」として再構成し、ビデオダンス作品『質量, slide ,& . in frames』を制作。その後、このビデオダンス作品を全編視聴できる特設ウェブサイトも制作した。このウェブサイトには、ほかにも完成した作品と使用されなかった映像素材とを比較する機能、撮影された全ての映像素材を一覧／ダウンロードする機能などが盛り込まれており、特に後者の機能では全映像素材にクリエイティブ・コモンズ・ライセンスが付与されており、視聴者が二次創作物を制作できるようになっている。



###Object and License

Ocject|License
---- | -----------
movie | CC BY-NC-SA

###Website
Choreography filmed: 5days of movement

http://c-filmed.ycam.jp/

Choreography filmed: 5days of movement

http://re-marks.ycam.jp/2011/c-filmed/



######二次利用事例

この公開されたコンテンツをもとに、BRDGがリミックス作品を制作した。


[BRDG013] primitive mindリリース! jealousguy×MaxRakisuta×白井剛

http://plumus.tokyomax.jp/894

[BRDG013] primitive mind

http://vimeo.com/49504217


######ライセンス選定プロセス


[CCを利用するか?]

現代の映像のあり方を考えたとき、素材を組み合わせていくという行為を他者に対しても開いていくことが自然であると考えられた。
こうした映像のあり方を見せる編集過程が見える形のアウトプットとなった。公開した映像を通じて、使われたものだけでなく、使われなかった素材も見えるようになっている。
こうした素材を使える方が自然だろう、ということで、CCを付して公開することとした。

[NCを付すか?]

白井氏の判断による。舞台作品は通常、収益を得るものである。これについて他者が商用利用することに違和感があった。
よって、NCを付すこととした。


---


<!--

#参考

##YCAM外での事例
IP3から

Arduino
CC BY-SA(EAGLE file),
GPLおよび LGPL(IDE),
商標

oF
MITライセンス

eyewriter2.0
CC BY-NC-SA(ハー ドウェア設計情報 instructables), GPL(ソフトウェア)


HIVE







######Fab的な事例
IPSJ田中論文から


FabLab的なクリエイションプラットフォーム、知財プラットフォーム、


田中論文、さまざまなパーソナルファブリケーション事例が上げられている、それぞれについて、知財がどのように扱われているかを確認する


fabcommons論文





##CC採用事例


###CCライセンスを採用していることの表記の例
```
国立情報学研究所 ヒカリ＆つばさの３択教室シリーズ

http://www.nii.ac.jp/service/portal/hikatsuba

この作品はクリエイティブ・コモンズ 表示 - 非営利 - 改変禁止 2.1 日本 ライセンスの下に提供されています。
```

```
朝日新聞出版

http://publications.asahi.com/mediactive/

この作品はクリエイティブ・コモンズ 表示 - 非営利 - 継承 2.1 日本 ライセンスの下に提供されています。
```
-->



---

  
<!--

##Licenses and Credits  

<a rel="license" href="http://creativecommons.org/licenses/by-sa/3.0/"><img alt="Creative Commons License" style="border-width:0" src="http://i.creativecommons.org/l/by-sa/3.0/88x31.png" /></a><br /> 
<span xmlns:dct="http://purl.org/dc/terms/" href="http://purl.org/dc/dcmitype/Text" property="dct:title" rel="dct:type">YCAMにおけるオープン化の試み </span><a xmlns:cc="http://creativecommons.org/ns#" href="https://github.com/yosukesakai/YCAMにおけるオープン化の試み"property="cc:attributionName" rel="cc:attributionURL">Produced by yosukesakai<br /></a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/3.0/">Creative Commons Attribution - ShareAlike 3.0 Unported License.<br />

-->


##Disclaimer
```
yosukesakai makes no guarantees whatsoever related to this text.
The persons involved in the creation/operation of this website (including other users) take no responsibility regarding 
the usage of this text (including any kind of use such as browsing, contribution, or external re-use; 
the same shall apply hereinafter).
When using this text, you are required to take personal responsibility. 
yosukesakai takes no responsibility regarding eventual damage resulting from your use of this text.
yosukesakai does not guarantee that your use of this text is legitimate according to applicable laws.
We don't guarantee in any way the legitimacy, accuracy and safety of all information provided as contents.
We make no guarantees regarding external website linked to from this site.
This text permits alteration or reuse based on the Creative Commons Attribution-ShareAlike 3.0 Unported License, 
however it does not permit forms of reuse that violate laws or other regulations.  
The use of images accompanying the text may be based on license agreements separate from the respective text licenses.  
yosukesakai may discontinue the publication of all or parts of this text and all other contents without prior notice.
```




