<template>
  <div class="column has-background-light is-flex is-one-third">
    <div class="menu-wrapper" id="menu">
      <h1 class="is-size-2">Search for a City:</h1>
      <div class="field is-grouped">
        <p class="control is-expanded">
          <input class="input" type="text" id="searchBox" placeholder="Enter City" />
        </p>
        <p class="control">
          <button class="button is-info" id="searchButton">Search</button>
        </p>
      </div>
      <button class="button is-large is-fullwidth">Austin</button>
      <button class="button is-large is-fullwidth">Chicago</button>
      <button class="button is-large is-fullwidth">New York</button>
      <button class="button is-large is-fullwidth">Orlando</button>
      <button class="button is-large is-fullwidth">San Francisco</button>
      <button class="button is-large is-fullwidth">Seattle</button>
      <button class="button is-large is-fullwidth">Denver</button>
      <button class="button is-large is-fullwidth">Atlanta</button>
    </div>
  </div>
</template>

<script>
export default {
    name: "Search"
};
</script>

<style lang="stylus" scoped></style>