<template>
  <nav class="navigation">
    <ul class="navigation__container">
      <li class="navigation__item">
        <a href="#" class="navigation__link">Home</a>
      </li>
      <li class="navigation__item">
        <a href="" class="navigation__link">Home</a>
      </li>
    </ul>
  </nav>
</template>

<script setup></script>

<style lang="scss" scoped>
.navigation {
  background-color: var(--main-color);
  width: 100vw; // occupe toute la largeur visible du viewport
  margin-left: calc(-1 * var(--side-padding)); // annule le padding du body
  margin-right: calc(-1 * var(--side-padding));
  display: flex;
  justify-content: center;

  &__container {
    display: flex;
    gap: 30px;
    padding: 10px 0;
  }

  &__item {
    background-color: aqua;
  }

  &__link {
    text-decoration: none;
    color: white;
  }
}
</style>
