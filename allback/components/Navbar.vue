<template>
  <nav>
    <ul class="nav">
      <li>
        <NuxtLink to="/" style="color: green; text-decoration: none"
          >ホーム</NuxtLink
        >
      </li>
      <li>
        <NuxtLink to="/amelo" style="color: green; text-decoration: none"
          >Aメロ</NuxtLink
        >
      </li>
      <li class="color">
        <NuxtLink to="/kansou" style="color: green; text-decoration: none"
          >間奏</NuxtLink
        >
      </li>
      <li>
        <NuxtLink to="/bmelo" style="color: green; text-decoration: none"
          >Bメロ</NuxtLink
        >
      </li>
      <li>
        <NuxtLink to="/youtube" style="color: tomato; text-decoration: none"
          >YouTube見本</NuxtLink
        >
      </li>
    </ul>
  </nav>

  <slot />
</template>

<style>
  .nav {
    display: flex;
    justify-content: space-between;
    margin-left: 2rem;
    margin-right: 2rem;
    list-style: none;
    background-color: rgb(233, 223, 223);
    text-align: center;
  }

  li {
    margin-right: 3rem;
  }

  .color {
    text-decoration: none;
  }
</style>
