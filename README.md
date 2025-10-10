# SKY-PerfecTV-EPG
XML EPG for SKY PerfecTV! channels

## Overview

This repository contains the XML EPG (Electronic Program Guide) for SKY PerfecTV channels. The EPG provides a schedule of the current and upcoming TV programs, enabling users to easily see what's on and plan their viewing.

Preview: https://dbghelp.github.io/epg.html?file=https://raw.githubusercontent.com/dbghelp/SKY-PerfecTV-EPG/refs/heads/main/perfectv.xml

## Features

- XML formatted EPG for SKY PerfecTV channels
- Up-to-date information on channel programming
- Easy integration with various applications and services

## Usage

To use the EPG data, you can fetch the XML file from this repository and parse it in your application to display the program schedule.

In your M3U8 playlist, 

1. Change your url-tvg to "https://raw.githubusercontent.com/dbghelp/SKY-PerfecTV-EPG/refs/heads/main/perfectv.xml":

```#EXTM3U url-tvg="https://raw.githubusercontent.com/dbghelp/SKY-PerfecTV-EPG/refs/heads/main/perfectv.xml" refresh="3600"```

2. Change your tvg-id to the following for the respective channels:
  
|   tvg-id   |         Channel Name          |
|------------|-------------------------------|
| BS193 | ＷＯＷＯＷシネマ |
| BS201 | BS10プレミアム |
| BS252 | ＷＯＷＯＷプラス 映画・ドラマ・スポーツ・音楽 |
| BS255 | 日本映画専門チャンネル |
| CS218 | 東映チャンネル |
| CS219 | 衛星劇場 |
| CS223 | 映画・チャンネルNECO |
| CS227 | ザ・シネマ |
| CS240 | ムービープラス |
| BS242 | J SPORTS 1 |
| BS243 | J SPORTS 2 |
| BS244 | J SPORTS 3 |
| BS245 | J SPORTS 4 |
| CS250 | スカイA |
| CS254 | GAORA SPORTS |
| CS257 | 日テレジータス |
| CS262 | ゴルフネットワーク |
| CS800 | スポーツライブ＋ |
| BS191 | ＷＯＷＯＷプライム |
| BS192 | ＷＯＷＯＷライブ |
| BS256 | ディズニー･チャンネル |
| CS296 | ＴＢＳチャンネル１ 最新ドラマ・音楽・映画 |
| CS297 | ＴＢＳチャンネル２ 名作ドラマ・スポーツ・アニメ |
| CS298 | テレ朝チャンネル１ |
| CS299 | テレ朝チャンネル２ |
| CS300 | 日テレプラス ドラマ・アニメ・音楽ライブ |
| CS301 | エンタメ～テレ☆シネドラバラエティ |
| CS305 | チャンネル銀河 歴史ドラマ・サスペンス・日本のうた |
| CS307 | フジテレビＯＮＥ スポーツ・バラエティ |
| CS308 | フジテレビＴＷＯ ドラマ・アニメ |
| CS309 | フジテレビＮＥＸＴ ライブ・プレミアム |
| CS801 | スカチャン1 |
| CS321 | ミュージック・ジャパンTV |
| CS322 | 音楽・ライブ！ スペースシャワーＴＶ |
| CS323 | MTV |
| CS324 | ミュージック・エア |
| CS325 | MUSIC ON! TV（エムオン!） |
| CS329 | 歌謡ポップスチャンネル |
| CS310 | スーパー！ドラマＴＶ #海外ドラマ☆エンタメ |
| CS311 | アクションチャンネル |
| CS312 | Dlife（ディーライフ） |
| CS314 | 女性チャンネル♪LaLa TV |
| CS316 | ミステリーチャンネル |
| CS317 | KBS World 韓流専門チャンネル |
| CS318 | Ｍｎｅｔ |
| CS290 | TAKARAZUKA SKY STAGE |
| CS292 | 時代劇専門チャンネル |
| CS293 | ファミリー劇場 |
| CS294 | ホームドラマチャンネル 韓流・時代劇・国内ドラマ |
| CS295 | MONDO TV |
| BS236 | アニマックス |
| CS330 | キッズステーション テレビアニメ･劇場版･ＯＶＡ |
| CS331 | カートゥーン ネットワーク 海外アニメ国内アニメ |
| CS333 | アニメシアターX(AT-X) |
| CS340 | ディスカバリーチャンネル |
| CS341 | アニマルプラネット |
| CS342 | ヒストリーチャンネル 日本・世界の歴史＆エンタメ |
| CS343 | ナショナル ジオグラフィック |
| CS349 | 日テレNEWS24 |
| CS351 | TBS NEWS |
| CS353 | ＢＢＣニュース |
| CS354 | CNNj |
| BS251 | ＢＳ釣りビジョン |
| CS339 | ディズニージュニア |
| CS363 | 囲碁・将棋チャンネル |
| BS234 | グリーンチャンネル |
| CS055 | ショップチャンネル |
| CS161 | ＱＶＣ（キューヴィーシー） |
| Ch.623 | ＷＯＷＯＷシネマ |
| Ch.625 | BS10プレミアム |
| Ch.628 | 衛星劇場 |
| Ch.629 | 東映チャンネル |
| Ch.630 | ＷＯＷＯＷプラス 映画・ドラマ・スポーツ・音楽 |
| Ch.631 | ザ・シネマ |
| Ch.632 | ムービープラス |
| Ch.633 | 映画・チャンネルNECO |
| Ch.634 | 日本映画専門チャンネル |
| Ch.635 | Ｖ☆パラダイス |
| Ch.636 | エキサイティング・グランプリ |
| Ch.580 | スポーツライブ＋ |
| Ch.584 | スポーツライブ＋ ２ |
| Ch.600 | FIGHTING TV サムライ |
| Ch.601 | ゴルフネットワーク |
| Ch.602 | GAORA SPORTS |
| Ch.603 | J SPORTS 1 |
| Ch.604 | J SPORTS 2 |
| Ch.605 | J SPORTS 4 |
| Ch.606 | J SPORTS 3 |
| Ch.607 | スカイA |
| Ch.608 | 日テレジータス |
| Ch.609 | 刺激ストロングチャンネル |
| Ch.665 | ダンスチャンネル by エンタメ～テレ |
| Ch.581 | スカチャン1 |
| Ch.585 | スカチャン5 |
| Ch.586 | スカチャン6 |
| Ch.587 | スカチャン7 |
| Ch.588 | スカチャン8 |
| Ch.589 | スカチャン9 |
| Ch.590 | スカチャン10 |
| Ch.591 | スカチャン11 |
| Ch.611 | テレ朝チャンネル１ |
| Ch.612 | テレ朝チャンネル２ |
| Ch.613 | フジテレビＮＥＸＴ ライブ・プレミアム |
| Ch.614 | フジテレビＯＮＥ スポーツ・バラエティ |
| Ch.615 | フジテレビＴＷＯ ドラマ・アニメ |
| Ch.616 | ＴＢＳチャンネル１ 最新ドラマ・音楽・映画 |
| Ch.617 | ＴＢＳチャンネル２ 名作ドラマ・スポーツ・アニメ |
| Ch.618 | エンタメ～テレ☆シネドラバラエティ |
| Ch.619 | 日テレプラス ドラマ・アニメ・音楽ライブ |
| Ch.620 | ディズニー･チャンネル |
| Ch.621 | ＷＯＷＯＷプライム |
| Ch.622 | ＷＯＷＯＷライブ |
| Ch.664 | チャンネル銀河 歴史ドラマ・サスペンス・日本のうた |
| Ch.638 | ミュージック・エア |
| Ch.639 | ミュージック・ジャパンTV |
| Ch.640 | MTV |
| Ch.641 | MUSIC ON! TV（エムオン!） |
| Ch.642 | 音楽・ライブ！ スペースシャワーＴＶ |
| Ch.644 | 歌謡ポップスチャンネル |
| Ch.645 | ミュージック・グラフィティＴＶ |
| Ch.647 | スーパー！ドラマＴＶ #海外ドラマ☆エンタメ |
| Ch.649 | ミステリーチャンネル |
| Ch.650 | アクションチャンネル |
| Ch.651 | Dlife（ディーライフ） |
| Ch.654 | 女性チャンネル♪LaLa TV |
| Ch.655 | アジアドラマチックTV（アジドラ） |
| Ch.656 | KBS World 韓流専門チャンネル |
| Ch.657 | ＫＮＴＶ |
| Ch.658 | Ｍｎｅｔ |
| Ch.535 | 大人のイキヌキ！ヌーヴェルパラダイス |
| Ch.659 | MONDO TV |
| Ch.660 | ファミリー劇場 |
| Ch.661 | ホームドラマチャンネル 韓流・時代劇・国内ドラマ |
| Ch.662 | 時代劇専門チャンネル |
| Ch.663 | アイドル専門チャンネルＰｉｇｏｏ |
| Ch.667 | アニメシアターX(AT-X) |
| Ch.668 | カートゥーン ネットワーク 海外アニメ国内アニメ |
| Ch.669 | キッズステーション テレビアニメ･劇場版･ＯＶＡ |
| Ch.670 | アニマックス |
| Ch.674 | ヒストリーチャンネル 日本・世界の歴史＆エンタメ |
| Ch.675 | ナショナル ジオグラフィック |
| Ch.676 | ディスカバリーチャンネル |
| Ch.677 | アニマルプラネット |
| Ch.560 | ＳＯＲＡ―お天気チャンネル― |
| Ch.565 | ＢＢＣニュース |
| Ch.566 | CNNj |
| Ch.567 | CNN U.S. |
| Ch.568 | 中国テレビ★大富チャンネル |
| Ch.570 | 日経CNBC |
| Ch.571 | 日テレNEWS24 |
| Ch.572 | TBS NEWS |
| Ch.529 | ベターライフチャンネル |
| Ch.536 | パチンコ★パチスロＴＶ！ |
| Ch.537 | パチ・スロ サイトセブンＴＶ |
| Ch.540 | 釣りビジョンＨＤ |
| Ch.542 | 寄席チャンネル |
| Ch.544 | 旅チャンネル |
| Ch.546 | 鉄道チャンネル |
| Ch.521 | 囲碁・将棋チャンネル |
| Ch.672 | ディズニージュニア |
| Ch.678 | 南関東地方競馬チャンネル |
| Ch.680 | ＪＬＣ６８０ |
| Ch.681 | ＪＬＣ６８１ |
| Ch.682 | ＪＬＣ６８２ |
| Ch.683 | ＪＬＣ６８３ |
| Ch.684 | ＪＬＣ６８４ |
| Ch.688 | グリーンチャンネル |
| Ch.689 | グリーンチャンネル２ |
| Ch.690 | ＳＰＥＥＤチャンネル（競輪ライブ） ６９０ |
| Ch.691 | ＳＰＥＥＤチャンネル（競輪ライブ） ６９１ |
| Ch.692 | ＳＰＥＥＤチャンネル（競輪ライブ） ６９２ |
| Ch.693 | ＳＰＥＥＤチャンネル（競輪ライブ） ６９３ |
| Ch.694 | ＳＰＥＥＤチャンネル（競輪ライブ） ６９４ |
| Ch.695 | ＳＰＥＥＤチャンネル（競輪ライブ） ６９５ |
| Ch.696 | ＳＰＥＥＤチャンネル（競輪ライブ） ６９６ |
| Ch.701 | 地方競馬ナイン ７０１ |
| Ch.702 | 地方競馬ナイン ７０２ |
| Ch.703 | 地方競馬ナイン ７０３ |
| Ch.518 | フェニックステレビ（鳳凰衛視） |
| Ch.523 | ショップチャンネル |
| Ch.525 | ＱＶＣ（キューヴィーシー） |
| Ch.527 | ジュエリー☆ＧＳＴＶ |
| Ch.528 | セレクトショッピング |
| Ch.942 | ｋｍｐチャンネル |
| Ch.943 | プレイボーイ チャンネル |
| Ch.944 | レインボーチャンネル |
| Ch.945 | ミッドナイト・ブルー |
| Ch.946 | パラダイステレビ |
| Ch.947 | チェリーボム |
| Ch.957 | ＶＥＮＵＳ |
| Ch.958 | バニラスカイチャンネル |
| Ch.959 | エンタ！９５９ |
| Ch.960 | Zaptv |
| Ch.963 | ダイナマイトTV |
| Ch.964 | AV王 |
| Ch.965 | レッドチェリー |
| Ch.966 | Splash |
| Ch.967 | フラミンゴ |
| Ch.599 | スカパー！プロモ599 |
