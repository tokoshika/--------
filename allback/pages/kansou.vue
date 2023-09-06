<template>
  <div class="main">
    <h3 class="title">
      強風オールバック(<span style="color: tomato">間奏</span>)
    </h3>
    <div class="full">
      <div class="ht-e">
        <div class="ht-e"><p style="background-color: red">レ</p></div>
        <img src="~/assets/ht-e.png" class="unshi" alt="" />
      </div>
      <div class="ht-e">
        <div class="mi"><p style="background-color: green">ラ</p></div>
        <img src="~/assets/n-a.png" class="unshi" alt="" />
      </div>
      <div class="ht-e">
        <div class="mi"><p>ミ</p></div>
        <img src="~/assets/h-e.png" class="unshi" alt="" />
      </div>
      <div class="ht-e">
        <div class="mi"><p>レ</p></div>
        <img src="~/assets/h-d.png" class="unshi" alt="" />
      </div>
      <div class="ht-e">
        <div class="mi"><p>ソ</p></div>
        <img src="~/assets/h-g.png" class="unshi" alt="" />
      </div>
      <div class="ht-e">
        <div class="mi"><p>ラ</p></div>
        <img src="~/assets/h-a.png" class="unshi" alt="" />
      </div>
    </div>
    <div class="phrase">
      <div class="phrase1">
        <div><p style="background-color: red">レ</p></div>
        <div>..</div>
        <div><p>ミ</p></div>
        <div>..</div>
        <div><p>レ</p></div>
        <div><p>ミ</p></div>
        <div><p>ミ</p></div>
        <div>..</div>
        <div><p>レ</p></div>
        <div><p>ミ</p></div>
        <div><p>ミ</p></div>
        <div>..</div>
        <div><p>レ</p></div>
        <div><p>ミ</p></div>
        <div><p>ミ</p></div>
        <div><p>ソ</p></div>
      </div>
      <div class="phrase2">
        <div><p style="background-color: red">レ</p></div>
        <div>..</div>
        <div><p>ミ</p></div>
        <div>..</div>
        <div><p>レ</p></div>
        <div><p>ミ</p></div>
        <div><p style="background-color: green">ラ</p></div>
        <div>..</div>
        <div><p>レ</p></div>
        <div><p>ミ</p></div>
        <div><p>ミ</p></div>
        <div>..</div>
        <div><p>レ</p></div>
        <div><p>ミ</p></div>
        <div><p>ミ</p></div>
        <div><p>ソ</p></div>
      </div>
      <div class="phrase3">
        <div><p style="background-color: red">レ</p></div>
        <div>..</div>
        <div><p>ミ</p></div>
        <div>..</div>
        <div><p>レ</p></div>
        <div><p>ミ</p></div>
        <div><p>ミ</p></div>
        <div>..</div>
        <div><p>レ</p></div>
        <div><p>ミ</p></div>
        <div><p>ミ</p></div>
        <div>..</div>
        <div><p>レ</p></div>
        <div><p>ミ</p></div>
        <div><p>ミ</p></div>
        <div><p>ソ</p></div>
      </div>
      <div class="phrase4">
        <div><p style="background-color: red">レ</p></div>
        <div>..</div>
        <div><p>ミ</p></div>
        <div>..</div>
        <div><p>レ</p></div>
        <div><p>ミ</p></div>
        <div><p>ミ</p></div>
        <div>..</div>
        <div><p>レ</p></div>
        <div><p>ミ</p></div>
        <div><p>ソ</p></div>
        <div><p>ラ</p></div>
        <div><p>ソ</p></div>
        <div><p style="background-color: white">ソ</p></div>
        <div><p style="background-color: white">ソ</p></div>
        <div class="white">..</div>
      </div>
    </div>
  </div>
</template>

<style scoped>
  .title,
  .full,
  .phrase1,
  .phrase2,
  .phrase3,
  .phrase4 {
    justify-content: center;
    text-align: center;
  }

  .phrase1,
  .phrase2,
  .phrase3,
  .phrase4,
  .full {
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
  }

  .unshi {
    width: 50%;
  }

  .white {
    color: white;
  }
</style>
