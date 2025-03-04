# DJ Library
<img width="1130" alt="スクリーンショット 2024-07-14 12 34 26" src="https://github.com/user-attachments/assets/699916d9-5625-453f-93cc-c83e6db31e8b">

## サービスの概要

DJに向けて楽曲の推薦と最適なプレイリストの提案を行います。

## サービスを開発した背景

DJ Libraryは、DJがプレイリストを作成する際に役立つツールを提供することを目的として開発されました。楽曲の特徴量に基づいて、似たような雰囲気の曲を簡単に見つけることができます。

## サービスのURL
[サービスのURL](https://djlibrary-eff32ad73f3d.herokuapp.com/)

## アプリに込めた思い

DJはターンテーブルやミキサーを使って、場所や雰囲気に合った音楽をノンストップで流し続けています。つまり、曲と曲の間を違和感なく繋ぎ合わせるということをしています。ダンスパーティーなどにおいてDJは重要な役割を果たしますが、DJ自身は休憩やダンスを楽しむことができません。そこで、DJを手助けするサービスを構想しました。

## 主な機能の説明

DJ-libraryは、Spotify APIを利用して楽曲の特徴量を取得し、ユーザーに推薦する楽曲を取得しています。そして楽曲の特徴量に基づいて楽曲をソートする機能も備えています。

- **楽曲特徴量の取得**：Spotify APIを利用して楽曲の特徴量を取得します。
- **楽曲推薦**：ユーザーが入力した楽曲に基づいて、Spotify APIを用いて似た楽曲を推薦します。
- **楽曲ソート**：特定の基準（ダンスビリティ、エネルギー、テンポなど）に基づいて楽曲をソートします。

## 使用技術

- **フロントエンド**：React.js
- **バックエンド**：Django
- **その他**：Spotify API, AWS

## 画面遷移図

![画面遷移図](path/to/your/screen-transition-diagram.png)

## 今後の展望

- **プレイリスト作成の高精度化**：より高精度なプレイリスト作成機能を機械学習で実現する。
- **既存のサービスとの連携**：Dj-libraryで作成したプレイリストをSpotifyやApple Musicに追加する機能を追加する。
- **UIの改善**：ユーザーが使いやすいUIを追求する。
- **曲と曲の間を繋ぐ**：DJの役割を果たす機能を追加する。
