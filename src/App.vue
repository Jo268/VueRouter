<template>
  <div>
  <div id="nav">
    <router-link to="/">Home</router-link>
    <router-link to="/brazil">Brazil</router-link>
    <router-link to="/hawaii">Hawaii</router-link>
    <router-link to="/jamaica">Jamaica</router-link>
    <router-link to="/panama">Panama</router-link>
  </div>
  <div class="container">
  <router-view></router-view>
  </div>
  </div>
</template>

<script></script>

<style>
.container{
  border: 2px gray;
}
</style>