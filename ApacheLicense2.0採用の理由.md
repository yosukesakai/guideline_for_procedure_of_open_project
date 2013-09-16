#Apache License 2.0の採用理由 / 特許関連条項を含むライセンスについて



オープンソースライセンスには、いわゆる"特許関連条項"を含むものとそうでないものがある。この"特許関連条項"は、オープンソースソフトウェアユーザの特許リスクを回避する事項を明示する。

例えば、MIT License(注1)(2-Clause BSD License BSDとほぼ同じ)は非常にシンプルで自由度の高いライセンスであるが、特許リスクについての対処は特になされていない。一方で、BSDライセンスの不足部分を補って作成された(注2)Apache License 2.0(注3)は、特許への対処を定めた"特許関連条項(Patent Clause)"を第3条に含んでいる。

この条項は大きく二つの部分を含む。一つは、コントリビューター(=ライセンサー)がApache Licenseが付されたコードに関する特許権を持っていた場合、ユーザー(=ライセンシー)に対してこの特許技術の使用を許可する"自動ライセンシング"(注4)である。もう一つは、ユーザ(=ライセンシー)が、このコードが特許権を侵害しているとして訴訟を起こした場合、このユーザーに対するライセンスが停止されるという"特許報復"(注4)である。つまり、実質的にユーザ(ライセンシー)の権利行使を防ぐ効果がある。

こうした"特許関連事項"を含むライセンスの採用は、そうでないものの採用よりユーザにとってのリスクを大幅に削減する事ができる。また、コントリビューターが特許攻撃をしないという態度表明ともなる。

GRPにおける公開ライセンスは、非コピーレフト型が望ましい。八田氏が挙げた7つの代表的な特許関連条項を含むライセンス(注4)のうち、非コピーレフト型でかつgnu.orgが使用を控えるよう勧告していないものは、Apache Licenseのみである。以上から、GRPにおいてはApahe Licenseを採用するべきと考える。

---

注1  Open Source Initiative OSI - The MIT License (MIT) http://opensource.org/licenses/mit-license.php, OSG-JP The MIT License http://sourceforge.jp/projects/opensource/wiki/licenses%2FMIT_license

注2 独立行政法人 情報処理推進機構 OSSライセンスの比較および利用動向ならびに係争に関する調査 調査報告書 2010, pp.31

注3 Apache License, Version 2.0 http://www.apache.org/licenses/LICENSE-2.0, OSG-JP Apache License Version 2.0 http://sourceforge.jp/projects/opensource/wiki/licenses%2FApache_License_2.0,

注4 八田真行 オープンソース•ソフトウェア•ライセンスにおけるソフトウェア特許と商標の扱いに関する研究, 知財紀要 2011 vol.20

