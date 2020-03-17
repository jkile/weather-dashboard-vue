<template>
  <div>
    <div class="columns is-vcentered">

      <Search/>

      <div class="display-wrapper">
        <div class="column">
          <div class="columns">
            <div class="column">
              <div class="box" id="weather-display"></div>
            </div>
          </div>
          <div class="columns">
            <div class="column">
              <h1 class="is-size-2">5-Day Forecast:</h1>
            </div>
          </div>
          <div class="columns" id="forecastRow"></div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Search from "./Search.vue";
export default {
  name: "Dashboard",
  props: {
    msg: String
  },
  components: {
    Search
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
html {
  height: 100%;
}
body {
  min-height: 100%;
}
.column {
  flex-direction: column;
  padding: 12px;
}
p {
  margin: 12px;
}
.menu-wrapper {
  padding-left: 10px;
}
.display-wrapper {
  padding-right: 10px;
}

.wrapper {
  padding: 12px;
}

.rounded {
  border-radius: 15%;
}
.stretch {
  min-height: 100%;
}
</style>
