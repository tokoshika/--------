<template>
  <nav>
    <ul class="nav">
      <li>
        <NuxtLink to="/main" style="color: green; text-decoration: none"
          >Aメロ</NuxtLink
        >
      </li>
      <li class="color">
        <NuxtLink to="/" style="color: green; text-decoration: none"
          >間奏</NuxtLink
        >
      </li>
      <li>
        <NuxtLink to="/bmelo" style="color: green; text-decoration: none"
          >Bメロ</NuxtLink
        >
      </li>
      <li>
        <NuxtLink to="/youtube" style="color: red; text-decoration: none"
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
    list-style: none;
    background-color: rgb(233, 223, 223);
  }

  li {
    margin-left: 0.3rem;
    margin-right: 0.3rem;
  }

  .color {
    text-decoration: none;
  }
</style>
