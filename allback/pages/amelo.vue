<template>
  <div class="main">
    <h3 class="title">強風オールバック(<span style="color:tomato">Aメロ</span>)</h3>
    <div class="unshi">
      <img src="~/assets/unshi02.png" />
    </div>
    <div class="phrase">
      <div class="phrase1">
        <div><p class="si">シ</p></div>
        <div>..</div>
        <div><p class="mi">ミ</p></div>
        <div><p class="mi">ミ</p></div>
        <div>..</div>
        <div><p class="re">レ</p></div>
        <div><p class="re">レ</p></div>
        <div><p class="mi">ミ</p></div>
        <div><p class="mi">ミ</p></div>
        <div>..</div>
        <div><p class="mi">ミ</p></div>
        <div><p class="so">ソ</p></div>
        <div>..</div>
        <div><p class="si">シ</p></div>
        <div><p class="ra">ラ</p></div>
      </div>
      <div class="phrase1">外でた瞬間終わったわ</div>
      <div class="phrase2">
        <div><p class="mi">ミ</p></div>
        <div>..</div>
        <div><p class="mi">ミ</p></div>
        <div><p class="mi">ミ</p></div>
        <div><p class="re">レ</p></div>
        <div>..</div>
        <div><p class="mi">ミ</p></div>
        <div>..</div>
        <div><p class="mi">ミ</p></div>
        <div><p class="black">レ#</p></div>
        <div>..</div>
        <div><p class="mi">ミ</p></div>
        <div><p class="so">ソ</p></div>
        <div><p class="black">フ#</p></div>
        <div><p class="re">レ</p></div>
        <div><p style="background-color: black">シ</p></div>
        <div><p class="mi">ミ</p></div>
      </div>
      <div class="phrase1">天気は良いのに進めない風</div>
      <div class="phrase3">
        <div><p class="si">シ</p></div>
        <div>..</div>
        <div><p class="mi">ミ</p></div>
        <div><p class="re">レ</p></div>
        <div><p class="re">レ</p></div>
        <div><p class="mi">ミ</p></div>
        <div><p class="mi">ミ</p></div>
        <div>..</div>
        <div><p class="mi">ミ</p></div>
        <div><p class="so">ソ</p></div>
        <div><p class="so">ソ</p></div>
        <div><p class="ra">ラ</p></div>
        <div><p class="si">シ</p></div>
      </div>
      <div class="phrase1">強すぎてお亡くなり</div>
      <div class="phrase4">
        <div><p class="mi">ミ</p></div>
        <div><p class="re">レ</p></div>
        <div><p class="mi">ミ</p></div>
        <div><p class="re">レ</p></div>
        <div><p class="mi">ミ</p></div>
        <div><p class="so">ソ</p></div>
        <div><p class="ra">ラ</p></div>
        <div><p class="si">シ</p></div>
        <div><p class="ra">ラ</p></div>
        <div><p class="so">ソ</p></div>
        <div><p class="black">フ#</p></div>
        <div><p class="re">レ</p></div>
        <div><p class="mi">ミ</p></div>
      </div>
      <div class="phrase1">定期定期的にオールバック</div>
    </div>
  </div>
</template>

<style scoped>
  h3 {
    margin-bottom: 0;
    font-family: 'Zen Maru Gothic';
  }

  .unshi,
  .title,
  .phrase1,
  .phrase2,
  .phrase3,
  .phrase4 {
    justify-content: center;
    text-align: center;
  }
  .title,
  .unshi,
  .phrase1,
  .phrase2,
  .phrase3,
  .phrase4 {
    display: flex;
  }

  p {
    display: inline-block;
    width: 30px;
    height: 30px;
    color: white;
    background-color: green;
    border-radius: 40px;
    margin-left: 0.5rem;
    margin-right: 0.5rem;
    text-align: center;
    line-height: 30px;
    font-family: "Zen Maru Gothic",;
    font-size: 1.2rem;
  }

  .si {
    background-color: mediumvioletred;
  }
  .mi {
    background-color: orangered;
  }

  .re {
    background-color: greenyellow;
    color: gray;
  }

  .so {
    background-color: mediumblue;
  }

  .sias {
    width: 3%;
  }

  .ra {
    background-color: springgreen;
    color: gray;
  }
  .black {
    background-color: black;
    font-size: 1rem;
  }
</style>
