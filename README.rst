=====================================================================
人事採点システム
=====================================================================


■はじめに
--------------------------------------------------------------------

このシステムは、人事で揉める事柄を回避するために"公平"で"理解しやすい”、
また”運用しやすい”事を目標とした人事採点システムである。

- 1.経営者、従業員、共に公平であること。

- 1.経営者、従業員、共に理解しやすいこと。

- 1.経営者、従業員、共に運用しやすいこと。

■大まかな採点方法
--------------------------------------------------------------------

本人事採点システムの原型アイディアは、国家試験に多くある手法を人事に応用している。

大きく分けて３ブロックの採点項目ある。

- 不動基準の加算採点（加算点）

- 人事による採点（人事点）

- 部長や決定権がある人による採点（部長点）

不動基準は、国家試験の筆記に辺り、主に出席日数や遅刻欠席、その他の社内ルールに沿った採点で、**基準が不動（変化しない）な採点** である。

人事による裁量採点は、国家試験で言う口頭試験に辺り、実際に従業員に話を聞いたり勤務態度を評価したりする **人事による基準が変動する評価** である。

部長や決定権がある人による採点は、国家試験には無い項目だが、人事評価が低くてもボーナス点として別途追加出来る **人事以外の基準が変動する評価** である。

ここで、それぞれの項目による採点比率は以下のようになる。

:不動基準の加算採点（加算点）: ０〜50点
:人事による採点（人事点）: ０〜50点
:部長や決定権がある人による採点（部長点）: ０〜50点

ここで、加算点と人事点と部長点を足すと１００点を超えるが、
仮に加算点が低く人事点もあまり良くないが部長点が高い場合は救済もあると行った「微妙なさじ加減」を部長点50で補っている。

これにより、頭の良い人による採点攻略法を確立を防ぐ意味もあり、人間味もありつつ数値的に計測が行える仕組みとなる。



■不動基準の加算採点（加算点）について
--------------------------------------------------------------------
不動の基準（社則に沿った内容など）があれば、その基準を元に加算の仕組みを組む。

例えば


.. csv-table::
	:header: 項, 名称, ★★★★★, ☆★★★★,☆☆★★★,☆☆☆★★,☆☆☆☆★
	:widths: 1,  30,   10,   20 , 10 ,  20 ,  40

	"1","出勤率","90%以上:10点","80%以上:8点","60%以上:5点","50%以上:3点","30%以上:1点"
	"2","遅刻率","10%以下:10点","80%以下:8点","60%以下:5点","50%以下:3点","30%以下:1点"


:出勤率: 欠勤日数/出勤日数*100 (%)
:遅刻率: 遅刻日数/出勤日数*100 (%)

と言った形で、決まった規則によって数量的に計算出来る項目を加算して行きます。

加算点が全て最良で合った際に、先ほどの５０点に整うように項目数分の底上げも行うと綺麗に整います。

:最大50点: 50/(最大点/項目数) =各項目点に加算する数

■人事による採点（人事点）について
--------------------------------------------------------------------

人事による採点は、人事に携わる方は既に持っている場合がありますが、新規に人事を行うことを想定して、以下のような項目

:評価基準: 良=10,普=5,悪=1

の様な感覚による評価を数値化する指標を持ちつつ、

:勤務態度: 悪(1)
:技術: 良(10)
:スピード: 良(10)
:あいさつ: 良(10)
:仕事の進み方: 普(5)

と言った形で評価と数値化を行い、その合計が最大５０に収まるように計算する。


■部長や決定権がある人による採点（部長点）について
--------------------------------------------------------------------

この点はボーナス点になる。採点方法は人事と変わらないが、人事以外の人（部長クラスなど）が採点することで救済することが出来る。


■それぞれの採点割合
--------------------------------------------------------------------

会社により合格点を幾つにするかは自由とし、仮に以下のように仮説を組む。

:合計90点以上: 優秀でお手本になる従業員
:合計80点以上: 注意が必要だが勤務に支障ない従業員
:合計70点以上: 注意が必要で勤務に支障が出始めてる従業員
:合計60点以上: 注意が必要で勤務に支障が出てる従業員
:合計50点以下: ヤバイ。

この採点指標を元に、給料面や昇給、人事を考えると言ったアイディアは如何だろうか。

2018.3.19　ドラフト



License
----------------------------------------------------

    The MIT License (MIT) Copyright (c) 2017 Yuta Kitagami (kitagami@artifactnoise.com,@nonnoise)
