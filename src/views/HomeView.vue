<script setup lang="ts">

</script>

<template>
 <div class="wrapper">
      <img src="/src/assets/welcome-home.gif" height="200" width="" />
      <br />
      <div class="title">
        welcome home, manchi
      </div>
      <div class="content">
        Finally, a writing app hacked just for you! Time to crank out some epic content.<br>
        Just adding a random second line to keep things looking legit.
      </div>
      <button id="home__button">
        <router-link class="orange" to="/select"> let’s get writing.</router-link>
      </button>
      <div class="home__footer">
        built by mosessmax. on vuejs3 + typescript
      </div>
    </div>
</template>
