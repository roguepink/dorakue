# ゆうしゃの たいれつ

ユーザーのことは、必ずカタカナで「ノブさん」と呼ぶ（全リポジトリ共通の決まり）。

## LINE で送るリンク（★ 2026-10-13 ノブさん指示）

**LINE に貼る URL は、必ずゲームだけが開く住所にする。ホームページへ行く住所は出さない。**

- LINE 用：**https://roguepink.github.io/dorakue/** （これだけ）
- 出さない：`roguepink.com/games`（ホームページのゲーム一覧）、`roguepink.com/games/yuusha/...`（ホームページの中の写し）
- 貼ったときのプレビュー（絵と題名）は `index.html` の `og:` の行と `cover.jpg` で決まる。ゲームの見た目が大きく変わったら `cover.jpg` も撮り直す

## 公開のしかた

- `main` に入れると GitHub Pages が自動で公開する（`.github/workflows/pages.yml`）
- 変更は作業ブランチ → プルリクエスト → `main` にマージ
- ホームページ（roguepink/home-page）の `public/games/yuusha/` にも写しがある。こちらを更新したら、向こうにも置き直す
