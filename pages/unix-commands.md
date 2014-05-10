---
layout: default
title: "UNIXコマンド"
categories: pages
---
{% include JB/setup %}

## Links

- [ジャンル別UNIXコマンド一覧](http://x68000.q-e-d.net/~68user/unix/genre.html)

## System

すぐにシャットダウン

    # shutdown -h now

すぐに再起動

    # shutdown -r now

## File, Directory

空のディレクトリを削除する

    find . -type d -empty -delete
