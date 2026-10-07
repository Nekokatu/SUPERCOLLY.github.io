# SUPER COLLY 公式サイト

SUPER COLLY の公式サイト用ファイルです。

## 公開URL

https://nekokatu.github.io/SUPERCOLLY.github.io/

## ファイル構成

- `index.html` — サイト本体
- `style.css` — デザイン・レイアウト
- `script.js` — JavaScript
- `robots.txt` — 検索エンジン向け設定
- `sitemap.xml` — サイトマップ
- `images/` — サイトで使用する画像

## 画像の差し替え

サイト内で使用している画像は、`images/` フォルダ内の同じファイル名の画像を上書きするだけで差し替えできます。
HTMLやCSSを編集する必要はありません。

### 差し替え可能な画像一覧

| ファイル名 | 用途 | 推奨形式 |
|---|---|---|
| `images/logo.png` | SUPER COLLYのロゴ。ヘッダーとトップページのメインタイトルに使用 | PNG推奨（透過可） |
| `images/hero.jpg` | トップページのメインビジュアル | JPG / PNG |
| `images/screenshot01.jpg` | WORLDセクションのメインスクリーンショット | JPG / PNG |
| `images/screenshot02.jpg` | WORLDセクションのスクリーンショット | JPG / PNG |
| `images/screenshot03.jpg` | WORLDセクションのスクリーンショット | JPG / PNG |
| `images/screenshot04.jpg` | WORLDセクションのスクリーンショット | JPG / PNG |
| `images/screenshot05.jpg` | WORLDセクションのスクリーンショット | JPG / PNG |
| `images/og-image.jpg` | XなどでサイトURLを共有したときに表示されるOGP画像 | JPG / PNG |

### ロゴについて

`images/logo.png` にロゴ画像を入れると、以下の2か所に自動で表示されます。

- ヘッダーのロゴ
- トップページのメインロゴ

ロゴ画像がまだ入っていない場合は、トップページの文字ロゴが自動的に表示されるため、ロゴを後から追加できます。

### 画像差し替え時の注意

- ファイル名は変更しないでください。
- `images/` フォルダの中に入れてください。
- JPGの場合は、現在使用しているファイルと同じ `.jpg` の名前にしてください。
- ロゴは透過PNGを推奨します。
- スクリーンショットは縦横比が違っていても、画像を切らずに表示するようにしています。
- 極端に大きな画像を使用するとページの読み込みが重くなるため、Web用に適度に圧縮してください。

## 外部リンク

現在、以下のページへのリンクを設定しています。

- X
  https://x.com/nekokatu0112
- UnityRoom
  https://unityroom.com/games/supercolly
- CreatorsCamp
  https://game-creators.camp/games/74811960/super_colly

SteamとNintendo Switchは、正式なページが公開された時点でURLを設定する予定です。

## 動画

YouTubeへの外部リンク欄は設けていません。

今後、ゲーム紹介動画などをサイト内で直接再生できる形にする予定です。

## 更新方法

1. GitHubの `SUPERCOLLY.github.io` リポジトリを開く
2. 変更したいファイルや画像をアップロード・上書きする
3. GitHub Pagesへの反映を待つ
4. 公開サイトを確認する

画像だけ変更する場合は、`images/` 内の同じファイル名の画像を差し替えるだけでOKです。

## レスポンシブ対応

PC・タブレット・スマートフォンのすべてで、基本的に**縦スクロールのみ**で閲覧できるようにしています。

画面幅が狭い場合は、画像や各セクションが自動的に縦方向へ並びます。

## WHY SUPER COLLY

「WHY SUPER COLLY」セクションを追加しています。

1996年生まれの開発者が、1996年に生まれた『スーパーマリオ64』に
自分なりの3Dアクションで挑戦する、というSUPER COLLYの制作理由を掲載しています。

## デザインについて

ゲームそのものを見せることを重視し、明るい空色・黄色・緑・赤を使った、
ファミリー向け3Dアクションゲームらしいレイアウトに変更しています。

画像の縦横比が違っていても、スクリーンショットは画像を切らずに表示します。

## トップ（HERO）について

トップのメインビジュアルは、`images/logo.png` のロゴ画像を使用します。

現在のHEROでは以下の装飾を使用していません。

- 画面上部の固定ヘッダー／ナビゲーション
- 「SUPER COLLY」のテキストロゴ
- メインビジュアル横の「JUMP!」「EXPLORE!」バッジ
- 雲の装飾
- 背景の円形装飾（太陽・図形）

そのため、ロゴとメインビジュアルを中心にしたシンプルなファーストビューになっています。
