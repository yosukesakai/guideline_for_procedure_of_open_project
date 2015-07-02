
---
#CCライセンス付与のしかた
以下の1-3の作業を行って下さい。

##1.Creative Commonsのウェブサイトでライセンス・コード生成する

プロジェクトごとにライセンス・コードを、下記ウェブサイトで生成します。

Get Creative Commons updates
http://creativecommons.org/choose/

```
BY-SA(YCAMでのデフォルト)のコードを生成するときは、以下を選んでください。

改変された作品が共有されることを許諾しますか？
>他の人が同じように共有するなら、許します

あなたの作品の商用利用を許しますか？
>はい

そのほかプロジェクトごとに、作品のタイトル、クレジットで表示すべき名前、作品のクレジット用URL、元になった作品のURLなどを入力してください。
```

生成したライセンス・コードには、検索エンジンが認識できるメタデータが埋め込まれています。

和文ページと英文ページとを制作する場合、それぞれに用いる和文版ライセンス・コード、英文版ライセンス・コードを埋め込むのがベストです。しかし、和文のウェブサイトに英文のライセンスコードを用いても大きな問題ありませんので、作成するライセンス・コードは英文のみでもかまいません。



##2.生成したライセンス・コードをコンテンツを掲載したウェブサイトに埋め込む

ライセンスが適用されるコンテンツが掲載されているそれぞれのページに(それぞれのページでライセンス・コードがレンダリングされて表示されるように)、ライセンス・コードを埋め込みます。


メタデータの例
(GRPContractFormでもちいたメタデータ)


```
<a rel="license" href="http://creativecommons.org/licenses/by-sa/3.0/"><img alt="Creative Commons License" style="border-width:0" src="http://i.creativecommons.org/l/by-sa/3.0/88x31.png" /></a><br /> 
<span xmlns:dct="http://purl.org/dc/terms/" href="http://purl.org/dc/dcmitype/Text" property="dct:title" rel="dct:type">GRP Contract Form</span><a xmlns:cc="http://creativecommons.org/ns#" href="http://interlab.ycam.jp/projects/grp-contract-form" property="cc:attributionName" rel="cc:attributionURL">  
Produced by the Yamaguchi Center for Arts and Media [YCAM],<br />
Planned and developed by YCAM InterLab,<br />
Supervised by Tasuku Mizuno (Creative Commons Japan, Attorney at Law),<br />
Supported by Dominick Chen (Creative Commons Japan)<br /></a>
GRP Contract Form is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/3.0/">Creative Commons Attribution - ShareAlike 3.0 Unported License.<br />
```

##3.Creative Commons Licenseが適用されていることをトッページに示す

さいごに、プロジェクトのウェブサイトのトップページや、NOTICEファイルやREADME.mdファイルがあるなら(たぶんあるでしょう)こうしたファイルにも、ライセンス・コードを埋め込みます。

もしhtmlを受け付けない場合は、同じ内容を平文で書いても良いでしょう。

プロジェクトを紹介するウェブサイトのトップページや、githubのREADMEに記載することで、このプロジェクトのコードにどんなライセンスが適用されているのかが一見してわかるようになります。  

この表記自体は、ライセンスの対象が明確でないので、有効性は十分ではありません。あくまで参考、補助的な表記として掲載するのが良いでしょう。実質的なライセンス効力があるのは、各コンテンツのページに記載されたライセンス表記である、と考えるべきででしょう。

```
e.g.
HIVE http://hive.ntticc.or.jp  

すべてのページのテンプレート(のページ末尾)に、ウェブサイトに掲載されたコンテンツにCCライセンスが適用されていることが表記されています。  
各コンテンツのページに、法的に有効なCCライセンスが示されています。  

大友良英　音楽と美術のあいだクロージング・トーク【前半】
http://hive.ntticc.or.jp/contents/artist_talk/20150222
```

---
#CC0ライセンス適用のしかた
##1.Creative Commonsのウェブサイトでライセンス・コード生成する

プロジェクトごとにライセンス・コードを、下記ウェブサイトで生成します。  
http://creativecommons.org/choose/zero/

生成したライセンスコードには、検索エンジンが認識できるメタデータが埋め込まれています。
和文ページと英文ページとを制作する場合、それぞれに用いる和文版ライセンス・コード、英文版ライセンス・コードを埋め込むのがベストです。
しかし、和文のウェブサイトに英文のライセンスコードを用いても大きな問題ありませんので、作成するライセンス•コードは英文のみでかまいません。



##2.生成したライセンス・コードをコンテントを掲載したウェブサイトに埋め込む。

