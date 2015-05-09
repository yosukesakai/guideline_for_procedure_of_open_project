
---
#ApacheLicense2.0のライセンス付与のしかた


以下の1-3の作業を行って下さい。


##1.以下のテキストをソースコードなどに示す

ソースコードのファイルが複数ある場合は、全てのファイルのコードの冒頭に記載します。


```
   Copyright [yyyy] [name of copyright owner]

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.
```



##2.LICENSEファイルを同梱する

配布するファイルが入ったフォルダの、最上位階層(トップディレクトリ)に、以下のファイルを置きます。
 
"http://www.apache.org/licenses/LICENSE-2.0.txt"

もしくは

"http://www.apache.org/licenses/LICENSE-2.0.html"



##3.ApacheLicense2.0が適用されていることをトップページに示す


さいごに、プロジェクトのトップページや、README.md(GitHubの場合)に、このライセンスが適用されていることを記載します。

```
*** by xxx, yyy, and zzz is licensed under the Apache License, Version2.0
```

この表記自体は、ライセンスの対象が明確でないので、有効性は十分ではありません。しかし、プロジェクトを紹介するウェブサイトのトップページや、githubのREADMEに記載することで、このプロジェクトのコードにどんなライセンスが適用されているのかが一見してわかるようになります。

あくまで参考、補助的な表記として掲載するのが良いでしょう。実質的なライセンス効力があるのは、各ソースコードの冒頭に記載されたライセンス表記である、と考えるべきででしょう。
詳細はウェブサイト構築ガイドラインを参照して下さい。


---
###参考
```
方法について示した既存の文書が、ふたつあります。

A.第三者的なユーザのオリジナルコードにApacheライセンスを付与する方法 (ライセンスの末尾に記載)(注1)
B.Apacheサーバーそのもののディストリビューション(のコード)にApacheライセンスを付与する方法 (Apacheのウェブサイトに記載)(注2)

本来はAに従うだけで良いはずですが、どうも不十分に思えます。
なので、実際にApacheで配布されているファイルを参照しつつ、両者を併せた、より適切であろうと思われる方法を作ってみました。
Apache Licenseの適用方法が、いろいろなウェブサイトでコメントとして書かれていますが、怪しい(=有効性に疑問がある)ものもあるので注意して下さい。
```


###注1 Apache Licenseの適用の方法 (ライセンス原文末尾部分より引用)

```
(英文)
   APPENDIX: How to apply the Apache License to your work.

      To apply the Apache License to your work, attach the following
      boilerplate notice, with the fields enclosed by brackets "[]"
      replaced with your own identifying information. (Don't include
      the brackets!)  The text should be enclosed in the appropriate
      comment syntax for the file format. We also recommend that a
      file or class name and description of purpose be included on the
      same "printed page" as the copyright notice for easier
      identification within third-party archives.

   Copyright [yyyy] [name of copyright owner]

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0       

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.


(和文)
付録： Apache Licenseの適用の仕方

あなたの製作物にApache Licenseを適用するときは、次の定型文を添付してください。ただし、"[]"で囲まれている部分は、あなた自身の識別情報に置き換えてください（その際、角括弧は取り除きます）。また、この文言を該当するファイル形式に合ったコメント構文で囲んでください。さらに、第三者アーカイブ内での識別を容易にするため、ファイル名またはクラス名ならびに趣旨説明が著作権表示と同じ「印刷ページ」に現れるようにすることをお勧めします。

Copyright [yyyy] [著作権所有者の名前]

Apache License Version 2.0（「本ライセンス」）に基づいてライセンスされます。あなたがこのファイルを使用するためには、本ライセンスに従わなければなりません。本ライセンスのコピーは下記の場所から入手できます。

http://www.apache.org/licenses/LICENSE-2.0

適用される法律または書面での同意によって命じられない限り、本ライセンスに基づいて頒布されるソフトウェアは、明示黙示を問わず、いかなる保証も条件もなしに「現状のまま」頒布されます。本ライセンスでの権利と制限を規定した文言については、本ライセンスを参照してください。
```




###注2 ApacheライセンスをApacheサーバのコードに付与する方法
```
Applying the Apache License, Version 2.0
http://www.apache.org/dev/apply-license.html


Applying the license to new software
To apply the ALv2 to a new software distribution, include one copy of the license text by copying the file:

http://www.apache.org/licenses/LICENSE-2.0.txt

into a file called LICENSE in the top directory of your distribution. If the distribution is a jar or tar file, try to add the LICENSE file first in order to place it at the top of the archive. This covers the collective licensing for the distribution.

In addition, a correct NOTICE file MUST be included in the same directory as the LICENSE file.

Each original source document (code and documentation, but excluding the LICENSE and NOTICE files SHOULD include a short license header at the top. If the distribution contains documents not covered by CLA, CCLA or Software Grant (such as third-party libraries) then see the policy guide.
```


---
  
#Apache License 2.0を採用した理由 / 特許関連条項を含むライセンスについて



オープンソースライセンスには、いわゆる"特許関連条項"を含むものとそうでないものがある。この"特許関連条項"は、オープンソースソフトウェアユーザの特許リスクを回避する事項を明示する。

例えば、MIT License(注1)(2-Clause BSD License BSDとほぼ同じ)は非常にシンプルで自由度の高いライセンスであるが、特許リスクについての対処は特になされていない。一方で、BSDライセンスの不足部分を補って作成された(注2)Apache License 2.0(注3)は、特許への対処を定めた"特許関連条項(Patent Clause)"を第3条に含んでいる。

この条項は大きく二つの部分を含む。一つは、コントリビューター(=ライセンサー)がApache Licenseが付されたコードに関する特許権を持っていた場合、ユーザー(=ライセンシー)に対してこの特許技術の使用を許可する"自動ライセンシング"(注4)である。もう一つは、ユーザ(=ライセンシー)が、このコードが特許権を侵害しているとして訴訟を起こした場合、このユーザーに対するライセンスが停止されるという"特許報復"(注4)である。つまり、実質的にユーザ(ライセンシー)の権利行使を防ぐ効果がある。

こうした"特許関連事項"を含むライセンスの採用は、そうでないものの採用よりユーザにとってのリスクを大幅に削減する事ができる。また、コントリビューターが特許攻撃をしないという態度表明ともなる。

GRPにおける公開ライセンスは、非コピーレフト型が望ましい。八田氏が挙げた7つの代表的な特許関連条項を含むライセンス(注4)のうち、非コピーレフト型でかつgnu.orgが使用を控えるよう勧告していないものは、Apache Licenseのみである。以上から、GRPにおいてはApahe Licenseを採用するべきと考える。



注1  Open Source Initiative OSI - The MIT License (MIT) http://opensource.org/licenses/mit-license.php, OSG-JP The MIT License http://sourceforge.jp/projects/opensource/wiki/licenses%2FMIT_license

注2 独立行政法人 情報処理推進機構 OSSライセンスの比較および利用動向ならびに係争に関する調査 調査報告書 2010, pp.31

注3 Apache License, Version 2.0 http://www.apache.org/licenses/LICENSE-2.0, OSG-JP Apache License Version 2.0 http://sourceforge.jp/projects/opensource/wiki/licenses%2FApache_License_2.0,

注4 八田真行 オープンソース•ソフトウェア•ライセンスにおけるソフトウェア特許と商標の扱いに関する研究, 知財紀要 2011 vol.20
  
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
