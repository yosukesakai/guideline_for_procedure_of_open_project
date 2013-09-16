
---
#ApacheLicense2.0のライセンス付与のしかた


以下の1,2の作業を行って下さい。

```
(参考)
方法について示した既存の文書が、ふたつあります。

A.第三者的なユーザのオリジナルコードにApacheライセンスを付与する方法 (ライセンスの末尾に記載)
B.Apacheサーバーそのもののコードディストリビューション(のコード)にapacheライセンスを付与する方法 (Apacheのウェブサイトに記載)

本来はAに従うだけで良いはずですが、読んでみたところ、どうも不十分です。
なので、実際にApacheで配布されているファイルを参照しつつ、両者を併せた、より適切であろうと思われる方法を作ってみました。
Apache Licenseの適用方法が、いろいろなウェブサイトでコメントとして書かれていますが、怪しい(=有効性に疑問がある)ものもあるので注意して下さい。
```


##1.以下のテキストをソースコードなどに示す

ソースコードのファイルが複数ある場合は、全てのファイルのコードの冒頭に記載します。
NOTICEファイルやREADMEファイルがある場合(たぶんあるでしょう)、これにも記載します。

ウェブサイト、たとえばgithubのREADMEに記載するのは、見えやすくて良いかと思います。
しかし、ライセンスの対象が明確でないので、有効性は疑問です。
あくまで参考、補助的な表記として掲載するのが良いでしょう。実質的なライセンス効力があるのは、ソースコードの冒頭に記載されたものである、と考えるべきででしょう。
詳細はウェブサイト構築ガイドラインを参照して下さい。

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
 
ファイル名 : "LICENSE"

内容 : "http://www.apache.org/licenses/LICENSE-2.0.txt"に表示されているテキスト(注:全文を文末に貼付けます。)

注：拡張子はtxtでよいでしょう。



---



##参考1:Apache Licenseの適用の方法 (ライセンス原文末尾部分より引用)

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




##参考2: ApacheライセンスをApacheサーバのコードに付与するとき
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