ライセンスが適用されるコンテンツが掲載されているそれぞれのページに(それぞれのページでライセンス・コードがレンダリングされて表示されるように)、ライセンス・コードを埋め込みます。  

メタデータの例(ForestSymphony apiによるデータ取得ページでもちいたCC0のメタデータ)


```
><p xmlns:dct="http://purl.org/dc/terms/"
>xmlns:vcard="http://www.w3.org/2001/vcard-rdf/3.0#">
>  <a rel="license"
>     href="http://creativecommons.org/publicdomain/zero/1.0/">
>    <img src="http://i.creativecommons.org/p/zero/1.0/88x31.png"
>style="border-style: none;" alt="cc0" />
>  </a>
>  <br />
>  to the extent possible under law,
>  <a rel="dct:publisher"
>     href="http://interlab.ycam.jp">
>    <span property="dct:title">ycam interlab</span></a>
>  has waived all copyright and related or neighboring rights to
>  <span property="dct:title">bioelectric potential data from trees in "forest
>symphony"</span>.
>this work is published from:
><span property="vcard:country" datatype="dct:iso3166"
>      content="jp" about="http://interlab.ycam.jp">
>  japan</span>.
></p>
```

##3.Creative Commons Licenseが適用されていることをトッページに示す

さいごに、プロジェクトのウェブサイトのトップページや、NOTICEファイルやREADME.mdファイルがあるなら(たぶんあるでしょう)こうしたファイルにも、ライセンス・コードを埋め込みます。

もしhtmlを受け付けない場合は、同じ内容を平文で書いても良いでしょう。

プロジェクトを紹介するウェブサイトのトップページや、githubのREADMEに記載することで、このプロジェクトのコードにどんなライセンスが適用されているのかが一見してわかるようになります。  

この表記自体は、ライセンスの対象が明確でないので、有効性は十分ではありません。あくまで参考、補助的な表記として掲載するのが良いでしょう。実質的なライセンス効力があるのは、各コンテンツのページに記載されたライセンス表記である、と考えるべきででしょう。




---
#xivelyにおけるCC0の適用のしかた

xivelyにおいて、デバイス、データをpublicに設定した場合、CC0が適用される。
データにCC0が適用されていることは、xivelyから送られるデータのヘッダに表示されているが、一般ユーザはこれを通常見ることはない。
よって、デバイス、データをpublicにした上で、データの詳細を表示するページに、そのデータにCC0が適用されていることを記述する。


###xivelyでデータを公開する方法、データをpublicにする方法

```
デバイスのメタデータ編集画面で、publicを選択する。
```




###xivelyの各データのページにCC0を表記する


xivelyのメタデータにCC0が適用されていることを記述します。

xivelyにログオンして、"Develop"を選び、目的のデバイスを選び、画面左下の"メタデータ"を編集し、CC0を適用していること示します。

(htmlのコードを埋め込むのがベストなのですが、XivelyのDescriptionはhtmlを受け付けないため、プレーンテキスト版を作ってみました。)


メタデータの例(Forest Symphonyにおいて、樹木の生体電位データのメタデータ用に作成したテキスト)

```
Metadata

Description
CC0 1.0 Universal [http://creativecommons.org/publicdomain/zero/1.0/]
To the extent possible under law, YCAM InterLab has waived all
copyright and related or neighboring rights to bioelectric potential
data from trees in 'Forest Symphony'. This work is published from:
Japan.
For more detail, please refer to our website.

Creator
YCAM InterLab

Website
http://interlab.ycam.jp/en/projects/forestsymphony

```


###参考

######xivelyから送られるのデータのヘッダを確認する方法

```
xivelyのサポート曰く、"On each outgoing request via our API we send a header
called “X-License” which points to the license for the data."。


firefoxのaddon”livehttpheaders”を用いて確認する。

これで、例えば以下を確認。
API Endpoint
https://api.xively.com/v2/feeds/176655154

CC0の表記を確認できる。
```

######xivelyではCC0を採用した (2013)
デバイス、データをpublicにした場合、CC0が採用される。

