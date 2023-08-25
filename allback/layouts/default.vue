<template>
  <nav>
    <ul class="nav">
      <li class="color">
        <NuxtLink to="/" style="color: rgb(48, 159, 38); text-decoration: none"
          >リコーダー</NuxtLink
        >
      </li>

      <li>
        <NuxtLink to="/main" style="color: green; text-decoration: none"
          >Aメロ</NuxtLink
        >
      </li>
      <li>
        <NuxtLink to="/bmelo" style="color: green; text-decoration: none"
          >Bメロ</NuxtLink
        >
      </li>
      <li>
        <NuxtLink to="/youtube" style="color: red; text-decoration: none"
          >YouTube</NuxtLink
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
  }

  li {
    margin-left: 0.3rem;
    margin-right: 0.3rem;
  }

  .color {
    text-decoration: none;
  }
</style>
