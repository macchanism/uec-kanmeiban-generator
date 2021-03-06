# uec-kanmeiban-generator
## What is this?
UECの施設にある、建物名が書かれたパネル(舘名板, kanmeiban)っぽい画像を生成するやつ

<div align="center">
  <img src="./sample.png" alt="sample image"/>
</div>

## Usage
Webブラウザで [UEC Kanmeiban Generator](https://uec-kanmeiban-generator.matchaism.net) にアクセス

1. 建物名(building)を指定
2. フォントサイズ(font size)を指定
3. 建物名の位置を調整(margin-topが縦方向、leftが横方向)
4. `Preview`で舘名板をプレビュー
5. 完成したら、`Generate and Download`で画像を生成し、ダウンロード
    - ダウンロードがうまくいかない場合は`Generate and Open new tab`で、新しいタブで画像を開き、長押しや右クリックして保存

## Requirement
  - PC,かスマートフォン
  - Webブラウザ
    - Chrome, Firefox, Safari
    - HTML5に対応していること
    - JavaScript: ON (required)

## Dependency
  - [jQuery](https://jquery.com/)
    - version 3.6.0
    - [CDN](https://ajax.googleapis.com/ajax/libs/jquery/3.6.0/jquery.min.js)
  - [html2canvas](https://html2canvas.hertzen.com/)
    - version 1.4.1
    - [CDN](https://cdn.jsdelivr.net/npm/html2canvas@1.4.1/dist/html2canvas.min.js)
  - [Bootstrap(SCSS)](https://github.com/twbs/bootstrap)
    - [v5.1.3](https://github.com/twbs/bootstrap/tree/v5.1.3)
    - Build-in `bootstrap/scss/` here

## License
MIT License

## Contributor
Special Thanks!!イカれたメンバーを紹介するぜ！

<div align="center">
  <a href="https://trpfrog.net"><img src="https://avatars.githubusercontent.com/u/7621012?v=4?s=100" width="100px;" alt=""/><br>
    <sub>
      <b>つまみ-TrpFrog</b>
    </sub>
  </a>
</div>

## Memo
### `css/custom.css`
Compile `scss/custom.scss` to `css/custom.css` after editing `scss/custom.scss`.
