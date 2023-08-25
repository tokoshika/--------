<template>
  <div class="main">
    <h3 class="title">強風オールバック(Bメロ)</h3>
    <div class="unshi">
      <img src="~/assets/unshi.png" />
      <!-- <img src="~/assets/si.png" class="sias" /> -->
    </div>
    <div class="phrase">
      <div class="phrase1">
        <div><p>シ</p></div>
        <div>..</div>
        <div><p class="mi">ミ</p></div>
        <div><p class="re">レ</p></div>
        <div>..</div>
        <div><p>ラ</p></div>
        <div><p>シ</p></div>
        <div><p>シ</p></div>
        <div><p>シ</p></div>
        <div><p>ラ</p></div>
        <div><p>ソ</p></div>
        <div>..</div>
        <div>..</div>
        <div><p class="re">レ</p></div>
        <div>..</div>
        <div><p>ラ</p></div>
        <div><p>シ</p></div>
        <div><p>シ</p></div>
        <div><p>シ</p></div>
        <div><p class="mi">ミ</p></div>
        <div><p class="re">レ</p></div>
      </div>
      <div class="phrase1">地下にもぐりたいなっ・・・て、思いました</div>
      <div class="phrase2">
        <div><p>シ</p></div>
        <div>..</div>
        <div><p>シ</p></div>
        <div><p class="mi">ミ</p></div>
        <div><p class="re">レ</p></div>
        <div>..</div>
        <div><p>シ</p></div>
        <div><p>シ</p></div>
        <div><p>シ</p></div>
        <div><p>ラ</p></div>
        <div><p>ソ</p></div>
        <div>..</div>
        <div>..</div>
        <div>..</div>
        <div><p>ラ</p></div>
        <div><p>シ</p></div>
        <div><p>シ</p></div>
        <div><p>シ</p></div>
        <div><p>ラ</p></div>
        <div><p>ソ</p></div>
      </div>
      <div class="phrase1">風さえ、なくなれば・・・・あったかいのに</div>
      <div class="phrase3">
        <div><p>シ</p></div>
        <div>..</div>
        <div><p class="mi">ミ</p></div>
        <div><p class="re">レ</p></div>
        <div>..</div>
        <div><p>ラ</p></div>
        <div><p>シ</p></div>
        <div><p>シ</p></div>
        <div><p>シ</p></div>
        <div><p>ラ</p></div>
        <div><p>ソ</p></div>
        <div>..</div>
        <div>..</div>
        <div><p class="re">レ</p></div>
        <div>..</div>
        <div><p>ラ</p></div>
        <div><p>シ</p></div>
        <div><p>シ</p></div>
        <div><p>シ</p></div>
        <div><p class="mi">ミ</p></div>
        <div><p class="re">レ</p></div>
      </div>
      <div class="phrase1">ずっと座りたいな・・・って思いました</div>
      <div class="phrase4">
        <div><p>シ</p></div>
        <div><p>シ</p></div>
        <div><p class="mi">ミ</p></div>
        <div><p class="re">レ</p></div>
        <div>..</div>
        <div><p class="re">レ</p></div>
        <div><p class="mi">ミ</p></div>
        <div><p class="mi">ミ</p></div>
        <div><p class="mi">ミ</p></div>
        <div><p class="so">ソ</p></div>
        <div><p class="si">シ</p></div>
        <div>..</div>
      </div>
      <div class="phrase1">いやいやと外でたら・・・</div>
      <div class="phrase5">
        <div><p class="ra">ラ</p></div>
        <div><p class="so">ソ</p></div>
        <div><p class="ra">ラ</p></div>
        <div><p class="so">ソ</p></div>
        <div><p class="ra">ラ</p></div>
        <div><p class="so">ソ</p></div>
        <div><p class="ra">ラ</p></div>
        <div><p class="so">ソ</p></div>
        <div><p class="mi">ミ</p></div>
        <div><p class="so">ソ</p></div>
        <div><p class="black">フ#</p></div>
        <div><p class="re">レ</p></div>
        <div><p class="mi">ミ</p></div>
      </div>
      <div class="phrase1">ハト・ハト・ハト・ハト大乱闘</div>
    </div>
  </div>

  <br />
  <br />
</template>

<style scoped>
  .unshi,
  .title,
  .phrase1,
  .phrase2,
  .phrase3,
  .phrase4,
  .phrase5 {
    justify-content: center;
    text-align: center;
  }
  .title,
  .unshi,
  .phrase1,
  .phrase2,
  .phrase3,
  .phrase4,
  .phrase5 {
    display: flex;
  }

  p {
    display: inline-block;
    width: 30px;
    height: 30px;
    color: white;
    background-color: black;
    border-radius: 40px;
    margin-left: 0.5rem;
    margin-right: 0.5rem;
    text-align: center;
    line-height: 30px;
    font-family: "Zen Maru Gothic", sans-serif;
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
