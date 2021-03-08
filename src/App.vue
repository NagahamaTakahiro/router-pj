<template>
  <div class="home">
    <router-link :to="{name:'Home'}">Home</router-link>
    <p>|</p>
    <router-link :to="{name:'Member'}">About</router-link>
    <h2>2</h2>
  </div>
</template>

<script>
export default {
  methods: {
    transition() {
      this.$router.push({ name: "Member" });
    }
  }
};
</script>

<style scoped>
.home {
  text-align: center;
}

.home router-link {
  display: flex;
  margin: 0px;
}

.home p {
  display: flex;
  margin: 0px;
}

</style>