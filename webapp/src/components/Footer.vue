<template>
    <div id="foot">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link> |
      <router-link to="/myaccount">My Account</router-link> |
      <router-link to="/">Tracking</router-link> |
      (805)-321-2831
    </div>
</template>

<script>
export default {
    name: "Footer"
}
</script>

<style scoped>
#foot {
  position: fixed;
  bottom: 0px;
  left: 0;
  padding: 15px;
  width: 100%;
  background-color: rgba(66, 34, 16, 0.8);
  border-top: solid 1px #7aa256;
  color: #cc783c;
}

#foot a {
  color: #cc783c;
}
</style>