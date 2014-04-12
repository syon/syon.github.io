---
layout: default
title: "Vimコマンド"
categories: pages
---
{% include JB/setup %}

## Links

- [viコマンド（vimコマンド）一覧（検索・置換）](http://uguisu.skr.jp/Windows/vi.html)

## 起動・ファイルを開く・保存

ファイルを開く

    $ vim path/to/file

上書き保存して終了

    :wq

保存しないで終了

    :q!

## 検索

abcde を検索

    /abcde

abcde を検索（逆方向） ※Shiftキーを押すと逆

    ?abcde

次を検索

    n

前を検索 ※Shiftキーを押すと逆

    N