```
xively Public and Private Feeds
https://xively.com/dev/docs/api/security/public_and_private_feeds/
“When a device is public, the device and its data are made available under the terms of the Creative Commons CC0 1.0 Universal license.”

xively Accounts, data, devices: An explanation
http://blog.xively.com/2013/05/15/accounts-data-devices-an-explanation/
“So, in Xively, if you make data public a Creative Commons CC0 1.0 Universal license is applied (both on its page and in headers when requested via the API), which expresses your ownership of your data but your desire to make it much more useful and usable to others that might access the data. Read more about CC0 here.”

Public and Private Feeds
https://xively.com/dev/docs/api/security/public_and_private_feeds/
Your data is your data. For full details please see the LogMeIn Terms of Service.
You can specify whether or not a Feed is private to you or publicly available to others, by configuring the privacy settings using the “private” attribute of the Feed.
When a device is private, the device and its data are only accessible to you and those to whom you selectively grant access. A private device is not listed in Xively’s online public directory.
When a device is public, the device and its data are made available under the terms of the Creative Commons CC0 1.0 Universal license. For detailed information, visit the Creative Commons website, http://creativecommons.org/publicdomain/zero/1.0/, but briefly this means that all data about and created by a public device can be copied, shared and modified by anyone, even for commercial gain. Public devices will be listed in Xively’s online public directory.


```

######xivelyに対するCC0についての問い合わせに対する返信 (抜粋)

```
Subject: concerned in data of Public Device under CC0
JUL 31, 2013  |  03:50PM BST

Putting the information in the description would work. All public
devices on Xively have their data licensed under the CC0 1.0 license
(http://creativecommons.org/publicdomain/zero/1.0/). On each outgoing
request via our API we send a header called “X-License” which points
to the license for the data.


```
  
---  
#CC BY-SA 選定プロセス

```
[CCを利用するか?]

「EyeWriter 2.0 のつくりかた」を普及させ、なるべく多くの人に利用してもらいたい。WSなどで複製して利用してもらってかまわない。使用許諾の要請があれば許諾するが、その障壁や手間を省きたい。
公開に際しては、YCAMの成果物であることを示したい。利用者や関連する人々が作り方がYCAMの成果物であることを知ることで、新たな関係が生み出されることを期待する。また、YCAMの宣伝効果も期待する。
普及・伝搬を促進し、許諾の障壁を除き、著作者を明示するため、CCライセンスを付すことが妥当である。


[NDを付すか?]

他の利用者に、作り方を改良して、バージョンをあげてもらいたい。より良いものが作られ、波及していけばよい。また、自由に外国語に翻訳してもらってもかまわない。
派生物の創作を認めるため、NDを付さないのが妥当である。


[NCを付すか?]

YCAMでは当該コンテントを利用してマネタイズを行う余力がない。マネタイズできる知恵とエネルギーがある人が行えばよい。雑誌に掲載するなら、その分のコストを払える人に、やってもらえればよい。
文化庁の出版物のように、巻末に作り方を付した印刷物を販売する、というケースも考えられる。
よって、NCを付さないのが妥当である。


[SAを付すか?]

他の利用者が改変、変形または加工したものを公開する場合、YCAMの表示を行い、また別の者による更なる改良の余地を残したい。
よってSAを付すのが妥当である。


[リスクの検討]

雑誌に勝手に掲載された場合、作り方のみを印刷して販売された場合 > NCの項で検討済み。
反社会的、公序良俗に反する利用があった場合 > 現実にこのような利用がなされる可能性は大きくない。公開の結果、わずかな危険があるかもしれないが、メリットの方が大きいと考えられる。



```


---  
#CC0 選定プロセス  

```
[CC0とは]
CC0は著作権にもとづいて最大限の許諾を行うライセンスである。

[データの著作物性]
原則として、そもそもデータには著作権は発生しない。
そもそも、権利の発生しないデータについて、他者の利用を制限することはできない。

[データのライセンスの有効性]
なので、著作権にもとづくライセンスは、データに対しては、法的に有効とは言い切れない。

[データにCC0を付して公開する効果]
しかし、CC0を付すことで、第三者が自由に利用できる、ということを明示することができる。
さらに、希少なアートにおける利用事例として、訴求力を生むことができる可能性がある。
よって、データについてはCC0を採用するのが妥当である。
```


  
---
  
  

  
##Licenses and Credits  

<a rel="license" href="http://creativecommons.org/licenses/by-sa/3.0/"><img alt="Creative Commons License" style="border-width:0" src="http://i.creativecommons.org/l/by-sa/3.0/88x31.png" /></a><br /> 
<span xmlns:dct="http://purl.org/dc/terms/" href="http://purl.org/dc/dcmitype/Text" property="dct:title" rel="dct:type">Guideline_for_Procedure_of_Open_Project</span><a xmlns:cc="http://creativecommons.org/ns#" href="https://github.com/yosukesakai/Guideline_for_Procedure_of_Open_Project" property="cc:attributionName" rel="cc:attributionURL">  
Produced by yosukesakai<br /></a>
Guideline_for_Procedure_of_Open_Project (document) is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/3.0/">Creative Commons Attribution - ShareAlike 3.0 Unported License.<br />



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
