# Transform Rotate Angle Slider (Vanilla JS)
指定した角度での分割配置 + スライダー機能をJavaScriptで実装したサンプルです。

#### デモ
https://codepen.io/sakata-kazuma/pen/YzaowJw


### 設定

```html
<div class="js-angle-slider">
  <!--
    prev,nextボタン
  -->
  <div class="js-angle-slider__pager">
    <button class="js-angle-slider__prev" type="button">
      prev
    </button>
    <button class="js-angle-slider__next" type="button">
      next
    </button>
  </div>
  <!--
      .js-angle-slider内でドットナビゲーションを
      任意の場所に出力したい場合は以下のdivを追加する
      <div class="js-angle-slider__dots"></div>

      （無い場合は .js-angle-slider__bodyの末尾に追加される）
  -->
  <div class="js-angle-slider__body">
    <!--
      data-slide-angle="12"：分割する角度
      data-show="7"：画面内に表示させる枚数
      data-speed="400"：next,prevボタン、ドラッグ後の移動スピード
      data-drag-speed-ratio="0.1"：ドラッグ中の移動スピード
      data-dots="true"：ドットナビゲーション表示
    -->
    <div class="js-angle-slider__list" data-slide-angle="12" data-show="7" data-speed="400" data-drag-speed-ratio="0.1" data-dots="true">
      <div class="js-angle-slider__item">slide1</div>
      <div class="js-angle-slider__item">slide2</div>
      <div class="js-angle-slider__item">slide3</div>
    </div>
  </div>
</div>
```

　

### 動作環境
Google Chrome 最新版
Firefox 最新版
Safari 最新版
