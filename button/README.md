# @akashic-assets/button

**@akashic-assets/button** は JavaScript で Akashic を用いたボタンのサンプルです。

## 利用方法

`@akashic-assets/button` を利用するには Node.js が必要です。

### 動作確認方法

以下のどちらかを実行後、ブラウザで `http://localhost:3000/game/` にアクセスすることでゲームを実行できます。

- `npm start`

- `npm install -g @akashic/akashic-sandbox` 後、 `akashic-sandbox .`

#### javascript

- `script/main.js` を編集することでサンプルプロジェクトの改変が可能です。

### アセットの更新方法

各種アセットを追加したい場合は、それぞれのアセットファイルを以下のディレクトリに格納します。

- 画像アセット: `image`
- スクリプトアセット: `script`
- テキストアセット: `text`
- オーディオアセット: `audio`

これらのアセットを追加・変更したあとに `akashic scan asset` をすると、アセットの変更内容をもとに `game.json` を書き換えることができます。

```sh
npm run lint
```
