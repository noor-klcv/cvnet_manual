---
layout: default
has_children: false

title: 1. API 概要
parent: WEB API
nav_order: 1
permalink: /API/1
---

# {{ page.title }}

{: .no_toc }



---

株式会社ディー・ティー・ピーが提供するLoyal CustomerシステムにアクセスするためのWeb APIです。HTTPSリクエスト（POSTリクエスト）で結果を取得する事が出来ます。
全てのAPIの結果はJSON形式となります。

WebAPIを利用する前にシステムへのログイン認証が必要となります。認証された場合、Tokenがセットされます。以降同一セッション内ではスマートフォンはTokenをﾛｰｶﾙｽﾄﾚｰｼﾞ内で保持し処理を行い、携帯電話はTokenをCookie内で保持し処理を行います。
（セットされるToken ： ASP.NET_SessionId、.ASPXAUTH）
Tokenの有効期間は60分です。
有効期間中は再ログイン(auth.aspx)不要、有効期間が切れた場合は再ログイン(auth.aspx)を行います。

※1 共通のhttpステータスコード（404（Not Found）等）は記述しておりません。
※2入力、出力ともに文字列の場合の日本語エンコードはShift-JIS (932)となります。

（2017/04/11 追記）
パラメータは、記号や日本語が含まれる可能性のあるものはすべてURLエンコードが必要になります
APIを呼び出すプログラムはAuth以外はAuthで認証されたセッションのCookieを引き継ぐ必要があります。(ASP.NET_SessionId、.ASPXAUTH) セッションは60分でタイムアウト
実装例）    

<BR>

curl -c cookie.txt "http://ap01.dtpnet.co.jp:85/cv.net_userxxx/isql/api/Auth.aspx?login_id=123&password=123"
（保存したcookieでアクセス）curl -b cookie.txt "http://ap01.dtpnet.co.jp:85/cv.net_userxxx/isql/api/Get_UserToken.aspx"

