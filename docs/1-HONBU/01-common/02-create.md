---
layout: default
title: '新規作成'
parent: '共通'
grand_parent: '本部用'
nav_order: 2
permalink: docs/honbu/common/create
---

# {{ page.title }}
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## 取引データ

<a href="/docs/00HONBU/img/10-common/create-torihiki.PNG" target="_blank">
<img src="/docs/00HONBU/img/10-common/create-torihiki.PNG" alt="create-torihiki">
</a>

業務選択【売上】- 【出荷・売上入力】をクリックします。

- ① 「修正/登録画面」

- ② ヘッダ情報を入力する事ができます。<br>
　売上日、掛計上日、取引区分、得意先、倉庫、掛率 <br>
　手入力伝票NO、関連伝票NO2、備考

- ③ 各種機能にて、品番を選択をします。<br>
「最終行追加」：1行づつ明細を追加する事ができます。<br>
「商品CD選択」：納品日ベースで、絵型を確認しながら、追加できます。<br>
「展開商品CD」：品番を入力し、色サイズを一括で追加する事ができます。<br>
「ﾊﾞｰｺｰﾄﾞ入力」：スキャナーでバーコードを読み、追加する事ができます。

- ④ 明細に、商品情報を表示します。<br>
　商品、色サイズ、原価フラグ、数量、上代単価、下代単価

- ⑤ 「追加」をクリックし、伝票作成します。


---

## 最終行追加

<a href="/docs/00HONBU/img/10-common/create-lastrow.PNG" target="_blank">
<img src="/docs/00HONBU/img/10-common/create-lastrow.PNG" alt="create-lastRow">
</a>

業務選択【売上】- 【出荷・売上入力】をクリックします。

- ① 「修正/登録画面」

- ② ヘッダ情報を入力する事ができます。<br>
　売上日、掛計上日、取引区分、得意先、倉庫、掛率  <br>
　手入力伝票NO、関連伝票NO2、備考

- ③「最終行追加」追加ボタンをクリック <br>
　または <br>
　「行」をダブルクリックし「はい」で行追加

- ④「一覧」より商品CDを選択

- ⑤「一覧」よりサイズ・カラーを選択「選択実行」

- ⑥ 数量を入力

- ⑦「追加」をクリックし、伝票作成します。

---

## 商品CD選択

<a href="/docs/00HONBU/img/10-common/create-shohin.PNG" target="_blank">
<img src="/docs/00HONBU/img/10-common/create-shohin.PNG" alt="create-shohin">
</a>

業務選択【売上】- 【出荷・売上入力】をクリックします。

① 「修正/登録画面」

② 得意先を入力

③ 展開商品CDに商品CDを入力し「展開」または「Enter」

④ 色サイズ毎の数量を入力し、<br>
　Enterキーまたは「↓」ボタンをクリックします。

⑤ 色サイズ毎の数量が展開されます。

⑥ 「選択実行」で完了となります

⑦ 「追加」をクリックし、伝票作成します。

---

## 展開品番


<a href="/docs/00HONBU/img/10-common/create-tenkai.PNG" target="_blank">
<img src="/docs/00HONBU/img/10-common/create-tenkai.PNG" alt="create-tenkai">
</a>

業務選択【売上】- 【出荷・売上入力】をクリックします。

① 「修正/登録画面」

② 得意先を入力

③ 展開商品CDに商品CDを入力し「展開」または「Enter」

④ 色サイズ毎の数量を入力し、<br>
　Enterキーまたは「展開」ボタンをクリックします。

**※数量入力毎に、Enterキーを押すと、右へ移動し、**<br>
    **最も右の色までいくと、次のサイズへ移動し、最後に展開へ移動します。** <br>
**※マスタ作成されていない物はグレースケールになっております。**

⑤ 色サイズ毎の数量が展開され、選択完了となります。

⑥ 「追加」をクリックし、伝票作成します。


---

## バーコード入力

<a href="/docs/00HONBU/img/10-common/create-barcode.PNG" target="_blank">
<img src="/docs/00HONBU/img/10-common/create-barcode.PNG" alt="create-barcode">
</a>

業務選択【売上】- 【出荷・売上入力】をクリックします。

① 「修正/登録画面」

② 得意先を入力

③ 「バーコード入力」ボタンをクリックします。

④ バーコード入力画面にて、タグのバーコードを読み取ります。

⑤ 読み取った内容が表示されます。

**※④の手順を繰り返す事で、複数の商品を読み取る事ができます。**

⑥ 読取終了後「選択実行」をクリックします。

⑦ 色サイズ毎の数量が展開され、選択完了となります。

⑧ 「追加」をクリックし、伝票作成します。
