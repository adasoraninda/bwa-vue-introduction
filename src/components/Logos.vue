<template>
  <div class="logos-wrapper">
    <h2 class="header-title">Find Best Logos</h2>
    <div class="item-logos">
      <img class="img-logo" src="../assets/kfc-logo.svg" alt="kfc-logo" />
    </div>
    <div class="item-logos">
      <img class="img-logo" src="../assets/starbucks-logo.svg" alt="kfc-logo" />
    </div>
    <div class="item-logos">
      <img class="img-logo" src="../assets/kfc-logo.svg" alt="kfc-logo" />
    </div>
    <div class="item-logos">
      <img class="img-logo" src="../assets/starbucks-logo.svg" alt="kfc-logo" />
    </div>
    <div class="item-logos">
      <img class="img-logo" src="../assets/kfc-logo.svg" alt="kfc-logo" />
    </div>
    <div class="item-logos">
      <img class="img-logo" src="../assets/starbucks-logo.svg" alt="kfc-logo" />
    </div>
  </div>
</template>

<script>
export default {
  name: "Logos",
};
</script>

<style scoped>
.header-title {
  margin-bottom: 40px;
  color: white;
  text-align: left;
}

.logos-wrapper {
  width: 60%;
  overflow: hidden;
  margin: auto;
  background: teal;
}

.item-logos {
  float: left;
  margin: 0 70px 70px 0;
  width: 150px;
  height: 150px;
}

.item-logos .img-logo {
  width: 150px;
  height: 150px;
}
</style>
