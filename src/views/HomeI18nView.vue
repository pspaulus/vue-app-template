<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloI18n/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloI18n from "@/components/HelloI18n";

export default {
  name: 'HomeI18nView',
  components: {
    HelloI18n
  }
}
</script>