注:LICENSE(テキストファイル)にはりつけるテキスト
------
```

                                 Apache License
                           Version 2.0, January 2004
                        http://www.apache.org/licenses/

   TERMS AND CONDITIONS FOR USE, REPRODUCTION, AND DISTRIBUTION

   1. Definitions.

      "License" shall mean the terms and conditions for use, reproduction,
      and distribution as defined by Sections 1 through 9 of this document.

      "Licensor" shall mean the copyright owner or entity authorized by
      the copyright owner that is granting the License.

      "Legal Entity" shall mean the union of the acting entity and all
      other entities that control, are controlled by, or are under common
      control with that entity. For the purposes of this definition,
      "control" means (i) the power, direct or indirect, to cause the
      direction or management of such entity, whether by contract or
      otherwise, or (ii) ownership of fifty percent (50%) or more of the
      outstanding shares, or (iii) beneficial ownership of such entity.

      "You" (or "Your") shall mean an individual or Legal Entity
      exercising permissions granted by this License.

      "Source" form shall mean the preferred form for making modifications,
      including but not limited to software source code, documentation
      source, and configuration files.

      "Object" form shall mean any form resulting from mechanical
      transformation or translation of a Source form, including but
      not limited to compiled object code, generated documentation,
      and conversions to other media types.

      "Work" shall mean the work of authorship, whether in Source or
      Object form, made available under the License, as indicated by a
      copyright notice that is included in or attached to the work
      (an example is provided in the Appendix below).

      "Derivative Works" shall mean any work, whether in Source or Object
      form, that is based on (or derived from) the Work and for which the
      editorial revisions, annotations, elaborations, or other modifications
      represent, as a whole, an original work of authorship. For the purposes
      of this License, Derivative Works shall not include works that remain
      separable from, or merely link (or bind by name) to the interfaces of,
      the Work and Derivative Works thereof.

      "Contribution" shall mean any work of authorship, including
      the original version of the Work and any modifications or additions
      to that Work or Derivative Works thereof, that is intentionally
      submitted to Licensor for inclusion in the Work by the copyright owner
      or by an individual or Legal Entity authorized to submit on behalf of
      the copyright owner. For the purposes of this definition, "submitted"
      means any form of electronic, verbal, or written communication sent
      to the Licensor or its representatives, including but not limited to
      communication on electronic mailing lists, source code control systems,
      and issue tracking systems that are managed by, or on behalf of, the
      Licensor for the purpose of discussing and improving the Work, but
      excluding communication that is conspicuously marked or otherwise
      designated in writing by the copyright owner as "Not a Contribution."

      "Contributor" shall mean Licensor and any individual or Legal Entity
      on behalf of whom a Contribution has been received by Licensor and
      subsequently incorporated within the Work.

   2. Grant of Copyright License. Subject to the terms and conditions of
      this License, each Contributor hereby grants to You a perpetual,
      worldwide, non-exclusive, no-charge, royalty-free, irrevocable
      copyright license to reproduce, prepare Derivative Works of,
      publicly display, publicly perform, sublicense, and distribute the
      Work and such Derivative Works in Source or Object form.

   3. Grant of Patent License. Subject to the terms and conditions of
      this License, each Contributor hereby grants to You a perpetual,
      worldwide, non-exclusive, no-charge, royalty-free, irrevocable
      (except as stated in this section) patent license to make, have made,
      use, offer to sell, sell, import, and otherwise transfer the Work,
      where such license applies only to those patent claims licensable
      by such Contributor that are necessarily infringed by their
      Contribution(s) alone or by combination of their Contribution(s)
      with the Work to which such Contribution(s) was submitted. If You
      institute patent litigation against any entity (including a
      cross-claim or counterclaim in a lawsuit) alleging that the Work
      or a Contribution incorporated within the Work constitutes direct
      or contributory patent infringement, then any patent licenses
      granted to You under this License for that Work shall terminate
      as of the date such litigation is filed.

   4. Redistribution. You may reproduce and distribute copies of the
      Work or Derivative Works thereof in any medium, with or without
      modifications, and in Source or Object form, provided that You
      meet the following conditions:

      (a) You must give any other recipients of the Work or
          Derivative Works a copy of this License; and

      (b) You must cause any modified files to carry prominent notices
          stating that You changed the files; and

      (c) You must retain, in the Source form of any Derivative Works
          that You distribute, all copyright, patent, trademark, and
          attribution notices from the Source form of the Work,
          excluding those notices that do not pertain to any part of
          the Derivative Works; and

      (d) If the Work includes a "NOTICE" text file as part of its
          distribution, then any Derivative Works that You distribute must
          include a readable copy of the attribution notices contained
          within such NOTICE file, excluding those notices that do not
          pertain to any part of the Derivative Works, in at least one
          of the following places: within a NOTICE text file distributed
          as part of the Derivative Works; within the Source form or
          documentation, if provided along with the Derivative Works; or,
          within a display generated by the Derivative Works, if and
          wherever such third-party notices normally appear. The contents
          of the NOTICE file are for informational purposes only and
          do not modify the License. You may add Your own attribution
          notices within Derivative Works that You distribute, alongside
          or as an addendum to the NOTICE text from the Work, provided
          that such additional attribution notices cannot be construed
          as modifying the License.

      You may add Your own copyright statement to Your modifications and
      may provide additional or different license terms and conditions
      for use, reproduction, or distribution of Your modifications, or
      for any such Derivative Works as a whole, provided Your use,
      reproduction, and distribution of the Work otherwise complies with
      the conditions stated in this License.

   5. Submission of Contributions. Unless You explicitly state otherwise,
      any Contribution intentionally submitted for inclusion in the Work
      by You to the Licensor shall be under the terms and conditions of
      this License, without any additional terms or conditions.
      Notwithstanding the above, nothing herein shall supersede or modify
      the terms of any separate license agreement you may have executed
      with Licensor regarding such Contributions.

   6. Trademarks. This License does not grant permission to use the trade
      names, trademarks, service marks, or product names of the Licensor,
      except as required for reasonable and customary use in describing the
      origin of the Work and reproducing the content of the NOTICE file.

   7. Disclaimer of Warranty. Unless required by applicable law or
      agreed to in writing, Licensor provides the Work (and each
      Contributor provides its Contributions) on an "AS IS" BASIS,
      WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or
      implied, including, without limitation, any warranties or conditions
      of TITLE, NON-INFRINGEMENT, MERCHANTABILITY, or FITNESS FOR A
      PARTICULAR PURPOSE. You are solely responsible for determining the
      appropriateness of using or redistributing the Work and assume any
      risks associated with Your exercise of permissions under this License.

   8. Limitation of Liability. In no event and under no legal theory,
      whether in tort (including negligence), contract, or otherwise,
      unless required by applicable law (such as deliberate and grossly
      negligent acts) or agreed to in writing, shall any Contributor be
      liable to You for damages, including any direct, indirect, special,
      incidental, or consequential damages of any character arising as a
      result of this License or out of the use or inability to use the
      Work (including but not limited to damages for loss of goodwill,
      work stoppage, computer failure or malfunction, or any and all
      other commercial damages or losses), even if such Contributor
      has been advised of the possibility of such damages.

   9. Accepting Warranty or Additional Liability. While redistributing
      the Work or Derivative Works thereof, You may choose to offer,
      and charge a fee for, acceptance of support, warranty, indemnity,
      or other liability obligations and/or rights consistent with this
      License. However, in accepting such obligations, You may act only
      on Your own behalf and on Your sole responsibility, not on behalf
      of any other Contributor, and only if You agree to indemnify,
      defend, and hold each Contributor harmless for any liability
      incurred by, or claims asserted against, such Contributor by reason
      of your accepting any such warranty or additional liability.

   END OF TERMS AND CONDITIONS

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


```

  
  
  
#Apache License 2.0の採用理由 / 特許関連条項を含むライセンスについて



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
