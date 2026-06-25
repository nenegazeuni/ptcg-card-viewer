# PTCG AI Battle Viewer

[Pokémon TCG AI Battle Challenge](https://www.kaggle.com/competitions/pokemon-tcg-ai-battle) 向けの公開ビューア。

**GitHub Pages:** https://nenegazeuni.github.io/ptcg-card-viewer/

## 機能

- カード検索・フィルタ（種別、タイプ、ex など）
- デッキ組み立てと枚数チェック
- 日本語カード名 + 英語名対応
- 公開リプレイの日本語カード名ビューア

## 出典

- 元Notebook: [taikimori/ptcg-card-list-viewer-deck-build](https://www.kaggle.com/code/taikimori/ptcg-card-list-viewer-deck-build)
- カードデータ: Kaggle コンペ提供の `JP_Card_Data.csv` / `EN_Card_Data.csv`
- リプレイ JSON: Kaggle simulation episode replay

## ライセンス・注意

コンペ提供データに基づく閲覧用ビューアです。Pokemon 関連の商標・画像は The Pokémon Company 等に帰属します。

リプレイ JSON は Cloudflare R2 などの外部ストレージから読み込みます。
